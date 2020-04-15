# Deploy de aplicações ASP .NET Core X.X no Heroku

<br>

```diff
+ //Inicia o arquivo de versionamento
````
<br>
git init

<br><br>

```diff
+ //Cria a aplicação e o ambiente no heroku
````
<br>
heroku create NOME-APLICACAO --buildpack https://github.com/jincod/dotnetcore-buildpack
<br><br>
<strong>OBS:</strong><em> O nome deve conter somente letras minúsculas, números e hífens</em>

<br><br>

```diff
+ //Adiciona e versiona os arquivos
````
<br>
git add .

<br><br>

```diff
+ //Adiciona um comentário a versão
````
<br>
git commit -m "commit inicial"
	
 <br><br>
  
```diff
+ //Envia o projeto para o ambiente de produção
````
<br>
git push heroku master

<br><br>

```diff
+ //Abre o projeto
````
<br>
heroku open

<br><br>
<br><br>
<p align="center">2020</p>
