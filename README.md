Projeto desenvolvido durante o curso de Laravel na Udemy para solidificar os conhecimentos na framework.

📚 Sobre o Projeto
O mathX é uma aplicação web construída com Laravel, com o intuito de praticar e reforçar os conceitos aprendidos durante o curso. Ele serve como base para o desenvolvimento de aplicações mais complexas utilizando o framework Laravel.

🚀 Tecnologias Utilizadas
Laravel

PHP

Composer

MySQL

Blade Templating Engine
repositorio.utfpr.edu.br
github.com

⚙️ Instalação
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/junioralbino/mathX.git
cd mathX
Instale as dependências do PHP:

bash
Copiar
Editar
composer install
Copie o arquivo de exemplo de ambiente e configure as variáveis de ambiente:

bash
Copiar
Editar
cp .env.example .env
php artisan key:generate
Configure o banco de dados no arquivo .env com suas credenciais.

Execute as migrações para criar as tabelas no banco de dados:

bash
Copiar
Editar
php artisan migrate
Inicie o servidor de desenvolvimento:

bash
Copiar
Editar
php artisan serve
Acesse a aplicação em http://localhost:8000 no seu navegador.

📂 Estrutura do Projeto
O projeto segue a estrutura padrão do Laravel, com diretórios para controllers, models, views, rotas, entre outros.

🤝 Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

📄 Licença
Este projeto está sob a licença MIT.
github.com
