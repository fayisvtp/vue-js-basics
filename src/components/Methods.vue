<template>
  <h3 style="color: blue">name : {{ getName().names }}</h3>
  <h2 style="color: brown">Email : {{ getEmail("faty") }}</h2>
  <h2 style="color: blueviolet;">Datas:  {{ getData().email }}</h2>
</template>
<script>
export default {
  name: "methods", // eslint-disable-line vue/multi-word-component-names
  methods: {
    getName() {
      return {
        names: 'fayisvtp'
      }
    },
    getEmail(name) {
      return  name ;
    },
    getData(){
        const Obj = this.getName();
        return{
            name: "fayis",
            country :"india",
            email :Obj.names
        }
    }
  },
};
</script>
