<script>
    import image1 from './assets/image1.png'
    import image2 from './assets/image2.png'
    
    export default {
        data: function() {
            return {
                image1: image1,
                image2: image2,
                selected: ''
            }
        }
  
    }

</script>

<template>
    <div class="flex md:flex-row-reverse">
        <div class="w-full md:w-3/4 bg-scroll bg-white font-medium text-sm text-black pb-12">
            <ul class="flex justify-end space-x-7 pr-32 pt-12">
                <li class="cursor-pointer hover:text-gray-600">Home</li>
                <li class="cursor-pointer hover:text-gray-600">Borrower</li>
                <li class="cursor-pointer hover:text-gray-600">Lender</li>
                <li class="cursor-pointer hover:text-gray-600">About Us</li>
                <li class="cursor-pointer hover:text-gray-600">FAQ</li>
                <li>|</li>
                <li class="space-x-2 cursor-pointer hover:text-gray-600"><font-awesome-icon icon="fa-solid fa-store" /><span>Easywarung</span></li>
                <span class="hidden">{{ selected }}</span>
                <div class="border-2 border-black px-4 py-1 -mt-1 rounded-full">
                    <select class="appearance-none" v-model="selected">
                        <option>IN</option>
                        <option>EN</option>
                    </select>
                </div>
            </ul>
        </div>
        <div class="w-full md:w-1/4 bg-white text-black pt-9 pl-32">
            <div class="flex flex-row items-center space-x-1">
                <img class="h-11 w-17" :src="image1"/>
                <img class="h-7 w-25" :src="image2"/>
            </div>
        </div>
    </div>
</template>