<!-- components/DesktopOnlyMessage.vue -->
<template>
  <div class="fixed inset-0 bg-black z-[9999] flex items-center justify-center p-4">
    <div class="text-center max-w-md">
      <div class="text-4xl mb-4">💻</div>
      <h1 class="text-2xl font-bold text-white mb-4">Version desktop uniquement</h1>
      <p class="text-gray-400">
        Cette application est optimisée pour les ordinateurs de bureau.<br>
        Veuillez utiliser un PC ou un ordinateur portable pour y accéder.
      </p>
    </div>
  </div>
</template>

<script setup>
import { ref, onMounted } from 'vue'

const isDesktop = ref(true)

const checkDevice = () => {
  const userAgent = navigator.userAgent.toLowerCase()
  // Détecter les appareils mobiles
  isDesktop.value = !/android|webos|iphone|ipad|ipod|blackberry|iemobile|opera mini/i.test(userAgent)
}

onMounted(() => {
  checkDevice()
  window.addEventListener('resize', checkDevice)
})
</script>