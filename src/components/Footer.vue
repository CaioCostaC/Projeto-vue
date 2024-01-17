<template>
    <footer id="footer">
        <p>Make  Your Burger &copy; 2024</p>
    </footer>
</template>

<script>
    export default {
        name: "Footer"
    }
</script>

<style scoped>
    #footer{
        height: 200px;
        background-color: #222;
        border-top: 4px solid #111;
        color: #FCBA03;
        display: flex;
        margin-top: 300px; /* Ação temporária para returar o bug do conteúdo na home sobrescrever o footer */
        align-items: center;
        justify-content: center;
        width: 100%;
    }
</style>