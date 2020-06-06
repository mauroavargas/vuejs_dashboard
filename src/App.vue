<template>
  <v-app>
<Navbar />
    <v-content>
      <router-view>
        <Users />
      </router-view>
    </v-content>
  </v-app>
</template>

<script>
import Navbar from '@/components/Navbar';
import Users from '@/views/Users';
export default {
  name: 'App',

  components: {
    Navbar,
    Users
  },

  data: () => ({
    //
  }),
};
</script>
