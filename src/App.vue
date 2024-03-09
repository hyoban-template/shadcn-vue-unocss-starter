<script setup lang="ts">
import { Button } from '@/components/ui/button'
import { ref } from 'vue'

const count = ref(0)
</script>

<template>
  <Button type="button" @click="count++">
    count is {{ count }}
  </Button>
</template>
