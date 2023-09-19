<style>
.v-toolbar.dsfr-toolbar {
  color: #0079C0;
  background-color: #ffffff;
  font-family: Roboto;
  font-size: 16px;
  font-weight: bold;
  text-transform: uppercase;
  border-radius: 4px;
  border-width: 1px;
  box-shadow: 0 1px 2px 0 rgba(0, 0, 0, 0.1);
}

.dsfr-button {
  color: #0079C0;
  background-color: #ffffff;
  font-family: Roboto;
  font-size: 16px;
  font-weight: bold;
  text-transform: uppercase;
  border-radius: 4px;
  border-width: 1px;
  border-color: #0079C0;
  box-shadow: 0 1px 2px 0 rgba(0, 0, 0, 0.1);
}
.toolbar-wrapper {
  display: flex;
  justify-content: start;
}
</style>

<template>
  <div class="toolbar-wrapper">
     <v-toolbar class="dsfr-toolbar">
    <v-img src="@/assets/Sopra_Steria_Logo.jpg" width="10" height="100"  />
    <v-btn class="dsfr-button" @click="doSomething">
      <v-icon>mdi-home</v-icon>
    </v-btn>
  </v-toolbar>
  </div>
 
</template>

<script lang ="ts">
export default {
  data() {
    return {
      menu: false,
    };
  },
  methods: {
    doSomething() {
      console.log("Do something");
    },
  },
};
</script>
