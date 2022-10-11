<template>
  <q-page class="container fundo">
    <div class="logo">
      <img src="../../../public/img/logo.svg" class="logo-mini">
    </div>
    <div>
      <Cliente />
    </div>
  </q-page>
</template>

<script>
import Cliente from '../../components/cliente/cliente.vue'
export default {
  name: 'MainAccess',
  components: {
    Cliente
  },
  // data () {
  //   return {
      
  //   }
  // },
  // methods: {
    
  // }
}
</script>