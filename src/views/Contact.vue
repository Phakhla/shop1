<template>
    <div class="Contact">
        <h1>This is Contact</h1>
        <Con />
    </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Con from '@/components/C1.vue'; 

@Component({
  components: {
    Con,
  },
})
export default class Home extends Vue {}
</script>
