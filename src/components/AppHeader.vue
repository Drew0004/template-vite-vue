<script>
export default {
    data() {
        return { 
            title: 'Titolo Header' 
        };
    },
};
</script>

<template>
    <header>
        <h1>{{ title }}</h1>
    </header>
</template>

<style scoped>
    header{
        padding: 20px;
        background-color: green;
    }
    h1{
        text-align: center;
    }
</style>
