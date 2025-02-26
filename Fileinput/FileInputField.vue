<template>
  <div class="relative">
    <input type="file" class="absolute inset-0 w-full h-full opacity-0 cursor-pointer border-2 border-[#4b7bf5] focus:ring-4 focus:ring-[#c2e2f5] rounded-lg">
    <div class="border-2 border-[#4b7bf5] rounded-lg py-2 px-4 text-base font-medium text-center bg-white cursor-pointer">选择文件</div>
  </div>
</template>

<script>
export default {
  name: 'FileInputField',
};
</script>