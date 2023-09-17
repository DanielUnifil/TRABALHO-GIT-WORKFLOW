<template>
  <div class="contact-page">
    <header>
      <h1>Entre em Contato Conosco</h1>
      <p>Estamos ansiosos para ouvir de você.</p>
    </header>
    <section>
      <h2>Informações de Contato</h2>
      <p>Endereço: Rua das Flores, 123 - Centro</p>
      <p>Telefone: (11) 1234-5678</p>
      <p>E-mail: contato@cidadedocafe.com</p>
    </section>
    <section>
      <h2>Formulário de Contato</h2>
      <form>
        <div class="form-group">
          <label for="name">Nome:</label>
          <input type="text" id="name" name="name" required>
        </div>
        <div class="form-group">
          <label for="email">E-mail:</label>
          <input type="email" id="email" name="email" required>
        </div>
        <div class="form-group">
          <label for="message">Mensagem:</label>
          <textarea id="message" name="message" rows="4" required></textarea>
        </div>
        <button type="submit">Enviar</button>
      </form>
    </section>
  </div>
</template>

<script>
export default {
  name: "ContactPage",
};
</script>

<style scoped>
/* Estilos CSS personalizados aqui */
.contact-page {
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

form {
  display: flex;
  flex-direction: column;
}

.form-group {
  margin-bottom: 20px;
}

label {
  font-size: 18px;
  color: #333;
}

input[type="text"],
input[type="email"],
textarea {
  width: 100%;
  padding: 10px;
  font-size: 16px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

button {
  background-color: #333;
  color: #fff;
  padding: 10px 20px;
  font-size: 18px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

</style>
