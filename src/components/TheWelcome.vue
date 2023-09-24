<script setup lang="ts">
// const messageList = reactive([])
</script>

<template>
  <div class="w-full h-full flex flex-col gap-2 justify-center items-center p-5">
    <div class="flex flex-col gap-3 w-full max-w-[500px]">
      <div
        class="w-full h-[300px] border border-green-400 border-solid rounded overflow-hidden outline-0 outline-offset-4 outline-green-300 px-2 py-1">
      </div>
      <div class="flex justify-between gap-2">
        <input type="text" class="w-full border border-green-400 rounded outline-0 px-2">
        <button
          class="border bg-green-500 hover:bg-green-400 active:bg-green-600 text-white px-3 py-1 rounded transition-all duration-300">Send</button>
      </div>
    </div>
  </div>
</template>
