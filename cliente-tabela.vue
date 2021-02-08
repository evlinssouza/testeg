<template>
    <div id="cliente">
      <h4>nome: {{nome}}</h4>
      <hr>
      <p>numero: {{numero}}</p>
      <p>email:{{email}}</p>
      <p>senha:{{senha}}</p>
      <p>cpf:{{cpf}}</p>
      <p>cnpj:{{cnpj}}</p>
    </div>
</template>
    <script>
export default {
    data(){
        return{
            numero:"2323",
            senha:"234234",
            cpf: 0,
            cnpj:0,
        }
    },
           props: {
            nome: String,
            email:String,
            idade:String,

       }
}
</script>

<style scoped>
    #cliente{
        background-color :pink;
        max-width: 200px;
        height: 150px;
        padding: 1%;
    }
</style>

