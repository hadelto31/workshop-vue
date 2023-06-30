<template>
  <div id="app">
    
    <work-cards-vue  vacante="SENIOR BACK END DEVELOPER - KNOWLEDGE GRAPH" habilidades="Graphql"  empresa="20 moves" ubicacion="Remoto" sueldo="2M -3M COP" vacantes="3 vacantes" dias="hace 3 dias"/> 
    <work-cards-vue   vacante="Director comercial " habilidades="Ingles" empresa="Bankuish" ubicacion="Remoto" sueldo="3K - 4K US" vacantes="1 vacante" dias="hace 1 dia"/>
    <work-cards-vue vacante="Gerente nacional de ventas " habilidades="Business Closure" empresa="Confidencial" ubicacion="Bogota" sueldo="6M - 13M COP" vacantes="1 vacante" dias="hace 2 dias"/>
  </div>
</template>

<script>
import WorkCardsVue from './components/WorkCards.vue'


export default {
  name: 'App',
  components: {
    WorkCardsVue
    
  }
}
</script>

<style>

</style>
