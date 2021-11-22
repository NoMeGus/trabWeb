# trabWeb
Tecnologias: para realizar este projeto foi utilizado o SGBD MySQL em sua última versão, 5.1.1, assim como a linguagem de programação PHP em sua versão mais atualizada, 8.0.12. Outra ferramenta usada foi o framework Laravel em sua versão 4.2.9.	Além disso, foi utilizado JavaScript, o Node.js (14.16.1) e também o Composer (2.1.11) que é um gerenciador de pacotes para a linguagem PHP.

Instalação: para que o programa possa ser executado com sucesso é necessário baixar o código da pasta compactada, a qual pode ser extraída e usada em qualquer IDE de programação para ser usada. Para acessar o projeto deve-se: abrir o Prompt de Comando, abrir a pasta trab, criada após o clone do repositório, deve-se criar, também, um banco de dados no PhpMyAdmin (acessado com o uso do XAMPP e aberto as portas do Apache e do MySql, e acessado no navegador pelo link: http://localhost:8080/phpmyadmin) com o nome “projeto_db” usuário root e sem senha, voltar a linha de comando e rodar os seguintes comandos:
composer update
php artisan migrate:fresh
php artisan serve
	
A aplicação atende aos seguintes requisitos de usuário:
- Definir tarefas.
- Agrupar tarefas em listas.
- Modificar tarefas e listas.
- Visualizar tarefas e listas.
- Publicar listas.
- Buscar por tarefas e listas.
- Compartilhamento/criação de listas públicas.
