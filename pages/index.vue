<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">forza.finance</h1>
      <div class="links">
        <a
          href="https://www.mintscan.io/kava/validators/kavavaloper18x7mhjqyjxadkzreh3ae2vfw83ar2cvhf72gk6"
          target="_blank"
          title="forza.finance Kava Validator"
          class="button--grey"
        >
          Kava
        </a>
        <a
          href="https://crypto.org/explorer/validator/crocncl1uc8sgjl2xm7u54al6p02mmt5vf6vhz6024485w"
          target="_blank"
          title="forza.finance Crypto.org Chain Validator"
          class="button--grey"
        >
          Crypto.org Chain
        </a>
        <a
          href="https://twitter.com/forzafin"
          target="_blank"
          class="button--grey"
        >
          Twitter
        </a>
        <a href="https://t.me/forzafin" target="_blank" class="button--grey">
          Telegram
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
