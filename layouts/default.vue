<template>
  <div class="container">
    <sidebar />
    <main>
      <navbar />
      <slot />
    </main>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css?family=Quicksand:400,500,600,700&display=swap');

body {
  margin: 0;
  background: #efefe6;
  color: #003c3c;
  font-family: Quicksand, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto,
    'Helvetica Neue', Arial, 'Noto Sans', sans-serif, 'Apple Color Emoji',
    'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
}

.page-enter-active,
.page-leave-active {
  transition: opacity 0.1s;
}
.page-enter,
.page-leave-to {
  opacity: 0;
}

.container {
  display: flex;
  min-height: 100vh;
  height: 100vh;
}

main {
  flex: 1;
  display: flex;
  flex-direction: column;
}

.page {
  flex: 1;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>
