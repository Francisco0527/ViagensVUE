<template>
  <div class="tabcontent">
    <h2>Gramado</h2>
    <p>Conteúdo para Gramado em breve.</p>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.tabcontent {
  padding: 20px;
  background-color: rgba(0, 0, 0, 0.7);
  border-radius: 10px;
  width: 60%;
  margin: auto;
  color: #ccc;
  text-align: left;
  height: 75vh;
  max-height: 90vh;
  overflow-y: auto;
}
/* Estilizando a barra de rolagem para navegadores baseados em WebKit */
.tabcontent::-webkit-scrollbar {
  width: 8px; /* Largura da barra de rolagem */
}

.tabcontent::-webkit-scrollbar-track {
  background: rgba(255, 255, 255, 0.1); /* Cor do fundo da barra de rolagem */
}

.tabcontent::-webkit-scrollbar-thumb {
  background-color: rgba(
    255,
    255,
    255,
    0.5
  ); /* Cor do "polegar" (a parte que se move) */
  border-radius: 10px; /* Cantos arredondados para suavidade */
  border: 2px solid rgba(0, 0, 0, 0.3); /* Um leve contorno para dar um efeito de profundidade */
}

.tabcontent::-webkit-scrollbar-thumb:hover {
  background-color: rgba(
    255,
    255,
    255,
    0.7
  ); /* Muda de cor ao passar o mouse */
}

/* Para navegadores que não suportam WebKit (como Firefox), você pode usar a propriedade scrollbar-color */
.tabcontent {
  scrollbar-width: thin; /* Define uma barra de rolagem fina no Firefox */
  scrollbar-color: rgba(255, 255, 255, 0.5) rgba(255, 255, 255, 0.1); /* Cor do polegar e do fundo no Firefox */
}
.tabcontent h2 {
  color: #fff;
  margin-top: 0;
  font-size: 28px;
}
.tabcontent h3 {
  color: #fff;
  margin-top: 0;
  font-size: 24px;
  padding-top: 18px;
  padding-bottom: 8px;
}
.tabcontent a {
  color: #b78655;
  margin-top: 0;
  font-size: 18px;
  padding-top: 4px;
  text-decoration: none;
}
.tabcontent p {
  color: #ccc;
  margin-top: 0;
  font-size: 18px;
  padding-top: 4px;
  padding-bottom: 2px;
}
@media (max-width: 900px) {
  .tablinks {
    font-size: 14px;
  }
  .tabcontent {
    width: 80%;
    font-size: 14px;
  }
}
</style>
