<template>
    <h2>Parent Componunt</h2>
    <child name="fayis"/>
</template>

<script>
import Child from './Child.vue'
export default {
    name :'Parent',// eslint-disable-line vue/multi-word-component-names
    components:{
        Child

    }

}
</script>