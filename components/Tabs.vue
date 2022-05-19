<script>
// Imports

import WhatsApp from '@/components/WhatsApp';
export default {
  name: 'Tabs',
  setup() {
    
  },
  components: {
    WhatsApp,
  }
}
</script>

<template>
<div>
  <b-tabs content-class="mt-3" justified>
    <b-tab title="WhatsApp" active>
      <WhatsApp />
    </b-tab>
    <b-tab title="SMS">
      TODO: SMS
    </b-tab>
  </b-tabs>
</div>
</template>