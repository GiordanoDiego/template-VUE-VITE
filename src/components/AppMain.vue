<script>
/* Come faccio ad utilizzare un componente dentro un altro?
        Si seguono 3 passaggi:
        1) Importazione del componente
        2) Dichiarazione del componente all'interno dell'oggetto
        3) Utilizzo del componente    
*/

export default {
    data(){
        return{
            
        }
    },
    components: {
       
    },
   
    methods: {

    }
}


</script>

<template>
    <main>
        <div class="my_container">
            main
        </div>
    </main>
</template>

<style lang="scss" scoped>
    @use'../assets/SCSS/main.scss';
</style>
