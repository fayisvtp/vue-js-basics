<template>
  <h3 style="color: blue">name : {{ getName().email }}</h3>
  <h2 style="color: brown">Email : {{ getEmail("faty") }}</h2>
  <h2 style="color: blueviolet;">Datas:  {{ getData().email }}</h2>
</template>
<script>
export default {
  name: "methods", // eslint-disable-line vue/multi-word-component-names
  methods: {
    getName() {
      return {
        email: 'fayisvtp@gmail.coms'
      }
    },
    getEmail(name) {
      return  name ;
    },
    getData(){
        return{
            name: "fayis",
            country :"india",
            email :this.email
        }
    }
  },
};
</script>
