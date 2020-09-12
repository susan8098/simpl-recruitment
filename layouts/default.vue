<template>
  <Nuxt />
</template>

<style>

@font-face {
  font-family: 'Libre Baskerville';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url('~assets/fonts/LibreBaskerville-Regular.ttf') format('truetype');
}

:root {
  font-size: 62.5%;
}

html {
  font-family:
    'Libre Baskerville'
    sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

body {
  font-size: 1.8rem;
  background: #000;
}

</style>
