# LearningPHP
> # Aprendendo Php
This is a repository maden for who wants to learn PHP and they who are a beginner in this programming language.


>Esse é um repositório que foi feito para quem quer aprender PHP e para os iniciantes nessa linguagem de programação.

For better learning is cool that you have knowledge in the basic of programming logic and web development (HTML/CSS and Javascript)
> Para melhor aprendizado é legal que você tenha conhecimento no básico de lógica de programação e no desenvolvimento web (HTML/CSS e Javascript)

Obs: If you don't know this technologies you can learn them looking the some links in the end of the page
> Obs: Se você não conhece essas tecnologias, pode aprendê-las procurando nos links no final da página

---
## What is PHP?
> ## O que é PHP?

PHP (recursive acronym for PHP: Hypertext Preprocessor) is a widely-used open source general-purpose scripting language that is especially suited for web development and can be embedded into HTML.

>O PHP (um acrônimo recursivo para PHP: Hypertext Preprocessor) é uma linguagem de script open source de uso geral, muito utilizada, e especialmente adequada para o desenvolvimento web e que pode ser embutida dentro do HTML.

---

## "Hello World!" example in PHP
> ## Exemplo de um "Hello World" em PHP
```php
<!DOCTYPE html>
<html>
<head>
    <title>Hello World Example</title>
</head>

<body>
    <?php 
        echo "Hello World!";
    ?>
</body>
</html>
```
In this case all the PHP code are between __*\<?php*__ and __*?>*__. So you can embedded the code PHP inside of a HTML page and only the code PHP will be interpreted by the server and will return to the user only HTML.
> Nesse caso todo o código PHP está entre __*\<?php*__ and __*?>*__. Então, você pode incorporar o código PHP dentro de uma página HTML e apenas o código PHP irá ser interpretado pelo servidor e retornará para o usuário apenas HTML

---

## Important settings
> ## Configurações importantes
If you want to learn PHP you will of the language PHP code and a server and the most popular server that you can use is the apache
> Se você quer aprender PHP você precisará de um servidor que interprete o código PHP e o servidor mais popular é o apache

PHP is a server side programming language and generally when you use it you will make connections to databases
> PHP é uma linguagem server side (interpretada no servidor) e, geralmente, quando você usá-lo você fará conexões com bancos de dados

For this reason you may need a database installed on your machine in the future and we will use the mysql database, which is the most popular today
> Por esse motivo você futuramente pode precisar de um banco de dados instalado na sua máquina e nós vamos utilizar o banco mysql, que é o mais popular atualmente

When you install the Apache, MySQL and PHP, we call this AMP. So to some programmers says that you will need a AMP to run PHP and to learn PHP I recommend you to use XAMPP:
> Quando você instala o Apache, MySQL e PHP, chamamos isso de AMP. Então, para alguns programadores, diz que você precisará de um AMP para executar o PHP e aprender PHP, eu recomendo que você use o XAMPP:

X - Many Operational Systems (Vários sistemas operacionais)

A - Apache

M - MySQL

P - PHP

P - Perl

You can download xampp in <https://www.apachefriends.org/pt_br/index.html>
> Você pode baixar o xampp em <https://www.apachefriends.org/pt_br/index.html>

When you install the xampp make this:
> Quando você instalar o xampp faça isso
- Open the *Xampp Control Panel* (Abra o *Xampp Control Panel*)
- Start the apache (Inicie o apache)
- Go to (Vá para):
   - C:/xampp/htdocs/
   - Delete all in this folder (Delete tudo nessa pasta)
- Open this folder in your favorite text editor (Abra essa pasta no seu editor de texto favorito)
- Make a file caled **_index.php_** and copy this (Faça um arquivo chamado **_index.php_** e copie isso):
```php
<?php
echo "Hello world!";
```
- Open *<http://localhost>* in your browser (Abra *<http://localhost>* no seu navegador)
- May be showed __Hello World!__ in your browser (Deve aparecer __Hello World!__ no seu navegador)

---

#### What process was make:
> #### Qual processo foi feito:

When you acess a website you always acess the website by the port 80 (port default)
> Quando você acessa um website, você sempre acessa ele pela porta 80 (porta padrão)

When you start apache you create a local server in your machine that will be visible in the port 80 in your machine
> Quando você inicia o apache, você cria um servidor local na sua máquina que será visível na porta 80 da sua máquina

To acess your machine you can go in browser and acess:
> Para acessar sua máquina, você pode ir no browser e acessar

- <http://127.0.0.1> or(ou) <http://localhost>

The apache will be called and will acess acess the folder C:/xampp/htdocs/ searching the file index.html and if doesn't exists will search the file index.php and in the index.php all PHP code will be interpreted by the PHP and the return it's only HTML for the browser.
> O apache será chamado e acessará a pasta C:/xampp/htdocs/procurando pelo arquivo index.html e se o arquivo não existir ele procura pelo arquivo index.php e no index.php todo o código PHP será interpretado pelo PHP e retornará apenas HTML para o navegador

OBS: In the index.php, we just open the tag **_\<?php_**, and we don't close with **_\?>_**, this is beacuse the file has only PHP and nothing more, so we can don't close the tag **_\<?php_**
> OBS: No arquivo index.php, nós apenas abrimos a tag  **_\<?php_**, e nós não fechamos com **_\?>_**, isso é porque o arquivo contém apenas PHP e nada mais, então nós podemos não fechar a tag **_\<?php_**
---

### Comments in PHP
> ### Comentários em PHP

In your search by the knowledge in PHP (or any programming language), you will see comments, that serve to explain for who is reading the code what something in code is made for. We leave comments in our programs that will show to you read about what the progran is doing.
> Na sua busca pelo conhecimento em PHP (ou qualquer linguagem de programação), você verá comentários que serve para explicar para quem estiver lendo o código para que o código foi feito. Nós deixamos comentários em nossos programas que mostrarão para você ler sobre o que o programa está fazendo 

The Comments in PHP is like this:
> Os comentários em PHP são dessa maneira:
```php
<?php
// One line comment

# Another line comment

/*
    One line comment
    Two line comment
*/
```

### And now?
> ### E agora?
 
Now you will have a process step-by-step to learn the basic of PHP, if you want some place to study, you can see the links in down of this list:
> Agora você terá um processo passo-a-passo para aprender o básico de PHP, se você quiser algum lugar para estudar,você pode ver os links abaixo dessa lista

- [Introduction (Introdução)](https://github.com/Luan-Farias/LearningPHP/blob/master/Introduction)

#### Some places to learn:
> #### Alguns lugares para aprender: 

- Programming Logic (Lógica de programação)
   - <https://www.youtube.com/watch?v=8mei6uVttho&list=PLHz_AreHm4dmSj0MHol_aoNYCSGFqvfXV>
   - <https://www.youtube.com/watch?v=4ZAOWlZRbZk&list=PLwXQLZ3FdTVG_mqZcOXhfFf3Po6whFv8o>
   - <https://www.udemy.com/course/logica-de-programacao-para-todos/>

- HTML/CSS:
   - <https://www.youtube.com/watch?v=epDCjksKMok&list=PLHz_AreHm4dlAnJ_jJtV29RFxnPHDuk9o>
   - <https://www.youtube.com/watch?v=YoDJsSII2Ug&list=PLwXQLZ3FdTVGKl3iPEyEWpFoYkMUxWW5O>
   - <https://github.com/gustavoguanabara/html-css>
   - <https://jornadadodev.com.br/cursos/aprenda-html-em-1-hora>
   - <https://jornadadodev.com.br/cursos/curso-completo-de-html5>
   - <https://alunos.b7web.com.br/curso/html5-e-css3>
   - <https://www.w3schools.com/html/>
   - <https://developer.mozilla.org/pt-BR/docs/Aprender/HTML>

- Javascript:
   - <https://alunos.b7web.com.br/curso/javascript>
   - <https://github.com/gustavoguanabara/javascript>
   - <https://www.youtube.com/watch?v=cprMYC8PCVY&list=PL85ITvJ7FLohGTWaE_p0J6B-TLmQbN4ka&pbjreload=101>
   - <https://www.youtube.com/playlist?list=PLHz_AreHm4dlsK3Nr9GVvXCbpQyHQl1o1&pbjreload=101>
   - <https://skylab.rocketseat.com.br/>
   - <https://developer.mozilla.org/pt-BR/docs/Aprender/JavaScript>
   - <https://jornadadodev.com.br/cursos/curso-completo-de-javascript>
   - <https://www.youtube.com/watch?v=ipHuSfOYhwA&list=PLInBAd9OZCzxl38aAYdyoMHVg0xCgxrRx>
   - <https://www.w3schools.com/js/>

- PHP:
   - <https://www.youtube.com/watch?v=F7KzJ7e6EAc&list=PLHz_AreHm4dm4beCCCmW4xwpmLf6EHY9k>
   - <https://www.youtube.com/watch?v=XwpsxPmQN2E&list=PLwXQLZ3FdTVEITn849NlfI9BGY-hk1wkq>
   - <https://www.youtube.com/watch?v=KlIL63MeyMY&list=PLHz_AreHm4dmGuLII3tsvryMMD7VgcT7x>
   - <https://www.php.net>
   - <https://www.devmedia.com.br/cursos/php>
   - <https://jornadadodev.com.br/cursos/curso-de-php-para-inciantes>
   - <https://jornadadodev.com.br/cursos/curso-completo-de-php>
   - <https://www.w3schools.com/php/>

- MySQL:
   - <https://www.youtube.com/watch?v=Ofktsne-utM&list=PLHz_AreHm4dkBs-795Dsgvau_ekxg8g1r>
   - <https://www.youtube.com/watch?v=fmerTu7dWk8&list=PLucm8g_ezqNrWAQH2B_0AnrFY5dJcgOLR>
   - <https://jornadadodev.com.br/cursos/curso-completo-de-mysql>
   - <https://www.w3schools.com/sql/default.asp>
   - <https://www.devmedia.com.br/curso/curso-completo-de-mysql/281>

OBS: I don't know if all this courses are free and all are in PT-BR
> OBS: Eu não sei se todos esses cursos são gratuitos e todos estão em PT-BR