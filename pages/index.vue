<template>
  <div class="w-screen h-screen flex p-8">
    <div class="flex flex-col flex-1 w-1/2 p-4">
      <h1>Doge Date</h1>

      <p class="lead">Coming Winter 2021</p>
      <p class="sub">Check back soon for updates</p>
    </div>
    <div id="right"
         class="flex-1 w-1/2"></div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
  h1 {
    font-size: 2.5rem;
    font-weight: 700;
    letter-spacing: -.01em;
    line-height: 1.25em;
  }

  .lead {
    font-size: 1rem;
    font-weight: 600;
    line-height: 1.25em;

    @apply mt-4;
  }

  .sub {
    font-size: 1rem;
    font-weight: 500;

    @apply text-gray-500;
  }

  #right {
    background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
    background-size: 400% 400%;
    animation: gradient 15s ease infinite;
  }

  @keyframes gradient {
    0% {
      background-position: 0% 50%;
    }
    50% {
      background-position: 100% 50%;
    }
    100% {
      background-position: 0% 50%;
    }
  }
</style>