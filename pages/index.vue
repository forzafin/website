<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">forza.finance</h1>
      <div class="links">
        <a
          href="https://crypto.org/explorer/validator/crocncl1qvhu7slzcdf3rer07y3au2xwxkwugr77xsylxv"
          target="_blank"
          title="forza.finance Crypto.org Chain Validator"
          class="button--grey"
        >
          Crypto.org Chain
        </a>
        <a
          href="https://escan.live/validator/evmosvalcons1p6fk4rrz09zyelequefq2txmq5s6ahqnt44ex0"
          target="_blank"
          title="forza.finance Evmos Validator"
          class="button--grey"
        >
          Evmos
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
