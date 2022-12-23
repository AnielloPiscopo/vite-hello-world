<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
import AppFooter from './components/AppFooter.vue';


export default {
    components: {
        AppTitle,
        AppHero,
        AppFooter,
    }
}
</script>

<template>
    <AppTitle />
    <AppHero />
    <AppFooter />
</template>

<style>
#app {
    margin: 5rem;
    background-color: var(--body-parts--bg-color);
}

#app>* {
    padding-bottom: 2rem;
}
</style>
