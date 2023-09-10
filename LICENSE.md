
html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="estilo.css">
    <title>Formulário de Cadastro</title>
</head>
<body>
    <form action="cadastro.html" method="POST">
        <fieldset>
            <legend>Dados Pessoais</legend>
            <label for="nome">Nome completo:</label>
            <input type="text" id="nome" name="nome" required><br><br>

            <label for="cpf">CPF:</label>
            <input type="text" id="cpf" name="cpf" required><br><br>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br><br>

            <label for="endereco">Endereço:</label>
            <input type="text" id="endereco" name="endereco" required><br><br>
            
            <label for="bairro">Bairro:</label>
            <input type="text" id="bairro" name="bairro" required><br><br>

            <label for="cidade">Cidade:</label>
            <input type="text" id="cidade" name="cidade" required><br><br>

            <label for="uf">UF:</label>
            <select id="uf" name="uf" required>
                <option value="AC">Acre</option>
                <option value="AL">Alagoas</option>
                <!-- Adicione as opções para os outros estados -->
            </select><br><br>

            <label for="cep">CEP:</label>
            <input type="text" id="cep" name="cep" required><br><br>

            <label for="dataNascimento">Data de Nascimento:</label>
            <input type="date" id="dataNascimento" name="dataNascimento" required><br><br>
        </fieldset>

        <fieldset>
            <legend>Dados de Contato</legend>
            <label for="celular">Celular:</label>
            <input type="text" id="celular" name="celular" required><br><br>
        </fieldset>

        <fieldset>
            <legend>Dados de Cadastro</legend>
            <label for="login">Login:</label>
            <input type="text" id="login" name="login" required><br><br>

            <label for="senha">Senha:</label>
            <input type="password" id="senha" name="senha" required><br><br>
        </fieldset>

        <input type="submit" value="Enviar">
    </form>
</body>
</html>

