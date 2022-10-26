<script setup>
let today = new Date();
let theDay = 26;
let theMonth = 10;
const todaysDay = today.getDate();
const todaysMonth = today.getMonth() + 1;

const isTodayBrettsBirthday = (theDay === todaysDay) && (theMonth === todaysMonth);

</script>

<template>
<main>
  <div class="hero min-h-screen bg-base-200">
    <div class="hero-content text-center">
      <div class="max-w-md">
        <h1 class="text-5xl font-bold text-white">{{isTodayBrettsBirthday ? 'YES' : 'NO'}}</h1>
      </div>
    </div>
  </div>
</main>
</template>

<style scoped>

</style>
