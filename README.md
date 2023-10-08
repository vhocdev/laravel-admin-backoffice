<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

## How to install

# Clone este repositório
$ git clone <https://github.com/vhocdev/laravel-admin-backoffice>

# Altere o .env (.env.example) com as credenciais de seu banco
DB_CONNECTION=mysql <br />
DB_HOST=127.0.0.1 <br />
DB_PORT=3306 <br />
DB_DATABASE=laravel <br />
DB_USERNAME=root <br />
DB_PASSWORD=

# Acesse a pasta do projeto no terminal/cmd e Instale as dependências Composer
$ composer install

# Execute os comandos para instalar depêndencias da lib <https://laravel-admin.org/> 
$ php artisan vendor:publish --provider="Encore\Admin\AdminServiceProvider" <br />
$ php artisan admin:install

# Execute a aplicação
$ php artisan serve

Abra http://localhost/admin/ no navegador e use admin no nome de usuário e senha

<img src="https://i.imgur.com/xTWU1ys.png" alt="Laravel Admin">
