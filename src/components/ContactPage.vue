<template>
    <section id="contactPage">
        <h1 class="sectionTitle">CONTACT NOW</h1>
        <div class="contact">
            <div id="addressDetails">
                <h1>Head Office</h1>
                <p class="address">-Station Rd, Near Nigoha bus stop, Nigohan,<br> Lucknow, Uttar Pradesh </p>
                <h1>Contact Number</h1>
                <p class="contactNo">+91 9336135764</p>
            </div>
            <div class="contactDetails">
                <a href="http://wa.me/+919336135764"><img src="../assets/whatsapp.png" alt=""> Chat with us</a>
                <a href="mailto:vikas.vikas.1063@gmail.com"><img src="../assets/gmail.png" alt=""> Mail us</a>
                <a href="tel:+919336135764"><img src="../assets/telephone.png" alt=""> Call us</a>
            </div>
            <iframe
                src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d7137.216765492015!2d81.03947694793212!3d26.56484599053582!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sen!2sin!4v1712578664524!5m2!1sen!2sin"
                width="400" height="400" style="border:2px solid #0A100D;" allowfullscreen="" loading="lazy"
                aria-expanded="true" referrerpolicy="no-referrer-when-downgrade"></iframe>
        </div>
    </section>
</template>
<script>
export default {
    name: "ContactPage",
}
</script>
<style scoped>
#contactPage {
    background-color: #FFFDF7;
    height: 100vh;
    padding: 0 2rem;
}

.contact {
    display: flex;
    justify-content: center;
    align-items: center;
}

.contact a {
    text-decoration: none;
    display: block;
    text-align: center;
    width: 40%;
    margin: 2rem auto;
    padding: 0.7rem;
    font-size: 1.2rem;
    border-radius: 2rem;
    color: #0A100D;
    background-color: #cccbca;
}

.sectionTitle {
    color: #0A100D;
}

#addressDetails p {
    font-size: 1.2rem;
    color: #0A100D;
    margin: 3rem 0;
}

#addressDetails h1 {
    font-size: 1.5rem;
    color: #0A100D;
    margin: 3rem 0;
}

.contact a img {
    width: 7%;
    margin: 0 1rem;
}
</style>