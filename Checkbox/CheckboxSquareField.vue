<template>
  <label class="inline-flex items-center cursor-pointer">
    <input type="checkbox" class="sr-only peer">
    <div class="w-6 h-6 border-2 border-[#4b7bf5] peer-checked:bg-[#4b7bf5] rounded-lg flex items-center justify-center transition-all">
      <svg class="w-4 h-4 text-white hidden peer-checked:block transform scale-0 peer-checked:scale-100 transition-transform duration-200" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
      </svg>
    </div>
    <span class="ml-2 text-base font-medium">Checkbox</span>
  </label>
</template>

<script>
export default {
  name: 'CheckboxSquareField',
};
</script>