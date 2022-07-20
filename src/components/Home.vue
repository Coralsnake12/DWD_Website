<template>
    <div class="bg-image">
            <div class="container px-4 px-lg-5 vh-100">
                <div class="row gx-4 gx-lg-5 h-100 align-items-center justify-content-center text-center">
                    <Navbar />
                    <div class="col-lg-8 align-self-end">
                        <h1 class="font-weight-bold">Welcome to my Website</h1>
                        <hr class="divider" />
                    </div>
                    <div class="col-lg-8 align-self-baseline">
                        <p class="text-white-75 mb-5">Start Bootstrap can help you build better websites using the Bootstrap framework! Just download a theme and start customizing, no strings attached!</p>
                        <a class="btn btn-primary btn-xl" href="#about">Find Out More</a>
                    </div>
                </div>
            </div>
    </div>
</template>



<script>
import Navbar from './navbar.vue'

export default {
    name: 'Home',
    components: {
        Navbar,
    }
}
</script>

<style>

.bg-image {
    background-image: url('../assets/home_page.jpg');
}

</style>