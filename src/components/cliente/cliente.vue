<template>
  <q-form
    @submit="save"
    @reset="onReset"
    class="q-gutter-md"
  >
    <q-input 
      filled
      v-model="nomeCompleto"
      label="Nome Completo"
      lazy-rules
      :rules="[ val => val && val.length > 0 || 'Por favor digite seu nome']"
    />
  </q-form>
</template>

<script>
export default {
  name: 'Cliente',
  data () {
    return {
      nomeCompleto,
    }
  }
}
</script>
