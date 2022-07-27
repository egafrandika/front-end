<script>
    import image3 from './assets/bg.jpg'

    export default {
        data: function() {
            return {
                image3: image3
            }
        }
    }

</script>
<template>
    <div>   
        <img class="object-cover fixed" :src="image3"/>
    </div>

    <article class="absolute flex flex-col">
        <h1 class="pl-32 pt-30 mt-20 text-lg font-bold text-left text-amber-500">TKB90=100%</h1>
        <p class="pl-32 mb-5 mt-5 text-5xl font-bold tracking-wide">Enjoy Easy Life With Easycash</p>
        <p class="pl-32 text-left">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nulla dolore vero officiis aperiam, dolor nesciunt autem. Enim ipsum accusantium officia.</p>
    </article>
</template>