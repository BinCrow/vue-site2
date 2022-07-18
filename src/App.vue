<template>
<HeaderSection />
<SliderSection />
<AwardSection />
<ActorSection />
<WorkSection />
<Youtube />
<ReviewSection />
<FooterSection />
</template>

<script>
import HeaderSection from './components/HeaderSection.vue'
import SliderSection from './components/SliderSection.vue'
import AwardSection from './components/AwardSection.vue'
import ActorSection from './components/ActorSection.vue'
import WorkSection from './components/WorkSection.vue'
import Youtube from './components/YoutubeSection.vue'
import ReviewSection from './components/ReviewSection.vue'
import FooterSection from './components/FooterSection.vue'

export default {
  name: 'App',
  components: {
    HeaderSection,
    SliderSection,
    AwardSection,
    ActorSection,
    WorkSection,
    Youtube,
    ReviewSection,
    FooterSection,
  }
}
</script>

<style>
@import "./App.css";
</style>
