<script setup>
    import Navbar from '../components/Home/Navbar.vue';
    import GetStarted from '../components/Home/GetStarted.vue';
</script>

<template>
    <div class="homePage">
        <Navbar />
        <main>
            <GetStarted />
        </main>
    </div>
</template>

<style scoped>
    .homePage {
        width: 100vw;
        height: 100vh;
    }
</style>