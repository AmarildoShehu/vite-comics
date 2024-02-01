<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
    name: 'MyApp',
    data: () => ({
    }),
    components: {
        AppHeader,
        AppMain,
        AppFooter,
    }
}
</script>

<template>
    <AppHeader />
    <AppMain />
    <AppFooter />
</template>

<style>
/* Generics */
* {
    margin: 0;
    padding: 0;
}

/* Utils */
.container {
    margin: 0 auto;
    width: 800px;
    border: 2px solid black;
}

/* Utils Flex */
.d-flex {
    display: flex;
}

.flex-between {
    justify-content: space-between;
}

.align-center {
    align-items: center;
}
</style>