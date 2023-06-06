<script setup>
import ScriptSetup from './components/ScriptSetup.vue'
import SetupMethod from './components/SetupMethod.vue'
import OptionsAPI from './components/OptionsAPI.vue'
</script>

<template>
  <div class="movie-list flex flex-wrap gap-4 max-[450px]:justify-center">
    <ScriptSetup />
    <SetupMethod />
    <OptionsAPI />
  </div>
</template>
