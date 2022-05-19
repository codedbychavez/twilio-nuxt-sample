<script>
// Imports
import Navigation from '@/components/Navigation';
import Tabs from '@/components/Tabs';


export default {
  name: 'IndexPage',
  components: {
    Navigation,
    Tabs,
  }
}
</script>

<template>
  <div class="wrapper">
    <Navigation />
    <div class="container">

      <Tabs />
    </div>
  </div>
</template>

<style>
.body {
  background: whitesmoke;
}

</style>

