<template>
  <div id="top-footer" class="text-left">
    <b-container style = "background-color: #4A4642">
      <b-row>
        <footer-widget>
          <template v-slot:widgettitle>
            Destinations
          </template>
        </footer-widget>
        <footer-widget>
          <template v-slot:widgettitle>
            ABOUT US
          </template>
        </footer-widget>
        <footer-widget>
          <template v-slot:widgettitle>
            HELP
          </template>
        </footer-widget>
      </b-row>
      <b-tooltip>
      </b-tooltip>
      <b-row>
        <b-col cols = "3">
          <b-row>
            <b-button variant="link">Petra</b-button>
          </b-row>
          <b-row>
            <b-button variant="link">Dead Sea</b-button>
          </b-row>
          <b-row>
            <b-button variant="link">Amman</b-button>
          </b-row>
          <b-row>
            <b-button variant="link">Magic Bedouin Star</b-button>
          </b-row>
        </b-col>
        <b-col cols = "3">
          <b-row>
            <b-button variant="link">Our agenda</b-button>
          </b-row>
          <b-row>
            <b-button variant="link">Benefits</b-button>
          </b-row>
          <b-row>
            <b-button variant="link">Contact</b-button>
          </b-row>
        </b-col>
        <b-col cols = "3">
          <b-row>
            <b-button variant="link">Payments</b-button>
          </b-row>
          <b-row>
            <b-button variant="link" class = "link-text">Frequenty Asked Questions</b-button>
          </b-row>
          <b-row>
            <b-button variant="link">Support Service</b-button>
          </b-row>
          <b-row>
            <b-button variant="link" class = "link-text">Guanrantee</b-button>
          </b-row>
        </b-col>
      </b-row>
      
    </b-container>
  </div>
</template>

<script>
import footerWidget from "./FooterWidget";
export default {
  name: "TopFooter",
  components: {
    "footer-widget": footerWidget
  }
};
</script>

<style lang="scss">
.link-text:hover{
  color: rebeccapurple;
  border: none;
}
.link-text{
  color: white;
  align-content: left;
  align-items: left;
}
#top-footer {
  background: #4a4642;
  padding: 50px 0;
}
</style>
