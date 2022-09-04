<template>
    <!--Para ter muitos componente é preciso usar tag DIV-->
    <div id="cliente">
        <!--Este recurso é usado com o v-model e usando as variaveis dentro
        da função data(){}-->
        <input type="text" v-model="nome">
        <input type="text" v-model="numero">
        <input type="text" :value="email">
        <input type="text" :value="idade">
        
        <h2 id="clienteNome">Cliente Aqui - {{ nome }}</h2>
        <h3>Registro de Clientes</h3> 
        <!--Expressoes de interpolação-->
        {{ 2+2+2*3 }}      
    </div>        
</template>
<script>
export default {  
    data() {
        return {
            numero: "990431613",
            email:"anderson77martins@outlook.com",
            idade:0
        }
    },  
    
}
</script>
<style scoped>
    #cliente{
        color: blue;
        background-color: aqua;
        max-width:600px;
        height:340px;
        padding: 3%;
        margin-top: 2%;
    }
    #clienteNome{
        color: orangered;

    }

</style>