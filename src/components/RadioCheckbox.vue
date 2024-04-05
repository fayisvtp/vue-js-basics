<template>
  <h2>check box and Radio</h2>
  <h4>tachnology</h4>
  <label for="java">java</label>
  <input type="checkbox" value="java" id="java" v-model="technology" />
  <br />
  <label for="js">js</label>
  <input type="checkbox" value="js" id="js" v-model="technology" />
  <br />
  <label for="Python">Python</label>
  <input type="checkbox" value="Python" id="Python" v-model="technology" />
  <br />
 <h2>Proffession</h2>
 <br />
  <label for="student">Student</label>
  <input type="radio" value="student   " id="student" v-model="proffession" />
<br>
  <label for="Developer">Developer</label>
  <input type="radio" value="Developer   " id="Developer" v-model="proffession" />
  <br />

  <h2 style="color: blue">Technology {{ technology }}</h2>
  <h2>I am a {{ proffession }}</h2>
</template>

<script>
export default {
  name: "RadioCheckbox",
  data() {
    return {
      technology: [],
      proffession : null
    };
  },
};
</script>
