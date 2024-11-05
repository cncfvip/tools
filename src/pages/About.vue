<script setup lang="ts">
import { useHead } from '@vueuse/head';

useHead({ title: 'About - 云原生工具CNCF.VIP' });
</script>

<template>
  <c-markdown :markdown="$t('about.content')" mx-auto mt-50px max-w-600px />
</template>
