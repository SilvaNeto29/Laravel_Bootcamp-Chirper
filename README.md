
# Message Board | Quadro de mensagens | Laravel

  Olá! Este é um projeto em Laravel onde vário usuários podem conversar entre si por meio de 'blocos de mensagens', como um tweet ou uma conversa em um grupo do WhatsApp ou Telegram.

  Todo o front do projeto foi baixado do https://bootcamp.laravel.com/ e a linguagem ultilizada para retirar a estaticidade do sistema foi a Blade, do próprio Laravel.


<a href='https://github.com/SilvaNeto29/Message-Board---Laravel/blob/master/README.en.md'>English</a> 




## Autores
- [@SilvaNeto29](https://www.github.com/SilvaNeto29)


## Funcionalidades

- Autenticação de usuário.
- Disparo de Email.
- Comunicação por meio de mesagens entre multiplos usuários.


## Stack utilizada

**Front-end:** Blade, HTML, TailwindCSS

**Back-end:** PHP 8.2, Laravel 10, MySQL 8


## Instalação

Instale o projeto localmente!

Precisamos ter o Mysql, Composer, PHP e o Vite (Para o TailWind) rodando. Para isso precisamos iniciar o Mysql de alguma forma (para meu ambiente de desenvolvimento usei o XAMPP). Composer é instalado previamente, o PHP e o Vite faremos com comandos no terminal:

```bash
  git clone (Link do projeto no github)
  cd projeto
  php artisan serve (Inicia o servidor imbutido do PHP)
  composer require laravel/breeze --dev 
  php artisan breeze:install blade
  npm run dev (Prepara as dependencias do Front e recarrega a tela em cada alteração)
  php artisan migrate (Prepara o banco de dados para a aplicação)
```
    
