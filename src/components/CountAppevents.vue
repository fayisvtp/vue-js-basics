<template>
    <h1>CountAppevents</h1>
    <h3>{{ count }}</h3>
    <button v-on:click="increment()">increment</button>
    <button v-on:click="decrement()">Decrement</button>
</template>

<script>
export default {
    name :'CountAppevents',
    data(){
        return {

            count:0
        }
    },
    methods:{
        increment(){
       this.count = this.count +1
        },
        decrement(){
            if (this.count>0){

                this.count = this.count -1
            }
        }
    }

}
</script>