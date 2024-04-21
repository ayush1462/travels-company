<template>
    <secion id="features">
        <h1 class="sectionTitle">Our Features</h1>
        <div class="cardGroup">
            <FeatureCard heading="FAST & SAFE" feature="Experience swift, secure transportation. Our skilled drivers prioritize safety and speedy arrivals.
                                Advanced technology
                                ensures a smooth journey, always putting passengers' well-being first." />
            <FeatureCard heading="BEST PRICE" feature="Enjoy competitive rates and unbeatable value. Transparent pricing guarantees the best deal every
                                time,
                                without
                                compromising quality or comfort." />
            <FeatureCard heading="DELIEVER PACKAGE" feature="Beyond passenger transport, rely on us for prompt, secure package delivery. Our dedicated drivers
                            ensure
                            parcels reach
                            their destination swiftly, providing a convenient solution for all delivery needs." />
        </div>
        <a>BOOK NOW</a>
    </secion>
</template>
<script>
import FeatureCard from './FeatureCard.vue';
export default {
    name: "FeatureSection",
    components: {
        FeatureCard,
    }
};
</script>
<style scoped>
#features {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-around;
    height: 100vh;
    background: linear-gradient(147deg, #000000 0%, #130140 94%);
    background-blend-mode: darken;
    background-size: cover;

}

.cardGroup {
    display: flex;
    justify-content: space-around;
    align-items: center;
}

#features a{
    padding: 0.7rem 2rem;
    border: 2px solid #fff;
    border-radius: 1rem;
    margin: 4rem 0;
    transition: 0.3s;
}
#features a:hover{
    border-color: #F1A208;
    background-color: #F1A208;
}
</style>