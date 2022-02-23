<template lang="html">
  <div class="container box mt-6">
      <center><img src="https://static.platzi.com/media/user_upload/Page%201-d8d869f4-7130-4ae9-9907-2fa809bd136a.jpg" class="container-img"></center>
    <h3 class="title"><b>Registro estación Platzi</b></h3>
    <form action="">
      <div class="field">
        <label id="label-name" class="label">Nombre</label>
        <div class="control">
          <input id="name" class="input is-small" type="text" placeholder="Nombre">
        </div>
        <label id="label-apellido" class="label">Apellido</label>
        <div class="control">
          <input id="apellido" class="input is-small" type="text" placeholder="Apellido">
        </div>
        <label id="label-cargo" class="label">Cargo</label>
        <div class="control">
          <input id="cargo" class="input is-small" type="text" placeholder="Cargo">
        </div>
      </div>

      <div class="field columns is-mobile field">
          <div class="column is-offset-8">
            <button class="button is-link is-small are-large is-fullwidth"><b>Enviar</b></button>
          </div>
      </div>
    </form>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style >
</style>
