<template>
  <div>
    <NavBar></NavBar>
    <HeroSection></HeroSection>
    <FeaturesSection></FeaturesSection>
    <DetailSections></DetailSections>
    <WhyChoseUs></WhyChoseUs>
    <AdvantageSection></AdvantageSection>
    <CustomerFeedback></CustomerFeedback>
    <FAQSection></FAQSection>
    <ContactFixed></ContactFixed>
  </div>
</template>

<script>
import NavBar from "./components/NavBar.vue";
import HeroSection from "./components/HeroSection.vue";
import FeaturesSection from "./components/FeaturesSection.vue";
import DetailSections from "./components/DetailSections.vue";
import WhyChoseUs from "./components/WhyChoseUs.vue";
import AdvantageSection from "./components/AdvantageSection.vue";
import CustomerFeedback from "./components/CustomerFeedback.vue";
import FAQSection from "./components/FAQSection.vue";
import ContactFixed from "./components/ContactFixed.vue";

export default {
  name: "App",
  components: {
    NavBar,
    HeroSection,
    FeaturesSection,
    DetailSections,
    WhyChoseUs,
    AdvantageSection,
    CustomerFeedback,
    FAQSection,
    ContactFixed,
  },
};
</script>

<style>
@import "./assets/css/app.css";
</style>
