<template>
    <div>
        <Logo />
        <NavBar />
    </div>
</template>

<script>
    import Logo from './Logo.vue';
    import NavBar from './NavBar.vue'
    export default {
        name: "AppHeader",
        components: {
            Logo,
            NavBar,
        },
    }
</script>

<style lang="scss" scoped>

</style>