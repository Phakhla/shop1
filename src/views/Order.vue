<template>
  <div class="Order">
    <h1>This is order</h1>
    <Order />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Order from '@/components/O1.vue'; // @ is an alias to /src

@Component({
  components: {
    Order,
  },
})
export default class Home extends Vue {}
</script>