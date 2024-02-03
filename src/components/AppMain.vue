<script>
import AppJumbotron from './main-components/AppJumbotron.vue';
import AppBarrel from './main-components/AppBarrel.vue';
import AppBluePart from './main-components/AppBluePart.vue';
export default {
    name: 'AppMain',
    data: () => ({
    }),
    components: {
        AppJumbotron,
        AppBarrel,
        AppBluePart
    }

}
</script>
<template>
    <main>
        <AppJumbotron />
        <AppBarrel />
        <AppBluePart />
    </main>
</template>
<style scoped>
main {
    background-color: #1C1C1C;
    color: white;
    padding-bottom: ;
}

.content {
    height: 100px;
}

.bg-myblack {
    background-color: #1C1C1C;
}
</style>