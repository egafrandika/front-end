<script>

    export default {
        name: 'App'
  
    }

</script>

<template>
    <div class="flex md:flex-row-reverse">
        <div class="py-18 w-full md:w-3/4 p-7 bg-scroll bg-sky-500 font-medium text-sm text-black">
            <ul class="flex justify-end space-x-7 pr-32 pt-6">
                <li>Home</li>
                <li>Borrower</li>
                <li>Lender</li>
                <li>About Us</li>
                <li>FAQ</li>
                <li>|</li>
                <li class="space-x-2"><font-awesome-icon icon="fa-solid fa-store" /><span>Easywarung</span></li>
                <label for="togglesix" class="flex items-center cursor-pointer select-none">
                    <div class="relative">
                        <input type="checkbox" id="toggleSix" class="sr-only">
                        <div class="box block bg-primary w-14 h-8 rounded-full"></div>
                        <div class="dot absolute left-1 top-1 bg-white w-6 h-6 rounded-full transition flex items-center justify-center"></div>
                    </div>
                </label>
            </ul>
        </div>
        <div class="w-full md:w-1/4 bg-gray-400 p-16 text-gray-700 pl-32">
            <ul>
                <li>logo</li>
            </ul>
        </div>
    </div>

</template>