<template lang="pug">
  #app
    Top
    Content
      template(v-slot:marquee)
        Marquee
    Footer
</template>

<script>
import Top from './components/Top'
import Content from './components/Content'
import Marquee from './components/Marquee'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Top,
    Content,
    Marquee,
    Footer
  }
}
</script>
