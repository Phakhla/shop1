<template>
    <div class="About">
        <h1>This is About</h1>
        <Ab />
    </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Ab from '@/components/A1.vue'; 

@Component({
  components: {
    Ab,
  },
})
export default class Home extends Vue {}
</script>
