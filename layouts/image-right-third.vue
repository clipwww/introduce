<script setup>
defineProps({
  image: {
    type: String,
    required: true,
  },
  backgroundSize: {
    type: String,
    default: 'contain',
  },
})
</script>

<template>
  <div class="slidev-layout grid h-full" style="grid-template-columns: 3fr 1fr;">
    <div class="p-10 flex flex-col justify-center">
      <slot />
    </div>
    <div class="flex items-center pr-6">
      <img
        :src="image"
        class="w-full h-auto rounded-2xl"
        :style="{ objectFit: backgroundSize === 'contain' ? 'contain' : 'cover' }"
      />
    </div>
  </div>
</template>
