<template>
  <div>
  <v-app>
<navbar />
<router-view></router-view>
    <v-content>
    </v-content>
  </v-app>
  </div>
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
