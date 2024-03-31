<template>
    <h1>seeing input value</h1>
    <input type="email" placeholder="enter email" v-model="email"><br>
    <input type="password" placeholder="enter password" v-model="password"><br>
    <button v-on:click="getDatas()">click </button>
</template>
<script>
export default {
    name:'InputValue',// eslint-disable-line vue/multi-word-component-names
    data(){
return {
    email :null,
    password : null
}
    },
    methods:{
        getDatas(){
            console.log("entered email and password:",this.email,this.password)
        }
    }
}
</script>