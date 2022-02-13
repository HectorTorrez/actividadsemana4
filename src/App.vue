<template>
  <div id="app">
    <header-title title="Conversion"/>
   <card/>
  </div>
</template>

<script>
import HeaderTitle from "../components/HeaderTitle.vue"
import Card from "../components/Cards.vue"

export default {
  name: 'App',
  components: {
    HeaderTitle,
    Card
  }
}
</script>


