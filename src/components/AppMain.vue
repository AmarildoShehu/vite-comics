<script>
import AppBluePart from './AppBluePart.vue';
export default {
    name: 'AppMain',
    data: () => ({
    }),
    components: {
        AppBluePart
    }

}
</script>
<template>
    <main>
        <div class="bg-myblack">
            <section class="container content">
                <p>
                    --- Content goes here --- </p>
            </section>
        </div>
        <AppBluePart />


    </main>
</template>
<style scoped>
main {
    background-color: #1C1C1C;
    color: white;
}

.content {
    height: 100px;
}

.bg-myblack {
    background-color: #1C1C1C;
}
</style>