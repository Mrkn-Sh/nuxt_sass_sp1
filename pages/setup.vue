<template>
  <div>
    <Header />
    <div>setup page!</div>
    <Footer />
  </div>
</template>

<script>
import { defineComponent } from '@nuxtjs/composition-api'
import Header from "@/components/Header"
import Footer from "@/components/Footer"

export default defineComponent({
  components: {
    Header,
    Footer,
  },
  setup() {
        
  },
})
</script>
