<template>
    <nav>
        <div class="logo">
            <h1>TRIVE </h1>TRAVELS
        </div>
        <div class="links">
            <ul class="navbar">
                <li class="nav-item"><a href="#home" class="nav-links">Home</a></li>
                <li class="nav-item"><a href="#features" class="nav-links">Features</a></li>
                <li class="nav-item"><a href="#pricing" class="nav-links">Pricing</a></li>
                <li class="nav-item"><a href="#contact" class="nav-links">Contact Us</a></li>
            </ul>
        </div>
    </nav>
</template>
<script>
export default {
    name: "NavBar",
};
</script>
<style scoped>
nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #26262673;
    position: fixed;
    width: 100%;
    height: 3rem;
    top: 0;
}

nav div {
    margin: 0rem 2rem;
}

.logo {
    text-align: center;
    line-height: 1rem;
    color: #F1A208;
}

.navbar {
    display: flex;
    justify-content: space-between;
}

.nav-item {
    list-style: none;
    margin-left: 1rem;
}

.nav-links {
    text-decoration: none;
    color: #FFFDF7;
    font-size: 1.2rem;
    font-weight: 400;
}

.nav-links:hover {
    color: #F1A208;
}
</style>