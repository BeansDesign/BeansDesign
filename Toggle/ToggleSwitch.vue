<template>
  <label class="inline-flex items-center cursor-pointer relative">
    <input type="checkbox" class="sr-only peer">
    <div class="w-12 h-7 bg-gray-200 rounded-full peer peer-focus:ring-4 peer-focus:ring-[#c2e2f5] peer-checked:bg-[#4b7bf5] peer-checked:after:translate-x-full peer-checked:after:border-white after:content-[''] after:absolute after:top-0.5 after:left-0.5 after:bg-white after:border-gray-300 after:border after:rounded-full after:h-6 after:w-6 after:transition-all"></div>
  </label>
</template>

<script>
export default {
  name: 'ToggleSwitch',
};
</script>