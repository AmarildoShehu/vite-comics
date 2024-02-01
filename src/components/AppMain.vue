<script>
export default {
    name: 'AppMain',
    data: () => ({
    }),
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

        <div class="bg-myblue">
            <section class="container digital">
                <p>hello</p>
            </section>
        </div>

    </main>
</template>
<style>
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




.digital {
    color: white;
    height: 100px;
}

.bg-myblue {
    background-color: #0282F9;
}
</style>