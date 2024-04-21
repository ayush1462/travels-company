<template>
    <div class="featureCard">
        <div class="heading">
            <img src="../assets/package.png" alt="fast">
            <h1>{{ heading }}</h1>
        </div>
        <p>{{ feature }}</p>
    </div>
</template>
<script>
export default {
    name: "FeatureCard",
    props: {
        heading: { requred: true, type: String },
        feature: { requred: true, type: String },
    },
};
</script>
<style scoped>
#features .featureCard {
    max-width: 16rem;
    height: 20rem;
    text-align: center;
    background-color: #FFFDF7;
    padding: 2rem 2rem;
    box-shadow: 0.5rem 0.5rem 0 #F1A208;
    margin: 0 4rem;
}

.heading {
    display: flex;
    align-items: center;
}

#features .featureCard p {
    color: #0A100D;
    text-align: center;
    font-size: 1.2rem;
    font-weight: 400;
}

.heading img {
    width: 20%;
    margin: 0 2rem;
}

.heading h1 {
    color: #0A100D;
    font-size: 2rem;
    font-weight: 800;
}

.heading span {
    color: rgb(255, 188, 2);
}
</style>