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
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: 'Open Sans', sans-serif;
}

/* Utils */
.container {
    margin: 0 auto;
    width: 1000px;

}


img {
    max-width: 100%;
}

ul {
    list-style: none;
}

a {
    text-decoration: none;
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