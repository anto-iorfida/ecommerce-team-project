<script>
    export default {
        name: 'CardProduct',
        data() {
        },
    }
</script>

<template>
    <section class="container py-2">
        <div class="row gap-3">
            <div class="col p-2">
                <h4>Articoli moda consigliati per te</h4>
                <div class="row">
                    <div class="ms-img-container">
                        <img src="https://staticgeopop.akamaized.net/wp-content/uploads/sites/32/2022/05/sole-colore.jpg" alt="">
                    </div>
                    <div class="ms-img-container">
                        <img src="https://staticgeopop.akamaized.net/wp-content/uploads/sites/32/2022/05/sole-colore.jpg" alt="">
                    </div>
                    <div class="ms-img-container">
                        <img src="https://staticgeopop.akamaized.net/wp-content/uploads/sites/32/2022/05/sole-colore.jpg" alt="">
                    </div>
                    <div class="ms-img-container">
                        <img src="https://staticgeopop.akamaized.net/wp-content/uploads/sites/32/2022/05/sole-colore.jpg" alt="">
                    </div>
                </div>
                <div>12345 <span>ciao</span></div>
                <div>Questo è un sole <small>Bello vero?</small></div>
            </div>
            <div class="col p-2">
                <h4>Ottimi prezzi sulla moda donna</h4>
                <div class="row">
                    <div class="ms-img-container">
                        <img src="https://staticgeopop.akamaized.net/wp-content/uploads/sites/32/2022/05/sole-colore.jpg" alt="">
                    </div>
                    <div class="ms-img-container">
                        <img src="https://staticgeopop.akamaized.net/wp-content/uploads/sites/32/2022/05/sole-colore.jpg" alt="">
                    </div>
                </div>

            </div>
            <div class="col p-2">
                <h4>Made in Italy</h4>
                <div class="row">
                    <div class="ms-img-container">
                        <img src="https://staticgeopop.akamaized.net/wp-content/uploads/sites/32/2022/05/sole-colore.jpg" alt="">
                    </div>
                    <div class="ms-img-container">
                        <img src="https://staticgeopop.akamaized.net/wp-content/uploads/sites/32/2022/05/sole-colore.jpg" alt="">
                    </div>
                </div>
            </div>
            <div class="col p-2">
                <h4>Riprendi da dove hai lasciato</h4>
                <div class="row">
                    <div class="ms-img-container">
                        <img src="https://staticgeopop.akamaized.net/wp-content/uploads/sites/32/2022/05/sole-colore.jpg" alt="">
                    </div>
                    <div class="ms-img-container">
                        <img src="https://staticgeopop.akamaized.net/wp-content/uploads/sites/32/2022/05/sole-colore.jpg" alt="">
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss" >
    @use '../style/variables' as *;
    .ms-img-container{
        width: 50%;
        padding: 0.3125rem;
        img{
            width: 100%;
        }
    }
</style>