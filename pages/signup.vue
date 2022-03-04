<template>
  <div class="h-full w-full flex">
    <div class="flex gap-3 flex-col mx-auto my-auto">
      <h2 class="text-amber-500 mb-2 font-semibold text-xl">Sign Up</h2>
      <div class="flex gap-3 flex-row">
        <input placeholder="First Name"/><input placeholder="Last Name"/>
      </div>
      <input placeholder="Email"/>
      <input placeholder="Password" type="password"/>
      <input placeholder="Confirm Password" type="password"/>
    </div>
  </div>
</template>

<script>
export default {
  name: "signUp"
}
</script>

<style scoped>
input {
  @apply placeholder:text-white/50 caret-amber-500 bg-black/10 border-2 border-white/80 rounded-sm outline-none ring-0 focus:border-amber-500 px-3 py-2;
}
</style>
