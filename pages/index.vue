<template>
  <div class="p-Index">
    <h1 class="visually-hidden">Simplr Recruitment</h1>
    <Logo />
    <div class="p-Index_Text">
      <p>Our site will be launching very soon!</p>
      <!-- <button>Send us a message at info@findsimplr.com</button> -->
      <p>In the meantime, send us a message at <a href="mailto:info@findsimplr.com">info@findsimplr.com</a>!</p>
    </div>
  </div>
</template>

<script>
// export default {}
export default {
  head() {
    return {
      script: [{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }]
    };
  },
};
</script>

<style>
@keyframes appear {
  0% {
    opacity: 0;
  }
}
@keyframes slideup {
  0% {
    opacity: 0;
  }
  30% {
    opacity: 0;
  }
  0% {
    transform: translateY(40px);
  }
}

.visually-hidden {
  clip: rect(0 0 0 0);
  clip-path: inset(50%);
  height: 1px;
  overflow: hidden;
  position: absolute;
  white-space: nowrap;
  width: 1px;
}

.p-Index {
  background: #062b33;
  text-align: center;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  animation: 1s appear;
  padding: 40px;
}

.p-Index_Text {
  margin-top: 60px;
  padding-bottom: 60px;
  animation: 1.2s slideup;
}

p {
  color: #E5E5E5;
  font-size: 1.4rem;
  margin: 8px;
  letter-spacing: .8px;
}

a {
  color: #BE9A3B;
}

button {
  background: #1E849A;
  border: none;
  padding: 15px 30px;
  color: white;
  margin: 10px;
  font-size: 1.5rem;
  letter-spacing: .8px;
}
h1 {
  font-weight: 400;
}
</style>
