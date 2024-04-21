<template>
    <section id="pricing">
        <h1 class="sectionTitle">
            OUR CARS
        </h1>
        <div class="autoroom">
            <div class="priceCard">
                <img src="../assets/cars/auragallerypc_4.jpg" alt="aura" id="aura" class="carImage">
                <div class="details">
                    <h1 class="carName">Hyundai AURA</h1>
                    <h2 class="priceDetail">Starting from 10rs/km</h2>
                    <button href="http://wa.me/+919336135764">BOOK NOW</button>
                </div>
            </div>
            <div class="priceCard">
                <img src="../assets/cars/DzireWhitemerged-v4.webp" alt="aura" id="dzire" class="carImage">
                <div class="details">
                    <h1 class="carName">Swift DZIRE</h1>
                    <h2 class="priceDetail">Starting from 10rs/km</h2>
                    <button href="http://wa.me/+919336135764">BOOK NOW</button>
                </div>
            </div>
            <div class="priceCard">
                <img src="../assets/cars/6th BOLERO Classic Variants _ pricing _816x400px_1.webp" alt="aura" id="aura" class="carImage">
                <div class="details">
                    <h1 class="carName">Mahindra BOLERO</h1>
                    <h2 class="priceDetail">Starting from 10rs/km</h2>
                    <button href="http://wa.me/+919336135764">BOOK NOW</button>
                </div>
            </div>
            <div class="priceCard">
                <img src="../assets/cars/super-white-color-1600x600.png" alt="aura" id="innova" class="carImage">
                <div class="details">
                    <h1 class="carName">Toyota INNOVA</h1>
                    <h2 class="priceDetail">Starting from 10rs/km</h2>
                    <button href="http://wa.me/+919336135764">BOOK NOW</button>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    name: "PricingSection",
}
</script>
<style scoped>
#pricing {
    height: 100vh;
    background-color: #fff;
}

.sectionTitle {
    color: #0A100D;
}

.autoroom {
    display: flex;
    align-items: center;
    justify-content: space-around;
}

.priceCard {
    height: 20rem;
    width: 25rem;
    margin: 0 1rem;
    border: 2px solid black;
    padding: 1rem;
}

.carName {
    font-size: 2rem;
    font-weight: 700;
    color: #0A100D;
}

.priceDetail {
    font-size: 1rem;
    color: #5a5a5a;
}

.carImage {
    width: 100%;
    height: 60%;
    object-fit: contain;
}

#dzire {
    width: 70% !important;
    margin: 0 2rem;

}
</style>