<template>
  <div class="tabcontent">
    <h2>Paraty</h2>
    <div class="category">
      <h3>Restaurantes</h3>
      <div class="restaurant">
        <a
          href="https://www.tripadvisor.com.br/Restaurant_Review-g303503-d15450454-Reviews-Pero_Restaurante-Paraty_State_of_Rio_de_Janeiro.html"
          >Peró Restaurante</a
        >
        <p>Faixa de preço: $$ - $$$</p>
        <p>Avaliação: 5,0 (723 avaliações)</p>
      </div>
      <div class="restaurant">
        <a
          href="https://www.tripadvisor.com.br/Restaurant_Review-g303503-d26366180-Reviews-Hamburgueria_Insanos_Burguers_Paraty-Paraty_State_of_Rio_de_Janeiro.html"
          >Pizzaria Malagueta</a
        >
        <p>Avaliação: 3,5 (440 avaliações)</p>
      </div>
      <div class="restaurant">
        <a
          href="https://www.tripadvisor.com.br/Restaurant_Review-g303503-d2328490-Reviews-Punto_di_Vino-Paraty_State_of_Rio_de_Janeiro.html"
          >Punto di Vino</a
        >
        <p>Faixa de preço: $$ - $$$</p>
        <p>Avaliação: 4,0 (1.404 avaliações)</p>
      </div>
      <div class="restaurant">
        <a
          href="https://www.tripadvisor.com.br/Restaurant_Review-g303503-d1870285-Reviews-Restaurante_Refugio-Paraty_State_of_Rio_de_Janeiro.html"
          >Restaurante Refúgio</a
        >
        <p>Faixa de preço: $$$$</p>
        <p>Avaliação: 4,0 (1.011 avaliações)</p>
      </div>
      <div class="restaurant">
        <a
          href="https://www.tripadvisor.com.br/Restaurant_Review-g303503-d12375526-Reviews-Prosa_Restaurante-Paraty_State_of_Rio_de_Janeiro.html"
          >Prosa Restaurante</a
        >
        <p>Faixa de preço: $$ - $$$</p>
        <p>Avaliação: 5,0 (1.581 avaliações)</p>
      </div>
      <div class="restaurant">
        <a
          href="https://www.tripadvisor.com.br/Restaurant_Review-g303503-d8055517-Reviews-Sancho_Panca-Paraty_State_of_Rio_de_Janeiro.html"
          >Sancho Pança</a
        >
        <p>Faixa de preço: $$ - $$$</p>
        <p>Avaliação: 5,0 (922 avaliações)</p>
      </div>
      <div class="restaurant">
        <a
          href="https://www.tripadvisor.com.br/Restaurant_Review-g303503-d7087660-Reviews-Celeiro-Paraty_State_of_Rio_de_Janeiro.html"
          >Celeiro - Armazém Tropical</a
        >
        <p>Faixa de preço: $$ - $$$</p>
        <p>Avaliação: 4,5 (842 avaliações)</p>
      </div>
    </div>
    <div class="category">
      <h3>Hamburguerias</h3>
      <div class="restaurant">
        <a
          href="https://www.tripadvisor.com.br/Restaurant_Review-g303503-d26366180-Reviews-Hamburgueria_Insanos_Burguers_Paraty-Paraty_State_of_Rio_de_Janeiro.html"
          >Hamburgueria Insanos Burguers Paraty</a
        >
        <p>Avaliação: 5,0 (195 avaliações)</p>
      </div>
      <div class="restaurant">
        <a
          href="https://www.tripadvisor.com.br/Restaurant_Review-g303503-d10799406-Reviews-Van_Gogh_Hamburgueria-Paraty_State_of_Rio_de_Janeiro.html"
          >Van Gogh Hamburgueria</a
        >
        <p>Faixa de preço: $</p>
        <p>Avaliação: 4,5 (887 avaliações)</p>
      </div>
    </div>
    <div class="category">
      <h3>Doces</h3>
      <div class="restaurant">
        <a
          href="https://www.tripadvisor.com.br/Restaurant_Review-g303503-d5759473-Reviews-Sorveteria_Pistache-Paraty_State_of_Rio_de_Janeiro.html"
          >Sorveteria Pistache</a
        >
        <p>Faixa de preço: $$ - $$$</p>
        <p>Avaliação: 4,0 (726 avaliações)</p>
      </div>
    </div>

    <div class="category">
      <h3>Bebidas</h3>
      <div class="restaurant">
        <a
          href="https://www.tripadvisor.com.br/Attraction_Review-g303503-d12438072-Reviews-Cachacaria_Cana_Caiana-Paraty_State_of_Rio_de_Janeiro.html"
          >Cachaçaria Cana Caiana</a
        >
        <p>Avaliação: 4,5 (14 avaliações)</p>
      </div>
    </div>

    <div class="category">
      <h3>Opções Econômicas</h3>
      <div class="restaurant">
        <a
          href="https://www.tripadvisor.com.br/Restaurant_Review-g303503-d5759563-Reviews-Quero_Mais_Restaurante-Paraty_State_of_Rio_de_Janeiro.html"
          >Quero Mais Restaurante</a
        >
        <p>Faixa de preço: $</p>
        <p>Avaliação: 3,0 (48 avaliações)</p>
      </div>
      <div class="restaurant">
        <a
          href="https://www.tripadvisor.com.br/Restaurant_Review-g303503-d6033890-Reviews-Manue-Paraty_State_of_Rio_de_Janeiro.html"
          >Manuê</a
        >
        <p>Faixa de preço: $</p>
        <p>Avaliação: 4,5 (748 avaliações)</p>
      </div>
    </div>
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
