<template>
    <div class="Login">
        <L1 />
    </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import L1 from '@/components/L1.vue'; 

@Component({
  components: {
    L1,
  },
})
export default class Home extends Vue {}
</script>
