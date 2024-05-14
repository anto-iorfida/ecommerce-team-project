<script>
export default {
    name: "DiscoverProduct",
    data() {
        return {

        }
    }
}
</script>

<template>
    <div class="container">
        <div class="row">
            <div class="col">
                <div id="carouselExampleInterval" class="carousel slide" data-bs-ride="carousel">
                    <div class="carousel-inner">
                        <div class="carousel-item active" data-bs-interval="10000">
                            <div class="row">
                                <div class="col-2">ciao</div>
                                <div class="col-2">proa</div>
                                <div class="col-2">proa</div>
                                <div class="col-2">proa</div>
                                <div class="col-2">proa</div>
                                <div class="col-2">proa</div>
                            </div>
                        </div>
                        <div class="carousel-item" data-bs-interval="2000">
                            <div class="row">
                                <div class="col-2">ciao</div>
                                <div class="col-2">proa</div>
                                <div class="col-2">proa</div>
                                <div class="col-2">proa</div>
                                <div class="col-2">proa</div>
                                <div class="col-2">proa</div>
                            </div>
                        </div>
                        <!-- <div class="carousel-item">
                            <div class="row">
                                <div class="col-2">ciao</div>
                                <div class="col-2">proa</div>
                                <div class="col-2">proa</div>
                                <div class="col-2">proa</div>
                                <div class="col-2">proa</div>
                                <div class="col-2">proa</div>
                            </div>
                        </div> -->
                    </div>
                    <button class="carousel-control-prev btn-carousel" type="button" data-bs-target="#carouselExampleInterval"
                        data-bs-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Previous</span>
                    </button>
                    <button class="carousel-control-next btn-carousel" type="button" data-bs-target="#carouselExampleInterval"
                        data-bs-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Next</span>
                    </button>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../style/variables.scss' as*;

.btn-carousel{
    background: rgba($color: #000000, $alpha: 0.5);
    border-radius: 50%;
    height: 50px;
    width: 50px;
}

</style>