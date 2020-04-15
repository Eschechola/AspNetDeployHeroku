# Deploy de aplicações ASP .NET Core X.X no Heroku

<br>

<font color="green">//Inicia o arquivo de versionamento</font>
<br>
git init

<br><br>

<font color="green">//Cria a aplicação no heroku</font>
<br>
heroku create NOME-APLICACAO --buildpack https://github.com/jincod/dotnetcore-buildpack
<br>
<strong>OBS:</strong><em> O nome deve conter somente letras minúsculas, números e hífens</em>

<br><br>

<font color="green">//Adiciona e versiona os arquivos</font>
<br>
git add .

<br><br>

<font color="green">//Adiciona um comentário a versão</font>
<br>
git commit -m "commit inicial"
	
 <br><br>
  
<font color="green">//Envia o projeto para o ambiente de produção</font>
<br>
git push heroku master

<br><br>

<font color="green">//Abre o projeto</font>
<br>
heroku open
