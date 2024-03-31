<template >
    <h1 class="events">Events</h1>
    <button v-on:click="getData('button 1 clicked')">click</button>
    <button v-on:click="getData('button 2 clicked')"> button2</button>
</template>
<script>
export default {
    name : "Events",// eslint-disable-line vue/multi-word-component-names
    methods :{
   getData(Data){
    alert(Data)
   }
    }
}
</script>


<style scoped>
.events{
    color:chocolate ;
    font-size: 8em;
}
</style>