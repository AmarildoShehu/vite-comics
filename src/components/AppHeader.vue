<script>
export default {
    name: 'AppHeader',
    data: () => ({
    }),
}
</script>
<template>
    <header>
        <div class="container d-flex flex-between align-center">
            <div>
                <img src="../assets/img/dc-logo.png" alt="">
            </div>
            <div>
                <ul class="d-flex">
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                </ul>
            </div>


        </div>
    </header>
</template>

<style>
header {
    background-color: aqua;
}

ul {
    list-style: none;
}

li a {
    padding: 5px;
    text-decoration: none;
}
</style>