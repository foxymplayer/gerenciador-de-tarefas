# Indice

[Tarefa Alternativa: Construção de Gerenciador de Tarefas](#tarefa-alternativa-constru%C3%A7%C3%A3o-de-gerenciador-de-tarefas)<br>
[Créditos:](#cr%C3%A9ditos)<br>
[LinkedIn: ](#linkedin)<br>


# Tarefa Alternativa: Construção de Gerenciador de Tarefas

Olá!

Como parte da tarefa alternativa proposta, desenvolvi uma aplicação de gerenciador de tarefas seguindo o tutorial do vídeo "Projeto - Gerenciador de Tarefas" disponível no canal Monolito PHP.

Descrição
Neste repositório, você encontrará uma implementação da aplicação de gerenciador de tarefas utilizando HTML5, CSS3 e PHP, conforme demonstrado no vídeo mencionado.

Recursos da Linguagem PHP Documentados
Aqui está uma breve descrição dos recursos da linguagem PHP mencionados no vídeo e utilizados para implementar o gerenciador de tarefas:

* 1 isset: Verifica se uma variável está definida e não é nula.

php:

if (isset($_POST['submit'])) {
    // código aqui
}

* 2 $SESSION: Variável global que armazena dados de sessão do usuário.

php:

session_start();
$_SESSION['username'] = 'exemplo';


* 3 foreach: Estrutura de repetição usada para percorrer arrays.

php:

foreach ($_SESSION['tasks'] as $task) {
    // código aqui
}

* 4 session_start(): Inicia uma nova sessão ou resume uma sessão existente.

php:

session_start();

* 5 array(): Função usada para criar um array.
 
 php:

 $tasks = array();

 * 6$_GET: Array associativo que armazena variáveis passadas para o script via parâmetros de URL.

 php:

 $id = $_GET['id'];

* 7 array_push(): Adiciona um ou mais elementos ao final de um array.

php:

array_push($_SESSION['tasks'], $newTask);

* 8 var_dump(): Exibe informações sobre a variável.

php:

var_dump($_SESSION['tasks']);

* 9 unset(): Remove uma variável especificada.

php:

unset($_SESSION['tasks'][$index]);

## Créditos:

O código foi desenvolvido com base no tutorial do canal Monolito PHP. O autor do vídeo mencionado é o responsável pelo conteúdo apresentado.

## LinkedIn: 

Link do meu [LinkedIn](https://www.linkedin.com/in/gustavo-henrique-ba708b2a0?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) 


