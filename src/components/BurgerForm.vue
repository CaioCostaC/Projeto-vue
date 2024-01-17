<template>
    <div>
        <p>Componente de mensagem</p>
        <div>
            <form id="burger-form">
                <div class="input-container">
                    <label for="nome">Nome do cliente:</label>
                    <input type="text" id="id" class="name" v-model="nome" placeholder="Digite o seu nome">
                </div>
                <div class="input-container">
                    <label for="pao">Escolha o pão:</label>
                    <select name="pao" id="pao" v-model="pao">
                        <option value="">Selecione o seu pão</option>
                        <option value="Integral">Integral</option>
                    </select>
                </div>
                <div class="input-container">
                    <label for="pao">Escolha a carne do seu bruger:</label>
                    <select name="pao" id="pao" v-model="carne">
                        <option value="">Selecione sua carne</option>
                        <option value="Integral">Maminha</option>
                    </select>
                </div>
                <div class="input-container">
                    <label for="opcionais">Escolha os opcionaopcionais</label>
                    <div class="checkbox-container">
                        <input type="checkbox" name="opcionais" v-model="opcionais" value="salame">
                        <span>Salame</span>
                    </div>
                </div>
                <div class="inpput-container">
                    <input type="submit" class="submit-btn" value="Criar meu Burger"> 
                </div>
            </form>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'BurgerForm'
    }
</script>

<style scoped>
    #burger-form{
        max-width:400px;
        margin: 0 auto;
    }
    .input-container{
        display: flex;
        flex-direction: column;
        margin-bottom: 20px;
    }
    label{
        font-weight: bold;
        margin-bottom: 15px;
        color: #222;
        padding: 5px 10px;
        border-left: 4px solid #fcba03;
    }
</style>