<template>
  <label class="inline-flex items-center cursor-pointer">
    <input type="checkbox" class="sr-only peer">
    <div class="w-5 h-5 border-2 border-[#18a558] peer-checked:bg-[#18a558] rounded-full flex items-center justify-center transition-all">
      <svg class="w-3 h-3 text-white hidden peer-checked:block transform scale-0 peer-checked:scale-100 transition-transform duration-200" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
      </svg>
    </div>
    <span class="ml-2 text-base">Checkbox</span>
  </label>
</template>

<script>
export default {
  name: 'CheckboxField',
};
</script>