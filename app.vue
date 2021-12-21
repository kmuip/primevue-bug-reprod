<template>
  <div>
    <Password
      class="w-full"
      v-model="password"
      placeholder="Passwort"
      :feedback="false"
      toggle-mask
    />
  </div>
</template>

<script setup lang="ts">
const password = ref("");
</script>
