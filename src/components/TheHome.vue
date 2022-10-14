<template>
  <div class="home">
    <HeroSection></HeroSection>
    <ServicesSection></ServicesSection>
    <PortfolioSection></PortfolioSection>
    <TechnologiesSection></TechnologiesSection>
    <ContactSection></ContactSection>
  </div>
</template>

<script>
import HeroSection from "./BaseComponents/HeroSection.vue";
import ServicesSection from "./BaseComponents/ServicesSection.vue";
import PortfolioSection from "./BaseComponents/PortfolioSection.vue";
import TechnologiesSection from "./BaseComponents/TechnologiesSection.vue";
import ContactSection from "./BaseComponents/ContactSection.vue";
export default {
  components: {
    HeroSection,
    ServicesSection,
    PortfolioSection,
    TechnologiesSection,
    ContactSection,
  },
};
</script>