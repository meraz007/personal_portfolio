<template>
  <div class="home">
    <SideNavigation />
  <i class="bi bi-list mobile-nav-toggle d-xl-none"></i>
  <HeroSection />

  <main id="main">
  <AboutSection />
  <FactsSection />
  <Skill />
  <Resume />
  <Portfolio />
  <ServiceSection />
  <TestimonialSection />
  <ContactSection />
  </main><!-- End #main -->
  <Footer />
  <a href="#" class="back-to-top d-flex align-items-center justify-content-center"><i class="bi bi-arrow-up-short"></i></a>
  </div>
</template>

<script>
import SideNavigation from '../components/SideNavigation.vue'
import HeroSection from '../components/HeroSection.vue'
import ContactSection from '../components/ContactSection.vue'
import TestimonialSection from '../components/TestimonialSection.vue'
import ServiceSection from '../components/ServiceSection.vue'
import Footer from '../components/Footer.vue'
import Portfolio from '../components/Portfolio.vue'
import Resume from '../components/Resume.vue'
import Skill from '../components/Skill.vue'
import FactsSection from '../components/FactsSection.vue'
import AboutSection from '../components/AboutSection.vue'

export default {
  name: 'Home',
  components: {
    SideNavigation,
    HeroSection,
    ContactSection,
    TestimonialSection,
    ServiceSection,
    Footer,
    Portfolio,
    Resume,
    Skill,
    FactsSection,
    AboutSection
  }
}
</script>
