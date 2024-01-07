<script setup lang="ts">
import AppHeader from '@/components/App/AppHeader.vue'
import AppIntroduction from '@/components/App/AppIntroduction.vue'
import AppMainContent from '@/components/App/AppMainContent.vue'
import AppPlayer from '@/components/App/AppPlayer.vue'
import AppAuth from '@/components/App/AppAuth.vue'
</script>

<template>
  <!-- Header -->
  <AppHeader />
  <!-- Introduction -->
  <AppIntroduction />
  <!-- Main Content -->
  <AppMainContent />
  <!-- Player -->
  <AppPlayer />
  <!-- Auth Modal -->
  <AppAuth />
</template>
