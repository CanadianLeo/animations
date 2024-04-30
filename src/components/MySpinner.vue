<template>
  <div>
    <div class="spinner"></div>
  </div>
</template>

<style scoped>
.spinner {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  border: 5px solid transparent;
  border-top-color: black;
  animation: spin infinite 1s linear;
}

@keyframes spin {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}
</style>
