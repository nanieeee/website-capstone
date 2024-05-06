<!--default button to be used throughout site-->
<template> 
<div class="mx-auto flex w-fit flex-col space-y-4 sm:flex-row sm:space-y-0 sm:space-x-4">
  <button class="rounded-md px-12 py-2 text-black font-semibold shadow-sm bg-teal-400 transition hover:bg-teal-500 min-h-8 min-w-32 max-h-8 flex items-center justify-center">Download Now</button>
</div>
</template>

<script>
export default {
  props: {
    buttonText: String
  }
}
</script>

<style scoped>
  .button {
  color: black;
  padding: 8px 16px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  height: 40px;
  min-height: 40px;
  min-width: 200px;

}
</style>