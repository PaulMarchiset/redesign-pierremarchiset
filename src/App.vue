<script setup lang="ts">
import { RouterView } from 'vue-router'
import { Suspense } from 'vue'
import HeaderPage from '@/components/HeaderPage.vue'
import FooterPage from '@/components/FooterPage.vue'
</script>

<template>
    <HeaderPage />
    <main>
        <Suspense>
            <RouterView />
        </Suspense>
    </main>
</template>
