<template>
    <div>
     <h1>{{ userName }}</h1>  
<h2>{{ data }}</h2>
<h2>{{ msg }}</h2>
    </div>
</template>
<script>
export default {
   name: 'Home', // eslint-disable-line vue/multi-word-component-names
    props:{
        userName:String,
        data:String,
        msg :String

    }
}
</script>
