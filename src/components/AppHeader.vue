<script>
export default {
    name: 'AppHeader',
    data: () => ({
        links: [
            {
                text: 'Characters',
                url: '#',
                current: false,
            },
            {
                text: 'Comics',
                url: '#',
                current: true,
            },
            {
                text: 'Movies',
                url: '#',
                current: false,
            },
            {
                text: 'TV',
                url: '#',
                current: false,
            },
            {
                text: 'Games',
                url: '#',
                current: false,
            },
            {
                text: 'Collectibles',
                url: '#',
                current: false,
            },
            {
                text: 'Videos',
                url: '#',
                current: false,
            },
            {
                text: 'Fans',
                url: '#',
                current: false,
            },
            {
                text: 'News',
                url: '#',
                current: false,
            },
            {
                text: 'Shop',
                url: '#',
                current: false,
            },
        ]
    })
}
</script>
<template>
    <header class="d-flex">
        <div class="container d-flex flex-between align-center">
            <figure>
                <a href="#"><img src="../assets/img/dc-logo.png" alt=""></a>
            </figure>
            <nav>
                <ul class="d-flex">
                    <li v-for="link in links"><a :href="link.url" :class="{ active: link.current }">{{ link.text }}</a></li>
                </ul>
            </nav>


        </div>
    </header>
</template>

<style>
header {
    background-color: #ffffff;
    height: 100px;
    text-align: center;
}

figure {
    height: 80px;
}

figure a img {
    height: 100%;
}

ul {
    list-style: none;
    gap: 10px;
}

li a {
    padding: 5px;
    text-decoration: none;
}

ul li a {
    font-weight: bold;
    text-transform: uppercase;
    color: #484848;
    padding: 36px 0;
}

ul li a:hover,
ul li a.active {
    color: #0282F9;
    border-bottom: 5px solid #0282F9;
}
</style>