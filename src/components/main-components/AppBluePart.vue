<script>
export default {
    name: 'AppBluePart',
    data: () => ({
    }),
}
</script>
<template>
    <div class="bg-myblue">
        <section class="container digital d-flex align-center justify-content-center">
            <ul class="d-flex align-center">
                <li class="d-flex align-center"><img src="../../assets/img/buy-comics-digital-comics.png">DIGITAL COMICS
                </li>
                <li class="d-flex align-center"><img src="../../assets/img/buy-comics-merchandise.png">DC merchandise</li>
                <li class="d-flex align-center"><img src="../../assets/img//buy-comics-subscriptions.png">subscriptions</li>
                <li class="d-flex align-center"><img src="../../assets/img/buy-comics-shop-locator.png">comics shop locator
                </li>
                <li class="d-flex align-center"><img src="../../assets/img/buy-dc-power-visa.svg">DC power-visa</li>
            </ul>
        </section>
    </div>
</template>
<style scoped>
.bg-myblue {
    background-color: #0282F9;
}

.digital {
    width: 90%;
    color: white;
    height: 100px;
}

.digital img {
    height: 40px;
}


li {
    padding: 10px;
    gap: 1rem;

    text-transform: uppercase;
    font-size: 0.75rem;
}
</style>