<template>
  <div class="container">
    <div class="mobile">
      <logo />
      <h2 class="subtitle">
        Marca com o olhar voltado ao bem estar e auto cuidado. Nossa inspiração vem do Yoga/Meditação.
      </h2>
      <p>Zafus para Meditação e Porta Mats para Yoga</p>
      <p>Para contato, utilize nossas redes sociais:</p>
      <div class="links">
        <a
          href="https://www.facebook.com/Purusha-Bem-Estar-Cia-107212180692002/"
          target="_blank"
          class="button--grey"
        >
          @ Facebook
        </a>
        <a
          href="https://www.instagram.com/purusha.bem.estar/"
          target="_blank"
          class="button--grey"
        >
          @ Instagram
        </a>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>

* {
  box-sizing: border-box;
}
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  font-family: 'Open Sans', -apple-system, BlinkMacSystemFont;
}

img {
  max-width: 100%;
  height: auto;
}

.subtitle {
  font-weight: 300;
  font-size: 16px;
  max-width: 360px;
  padding-top: 20px;
  text-align: left;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
p {
  font-weight: 300;
  line-height: 22px;
  margin: 20px 0 0;
}

@media only screen 
and (min-device-width : 320px) 
and (max-device-width : 980px) {
  .container {
    display: block;
  }
  .mobile {
    padding: 12px;
    padding-bottom: 60px;
  }
  .links {
    font-size: 13px;
  }
  
}
</style>
