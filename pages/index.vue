<template>
  <div class="p-Index">
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
      script: [{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }],
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

.p-Index {
  background: #062b33;
  text-align: center;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  animation: 1s appear;
}
.p-Index_Text {
  margin-top: 60px;
  padding-bottom: 60px;
}
p {
  color: #E5E5E5;
  font-size: 1.8rem;
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
