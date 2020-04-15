<template>
  <div id="app">
    <top-header></top-header>
    <router-view />
    <footer>
      <top-footer></top-footer>
      <bottom-footer></bottom-footer>
    </footer>
  </div>
</template>

<script>
import TopHeader from "./components/common/TopHeader.vue";
import TopFooter from "./components/common/TopFooter";
import BottomFooter from "./components/common/BottomFooter";

export default {
  components: {
    "top-header": TopHeader,
    "top-footer": TopFooter,
    "bottom-footer": BottomFooter
  }
};
</script>
