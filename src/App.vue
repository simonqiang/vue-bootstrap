<template>
    <div id="app" style="background-color: #f8f9fa">
        <Menu/>
        <div class="container">
            <div class="row">
                <TopList class="col mr-3 d-none d-xl-flex"/>
                <TopList class="col mr-3 d-none d-lg-flex"/>
                <TopList class="col d-none d-sm-flex"/>
            </div>
            <div class="row">
                <MainVideoTab style="background-color: white; " class="mt-3"/>
            </div>
        </div>

    </div>
</template>

<script>
    // import HelloWorld from './components/HelloWorld.vue'
    import Menu from "./components/Menu";
    import MainVideoTab from "./components/MainVideoTab";
    import TopList from "./components/TopList";

    export default {
        name: 'App',
        components: {
            TopList,
            // HelloWorld
            Menu,
            MainVideoTab
        }
    }
</script>

<style scoped>
    mybody {
        background-color: yellow;

    }
</style>
