<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Cadastro de Participante - Evento</title>
</head>
<body>

  <h1>Formulário de Cadastro para Evento</h1>

  <form action="#" method="post">
    <fieldset>
      <legend>Informações Pessoais</legend>

      <label for="nome">Nome completo:</label><br>
      <input type="text" id="nome" name="nome" required><br><br>

      <label for="cpf">CPF:</label><br>
      <input type="text" id="cpf" name="cpf" maxlength="14" required><br><br>

      <label for="rg">RG:</label><br>
      <input type="text" id="rg" name="rg"><br><br>

      <label for="nascimento">Data de nascimento:</label><br>
      <input type="date" id="nascimento" name="nascimento" required><br><br>

      <label>Gênero:</label><br>
      <input type="radio" name="genero" value="masculino"> Masculino
      <input type="radio" name="genero" value="feminino"> Feminino
      <input type="radio" name="genero" value="outro"> Outro<br><br>
    </fieldset>

    <br>

    <fieldset>
      <legend>Contato</legend>

      <label for="email">E-mail:</label><br>
      <input type="email" id="email" name="email" required><br><br>

      <label for="telefone">Telefone:</label><br>
      <input type="tel" id="telefone" name="telefone" required><br><br>

      <label for="whatsapp">WhatsApp:</label><br>
      <input type="tel" id="whatsapp" name="whatsapp"><br><br>
    </fieldset>

    <br>

    <fieldset>
      <legend>Endereço</legend>

      <label for="endereco">Endereço:</label><br>
      <input type="text" id="endereco" name="endereco" required><br><br>

      <label for="numero">Número:</label><br>
      <input type="text" id="numero" name="numero" required><br><br>

      <label for="bairro">Bairro:</label><br>
      <input type="text" id="bairro" name="bairro"><br><br>

      <label for="cidade">Cidade:</label><br>
      <input type="text" id="cidade" name="cidade" required><br><br>

      <label for="estado">Estado:</label><br>
      <select id="estado" name="estado" required>
        <option value="">Selecione</option>
        <option value="SP">São Paulo</option>
        <option value="RJ">Rio de Janeiro</option>
        <option value="MG">Minas Gerais</option>
        <option value="RS">Rio Grande do Sul</option>
        <option value="BA">Bahia</option>
        <option value="PR">Paraná</option>
        <!-- Adicione mais estados conforme necessário -->
      </select><br><br>

      <label for="cep">CEP:</label><br>
      <input type="text" id="cep" name="cep" maxlength="9"><br><br>
    </fieldset>

    <br>

    <fieldset>
      <legend>Informações do Evento</legend>

      <label for="evento">Nome do evento:</label><br>
      <input type="text" id="evento" name="evento" value="Conferência Tech 2025" readonly><br><br>

      <label for="tipo_ingresso">Tipo de ingresso:</label><br>
      <select id="tipo_ingresso" name="tipo_ingresso" required>
        <option value="gratuito">Gratuito</option>
        <option value="meia">Meia-entrada</option>
        <option value="inteira">Inteira</option>
        <option value="vip">VIP</option>
      </select><br><br>

      <label for="disponibilidade">Você estará disponível nos dias do evento?</label><br>
      <input type="checkbox" name="disponibilidade1" value="dia1"> Dia 1<br>
      <input type="checkbox" name="disponibilidade2" value="dia2"> Dia 2<br>
      <input type="checkbox" name="disponibilidade3" value="dia3"> Dia 3<br><br>

      <label for="observacoes">Observações ou necessidades especiais:</label><br>
      <textarea id="observacoes" name="observacoes" rows="4" cols="50" placeholder="Descreva aqui..."></textarea><br><br>
    </fieldset>

    <br>

    <input type="submit" value="Enviar Cadastro">
    <input type="reset" value="Limpar Formulário">

  </form>

</body>
</html>
