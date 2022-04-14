<script></script>
<template>
  <header>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">Comunidade</a></li>
      <li><a href="#">Sobre</a></li>
      <li><a href="#">Ajuda</a></li>
    </ul>
  </header>
  <main>
    <h1>Titulo</h1>
    <br />
    <p>Me senti muito legal hj professor vai mudar o modo de ensinar Vue</p>
  </main>
</template>
<style>
header {
  background-color: aqua;
}
ul {
  text-align: center;
  display: flex;
  justify-content: space-around;
  list-style: none;
}
ul li {
  text-align: center;
  padding: 10px;
}
ul li a {
  text-decoration: none;
  color: black;
}
ul li:hover {
  background-color: gray;
}
h1 {
  text-align: center;
}
p {
  text-align: center;
}
</style>
