<script>
export default {
    name: 'AppFooter',
    data: () => ({
    }),
}
</script>

<template>
    <footer>
        <section id="upfooter">
            <div class="container d-flex flex-between">
                <div class="upleft">
                    <div>
                        <h4>DC Comics</h4>
                        <ul>
                            <li></li>
                        </ul>
                    </div>
                    <div>
                        <h4>SHOP</h4>
                        <ul>
                            <li></li>
                        </ul>
                    </div>
                    <div>
                        <h4>DC/h4>
                            <ul>
                                <li></li>
                            </ul>
                        </h4>
                    </div>
                    <div>
                        <h4>Sites</h4>
                        <ul>
                            <li></li>
                        </ul>
                    </div>
                </div>
                <div class="upright"></div>
            </div>
        </section>
        <section id="downfooter">
            <div class="container d-flex flex-between">
                <div>sign up now</div>
                <div>Follow us</div>
            </div>
        </section>
    </footer>
</template>

<style>
footer {
    max-height: 400px;
}

#upfooter {
    background-image: url(../assets/img/footer-bg.jpg);
    height: 300px;
    position: relative;
}

.upleft {
    width: 100px;
    height: 300px;
    border: 1px solid black;
}

.upright {
    width: 50%;
    height: 300px;
    background-image: url(../assets/img/dc-logo-bg.png);
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}

#downfooter {
    background-color: #303030;
    height: 100px;
}
</style>