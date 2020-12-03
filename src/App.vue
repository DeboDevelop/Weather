<template>
<div id="app"></div>
</template>

<script>
require("dotenv").config();

export default {
  name: "App",
    data () {
    return {
      api_key: process.env.API_KEY ,
    }
  },
};
</script>

<style>

</style>