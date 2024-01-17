<script>
// Importazione 
import AppHeader from './components/AppHeader.vue';

export default {
    data() {
        return { 
            count: 0 
        };
    },
    components: {
        // Dichiarazione componente
        AppHeader
    }
};
</script>

<template>
    <div>
        <!-- Utilizzo componente -->
        <AppHeader/>
        
        <h1>Prova</h1>
        
        <p>{{count}}</p>
        
        <button @click="count++">
            Incrementa count
        </button>
    </div>
</template>

<style scoped>
</style>
