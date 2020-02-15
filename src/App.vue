<template>
  <v-app>
<navbar />
    <v-content>
    </v-content>
  </v-app>
</template>

<script>
//import HelloWorld from './components/HelloWorld';
import navbar from './components/navbar';
export default {
  name: 'App',

  components: {
    navbar,
  },

  data: () => ({
    //
  }),
};
</script>
