<template>
  <div class="Home">
    <H1 />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import H1 from '@/components/H1.vue'; 

@Component({
  components: {
    H1,
  },
})
export default class Home extends Vue {}
</script>
