# ATIVIDADE0_11-03_HTML 

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Ficha de Inscrição</title>
</head>

<body>

<h2 align="center">Ficha de Inscrição</h2>

<form>

<table border="1" align="center">

<tr>
<td>Nome do candidato:</td>
<td colspan="5">
<input type="text" name="nome" size="60">
</td>
</tr>

<tr>
<td>Endereço:</td>
<td colspan="5">
<input type="text" name="endereco" size="60">
</td>
</tr>

<tr>
<td>CEP:</td>
<td><input type="text" name="cep"></td>

<td>Cidade:</td>
<td>
<select name="cidade">
<option>-- Cidade --</option>
<option>Brasília</option>
<option>Goiânia</option>
<option>São Paulo</option>
</select>
</td>

<td>UF:</td>
<td>
<select name="uf">
<option>-- UF --</option>
<option>DF</option>
<option>GO</option>
<option>SP</option>
<option>RJ</option>
</select>
</td>
</tr>

<tr>
<td>Telefone:</td>
<td colspan="5">
<input type="text" name="telefone">
</td>
</tr>

<tr>
<td>RG:</td>
<td><input type="text" name="rg"></td>

<td>CPF:</td>
<td><input type="text" name="cpf"></td>

<td>Sexo:</td>
<td>
<input type="radio" name="sexo" value="masc"> Mas.
<input type="radio" name="sexo" value="fem"> Fem.
</td>
</tr>

<tr>
<td>Escolaridade:</td>
<td>
<select name="escolaridade">
<option>-- Selecione --</option>
<option>Ensino Médio</option>
<option>Superior Incompleto</option>
<option>Superior Completo</option>
</select>
</td>

<td>Email:</td>
<td colspan="3">
<input type="email" name="email" size="30">
</td>
</tr>

<tr>
<td>Curso:</td>
<td>
<select name="curso">
<option>-- Selecione --</option>
<option>Análise e Desenvolvimento de Sistemas</option>
<option>Administração</option>
<option>Direito</option>
</select>
</td>

<td>Senha de acompanhamento:</td>
<td colspan="3">
<input type="password" name="senha">
</td>
</tr>

<tr>
<td colspan="6" align="center">
<input type="submit" value="CADASTRAR">
</td>
</tr>

</table>

</form>

</body>
</html>
