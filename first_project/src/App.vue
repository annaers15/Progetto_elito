<template>
  <div>
    <PricingPlan />
    <TalkComponent />
    <NewsComponent />
    <ContactUsComponent />
    <FooterComponent />
  </div>
</template>

<script>
import PricingPlan from './components/PricingPlan.vue'
import TalkComponent from './components/TalkComponent.vue'
import NewsComponent from './components/NewsComponent.vue'
import ContactUsComponent from './components/ContactUsComponent.vue'
import FooterComponent from './components/FooterComponent.vue'

export default {
  name: 'App',
  components: {
    PricingPlan,
    TalkComponent,
    NewsComponent,
    ContactUsComponent,
    FooterComponent
    
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
#app {
  font-family: "Inter", sans-serif;
  padding: 0;
  margin: 0;
}
</style>
