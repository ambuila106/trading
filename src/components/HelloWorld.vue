<template>
  <div class="hello">
    <h1>Bienvenida a tus operaciones</h1>
    <div class="card">
      <h3>Actividades de hoy</h3>
      <p>
        La meditación y la relajación son importantes
      </p>
    </div>

    <div class="container">
      <h3>Ingresos Acumulados</h3>
      <p>$5000</p>
      <img src="../assets/dinero.jpg" alt="">
    </div>
    <button class="button" @click="alert()">retirar</button>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  methods: {
    alert: function() {
      alert('debes tener por lo menos 50mil pesos para poder retirar');
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

.card {
  margin: 0 1rem;
  padding: 1rem;
  height: 4.5rem;
  border-radius: .5rem;
  background-color: white;
  color: gold;
}

.card h3 {
  text-align: left;
  margin: 0;
  padding: 0;
}

.card p {
  color: black;
  text-align: left;
  margin-bottom: .5rem;
}

.container img {
  width: 15rem;
  border-radius: .5rem;
}

.button {
  width: 5rem;
  height: 1.5rem;
}
</style>
