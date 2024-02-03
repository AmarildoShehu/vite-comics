<script>
import AppBarrel from './AppBarrel.vue';
import AppBluePart from './AppBluePart.vue';
export default {
    name: 'AppMain',
    data: () => ({
    }),
    components: {
        AppBarrel,
        AppBluePart
    }

}
</script>
<template>
    <main>
        <AppBarrel />
        <AppBluePart />
    </main>
</template>
<style scoped>
main {
    background-color: #1C1C1C;
    color: white;
    padding-bottom: 2rem;
}

.content {
    height: 100px;
}

.bg-myblack {
    background-color: #1C1C1C;
}
</style>