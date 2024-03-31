<template>
<h1 class="heads"> Two way binding in vue js</h1>
<p class="Data">{{ data }}</p>
<input type="text" v-model="data">
</template>

<script>
export default {
    name:'TwowayBinding',
    data (){
        return{
            data:0
        }
    }

}
</script>

<style>
.Data{
    color: brown;
    background-color: bisque;
    font-size: 2em;
}
.heads{
    color: rgb(74, 19, 214);
    font-size: 6em;
}
</style>