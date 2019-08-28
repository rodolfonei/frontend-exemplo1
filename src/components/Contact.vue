<template>
  <section class="container py-5">
    <h1>CONTATO</h1>
    <p>Ut vitae volutpat risus. Nam vitae congue odio, mattis dignissim neque. Nam eros sapien, semper in pellentesque ut, suscipit eu nunc. Donec malesuada egestas ligula, non malesuada sapien suscipit ut.</p>
    <!-- Formulário de Contato -->
    <form class="d-flex flex-wrap flex-lg-nowrap justify-content-between">
      <!-- Primeira Metade do Form -->
      <div class="col-12 col-lg-6 p-0 my-3">
        <!-- Nome -->
        <div class="d-flex flex-column">
          <label for="contato-nome">Nome*</label>
          <input class="form-control" id="contato-nome" type="text" placeholder="Nome" required>
          <div class="invalid-feedback">
            Please choose a username.
          </div>
        </div>
        <!-- Email -->
        <div class="d-flex flex-column">
          <label for="contato-email">E-mail*</label>
          <input id="contato-email" type="text" placeholder="E-mail" required>
        </div>
        <!-- Cidade -->
        <div class="d-flex flex-column">
          <label for="contato-cidade">Cidade</label>
          <input id="contato-cidade" type="text" placeholder="Cidade">
        </div>
        <!-- Telefone -->
        <div class="d-flex flex-column">
          <label for="contato-telefone">Telefone*</label>
          <input id="contato-telefone" type="text" placeholder="(99) 99999999" required>
        </div>
      </div>
      <!-- Segunda Metade do Form -->
      <div class="col-12 col-lg-6 p-0 ml-lg-3 my-lg-3">
        <!-- Assunto -->
        <div class="d-flex flex-column">
          <label for="contato-assunto">Assunto*</label>
          <input id="contato-assunto" type="text" placeholder="Assunto" required>
        </div>
        <!-- Mensagem -->
        <div class="d-flex flex-column">
          <label for="contato-mensagem">Mensagem*</label>
          <textarea id="contato-mensagem" placeholder="Digite aqui sua mensagem..." required></textarea>
        </div>
        <!-- Botão Submit -->
        <div class="text-right">
          <input id="submit-btn" type="submit" value="Enviar">
        </div>
      </div>
    </form>
  </section>
</template>

<style>

  form div > div {
    margin: 20px 0;
  }

  form label {
    font-weight: bolder;
  }

  form input {
    padding: 6px;
  }

  textarea {
    height: 222px;
  }

  #submit-btn {
    color: white;
    background-color: yellow;
    border: 1px solid white;
    background-color: rgb(64,50,37);
    padding: 8px 50px;
  }

  #submit-btn:hover {
    color: rgb(64,50,37);
    background-color: white;
    border: 1px solid rgb(64,50,37);
    transition: 0.2s;
  }

</style>