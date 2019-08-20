<template>
  <div>
    <navbar />
    <top-banner />
    <center-section />
    <left-section />
    <right-section />
  </div>
</template>

<script>
import Navbar from '~/components/Navbar.vue'
import TopBanner from '~/components/TopBanner.vue'
import CenterSection from '~/components/CenterSection.vue'
import LeftSection from '~/components/LeftSection.vue'
import RightSection from '~/components/RightSection.vue'

export default {
  components: {
    Navbar,
    TopBanner,
    CenterSection,
    LeftSection,
    RightSection
  }
}
</script>
