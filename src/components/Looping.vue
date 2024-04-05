<template>
    <h1>For loop in Vue js</h1>

    <ul>
        <li style="color: cadetblue;background-color: blueviolet;" v-for="item in technology" :key="item">
        {{ item }}
    </li>
    <li v-for ="item in users" :key="item.id">
    name is : {{ item.name }} email is {{ item.email}}
</li>
    </ul>
</template>

<script>
export default {
    name :'Looping',// eslint-disable-line vue/multi-word-component-names
    data(){
        return{
            technology : [
                 "javascript","node js", "html" ],
                 users : [{
                    
                    id : '1',
                    name : 'fayis',
                    email: 'vtpfayis@gmail.com'
  
                 },
                 {
                    id : '1',
                    name : 'asad',
                    email : 'azad@gmail.com'
                 }
              
                
                ]
            
        }
    }
}
</script>