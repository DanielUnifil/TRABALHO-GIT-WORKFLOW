<template>
  <div class="landing-page">
    <header>
      <h1>Bem-vindo à Cafeteria Cidade do Café</h1>
      <p>Saboreie os melhores cafés, bolos e lanches da cidade.</p>
    </header>
    <section>
      <h2>Nossos Destaques</h2>
      <div class="product">
        <h3>Café Especial</h3>
        <img src="@/assets//image/coffee-image.jpg" alt="Café Especial">
        <p>Experimente nossos cafés especiais cuidadosamente selecionados.</p>
      </div>
      <div class="product">
        <h3>Bolo de Chocolate</h3>
        <img src="@/assets//image/cake.jpg" alt="Bolo de Chocolate">
        <p>Delicioso bolo de chocolate com cobertura de ganache.</p>
      </div>
    </section>
    <section>
      <h2>Nossa Localização</h2>
      <p>Estamos localizados no centro da cidade, venha nos visitar!</p>
      <p>Horário de Funcionamento:</p>
      <ul>
        <li>Segunda a Sexta: 7:00 - 19:00</li>
        <li>Sábado e Domingo: 8:00 - 16:00</li>
      </ul>
    </section>
    <section>
      <h2>Sobre Nós</h2>
      <p>Somos uma cafeteria apaixonada por café de alta qualidade. Nossa jornada começou com a busca por grãos de café nas plantações do Brasil, Colômbia e Etiópia.</p>
      <p>Cada xícara de café na "Cidade do Café" é uma obra de arte, preparada pelos nossos baristas especializados. Queremos tornar cada visita memorável para você.</p>
      <p>Nossa missão é proporcionar uma experiência única de café em um ambiente acolhedor e amigável.</p>
    </section>
  </div>
</template>

<script>
export default {
  name: "LandingPage",
};
</script>

<style scoped>
/* Estilos CSS personalizados aqui */
.landing-page {
  font-family: Arial, sans-serif;
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
  background-color: #f5f5f5; /* Fundo cinza claro */
  color: #333; /* Fontes escuras */
}

header {
  text-align: center;
  padding: 20px;
}

h1 {
  font-size: 36px;
  margin: 0;
  color: #333;
}

p {
  font-size: 18px;
  color: #666;
}

section {
  margin-top: 30px;
}

h2 {
  font-size: 28px;
  margin-bottom: 10px;
  color: #333;
}

.product {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: 20px;
}

.product img {
  max-width: 100%;
}

.product h3 {
  font-size: 24px;
  margin-top: 10px;
  color: #333;
}

.product p {
  font-size: 16px;
  text-align: center;
  color: #666;
}

ul {
  list-style-type: disc;
  margin-left: 20px;
}

</style>
