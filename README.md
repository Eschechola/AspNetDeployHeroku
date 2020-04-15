# Deploy de aplicações ASP .NET Core X.X no Heroku

<br>

+ //Inicia o arquivo de versionamento
<br>
git init

<br><br>

+ //Cria a aplicação no heroku
<br>
heroku create NOME-APLICACAO --buildpack https://github.com/jincod/dotnetcore-buildpack
<br>
<strong>OBS:</strong><em> O nome deve conter somente letras minúsculas, números e hífens</em>

<br><br>

+ //Adiciona e versiona os arquivos
<br>
git add .

<br><br>

+ //Adiciona um comentário a versão
<br>
git commit -m "commit inicial"
	
 <br><br>
  
+ //Envia o projeto para o ambiente de produção
<br>
git push heroku master

<br><br>

+ //Abre o projeto
<br>
heroku open
