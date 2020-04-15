<template>
  <div id="app">
    <top-header></top-header>
    <router-view />
    <footer>
      <top-footer></top-footer>
    </footer>
  </div>
</template>

<script>
import TopHeader from "./components/common/TopHeader.vue";
import TopFooter from "./components/common/TopFooter";

export default {
  components: {
    "top-header": TopHeader,
    "top-footer": TopFooter
  }
};
</script>
