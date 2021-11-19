<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Para que rememores las interminables horas que nos hemos pasado jugando a
      cierto juego nos gustaría que empleases el crédito que te vamos a regalar
      para que te compres la versión remasterizada para videoconsola:
    </p>
    <ul>
      <li>
        <a
          href="https://www.playstation.com/es-es/games/diablo-ii-resurrected/"
          target="_blank"
          rel="noopener"
        >
          Diablo 2 Resurrected
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: {
      type: String,
      default: "",
    },
  },
};
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
p {
  max-width: 20rem;
}
.hello {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  min-height: 80vh;
  background-color: rgba(0, 0, 0, 0.33);
}
</style>
