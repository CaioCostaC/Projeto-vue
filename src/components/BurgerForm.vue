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
                    <label for="pao">Escolha a carde do seu bruger:</label>
                    <select name="pao" id="pao" v-model="carne">
                        <option value="">Selecione sua carne</option>
                        <option value="Integral">Maminha</option>
                    </select>
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