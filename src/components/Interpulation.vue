<template>
    <h1>User name :{{ username }}</h1>
    <h2>Email : {{ email }}</h2>
    <h3>Contact : {{ phone }}</h3>


</template>
<script>
export default {
    name:'Interpulatian', // eslint-disable-line vue/multi-word-component-names
    data (){
        return{
            username : "fayis",
            email :"vtpfayis@gmail.com",
            phone : 9876543210
            
        }
    }
}
</script>