<script lang="ts" setup>
import { useTheme } from "@@/composables/useTheme"

const { initTheme } = useTheme()

// 初始化主题
initTheme()
</script>

<template>
  <router-view />
</template>
