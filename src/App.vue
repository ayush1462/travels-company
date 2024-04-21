<script>
import NavBar from './components/NavBar.vue'
import HeroSection from './components/HeroSection.vue'
import FeatureSection from './components/FeatureSection.vue'
import PricingSection from './components/PricingSection.vue'
import ContactPage from './components/ContactPage.vue'
import FooterSection from './components/FooterSection.vue'
export default {
  name: "App",
  components: {
    NavBar,
    HeroSection,
    FeatureSection,
    PricingSection,
    ContactPage,
    FooterSection,
  }
}
</script>

<template>
  <NavBar />
  <HeroSection />
  <FeatureSection />
  <PricingSection />
  <ContactPage />
  <FooterSection/>
</template>

