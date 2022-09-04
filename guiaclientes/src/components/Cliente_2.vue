<template>
    <div id="cliente">
        <h4>Nome: {{nome}}</h4>
        <hr>
        <p>Descrição: {{descricao}}</p>
        <p>Email: {{email}}</p>
        <p>Idade: {{idade}}</p>
    </div>           
</template>
<script>
export default {  
    data() {
        return {
            descricao: "Cliente vips 5 estrelas, tem residencia  no Miami-Vice",
            numero: "990431613"            
        }
    },  
    props: {
        nome: String,
        email: String,
        idade: Number
    }
}
</script>
<style scoped>
    #cliente{
        color: blue;
        background-color: aqua;
        max-width:600px;
        height:240px;
        padding:3%;
    }
    #clienteNome{
        color: orangered;

    }

</style>