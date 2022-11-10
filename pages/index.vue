<template>
  <Registrarse/>
</template>

<script lang="ts">
import Vue from 'vue'
import Registrarse from '~/components/Registrarse.vue';

export default Vue.extend({
    name: "IndexPage",
    components: { Registrarse }
})
</script>
