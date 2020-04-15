<template>
<b-container>
  <heading
    heading="Why travellers use Jordan Marvels"
    btnText="Add your review"
    btnLink="#"
  ></heading>
  <v-row>
      <profile/>
  </v-row>
</b-container>
</template>
<script>

import heading from "./Heading";
import profile from "./Profile"
export default {
  components: { 
    heading,
    profile
    }
};
</script>
