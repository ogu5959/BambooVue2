<template>
  <v-app>
    <Header />
    <Navigation />
    <Content />
  </v-app>
</template>

<script>
import Header     from "@/components/Header.vue"
import Navigation from '@/components/Navigation.vue'
import Content    from '@/components/Content.vue'

export default {
  name: 'App',
  components: {
    Header,
    Navigation,
    Content
  },

  data: () => ({
    //
  }),
};
</script>
