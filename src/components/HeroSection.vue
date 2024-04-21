<template>
    <section id="home">
        <div class="left">
            <h1>WHERE EVERY MILE FEELS <br> LIKE A SMILE</h1>
            <p>We provide 24X7 outstation and local taxi service from lucknow. Contact us to book your trip from lucknow to
                anywhere Because we provide highly trained drivers with well maintained and clean taxi in wide range. </p>
            <div class="links">
                <a id="contactBtn" href="#contact">Book Now</a>
                <div id="pricingBtn"> <a href="#pricing">Pricing</a> <img src="../assets/arrow.svg" alt=""></div>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    name: "HeroSection",
}
</script>
<style scoped>
#home {
    display: flex;
    justify-content: space-around;
    align-items: center;
    background: rgba(0, 0, 0, 0.63) url(../assets/pexels-pixabay-210182.jpg);
    background-blend-mode: darken;
    background-size: cover;
    background-attachment: fixed;
    background-position-x: center;
    padding: 1rem 10rem;
    height: 100vh;
}

#home .left #contactBtn {
    text-decoration: none;
    color: #FFFDF7;
    background-color: #F1A208;
    border-radius: 1rem;
    font-size: 1.2rem;
    font-weight: 400;
    padding: 0.7rem 2rem;
    margin: 1rem;
    transition: 0.3s;
}

#home .left #contactBtn:hover {
    box-shadow: 0 0 10px #F1A208;
}

#home .left #pricingBtn {
    display: inline-flex;
    width: min-content;
    align-items: center;
    color: #ffffff;
    font-size: 1.2rem;
    font-weight: 400;
    margin: 5rem;
    padding: 0.2rem;
    text-decoration: none;
    border-bottom: 1px solid #F1A208;
}

#pricingBtn a {
    color: #ffffff;
    font-size: 1.2rem;
    font-weight: 400;
    text-decoration: none;
    transition: 0.3s;
}
#pricingBtn:hover a{
    margin-right: 0.2rem;
}
#home .left {
    text-align: center;
}

#home .left h1 {
    color: #ffffff;
    font-size: 5rem;
    font-weight: 900;
    line-height: 1.1;
}

#pricingBtn img {
    width: 30%;
    height: auto;
    margin-top: 0.5rem;
    margin-left: 0.5rem;
}
</style>
