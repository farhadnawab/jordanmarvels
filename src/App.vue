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

<style lang="scss">
.heading {
  color: #50473d;
  font-weight: bold;
  position: relative;
  margin-bottom: 20px;
  &::before {
    content: "";
    position: absolute;
    width: 100px;
    border-top: 2px solid #d5d5d5;
    top: 50%;
    left: -125px;
  }
}
</style>
