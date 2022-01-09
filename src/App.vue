<template>
  <v-app>
    <v-navigation-drawer app>
      <Navigation />
    </v-navigation-drawer>

    <v-app-bar app>
      <Header />
    </v-app-bar>

    <v-main>
      <Content />
    </v-main>

    <v-footer app>
      <!-- -->
    </v-footer>
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
