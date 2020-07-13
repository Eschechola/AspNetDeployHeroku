# Deploy de aplicações ASP .NET Core X.X no Heroku


<p>
	Artigo demonstrando como realizar o deploy de aplicações ASP .NEt Core X no Heroku
	<br>
	Link: https://eschechola.com.br/2020/04/15/hospedando-uma-aplicacao-asp-net-core-no-heroku
</p>

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
heroku create <strong>NOME-APLICACAO</strong> --buildpack https://github.com/jincod/dotnetcore-buildpack<strong>#VERSAO</strong>
<br><br>
<strong>Versões: </strong><a href="https://github.com/jincod/dotnetcore-buildpack/releases">aqui</a>
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
