<template>
   <div class="page-container">
      <hr class="border-t-2 border-emerald-800/30" />
   </div>
</template>

<script lang="ts" setup>
import { defineOptions, defineProps } from "vue";

defineOptions({
   label: "Divider",
});

withDefaults(
   defineProps<{
      kicker?: string;
   }>(),
   {}
);
</script>

