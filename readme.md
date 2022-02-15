<p align="center" id="top">
    <img alt="Readme" title="Readme GIF" src="banner.png" />
</p>

<h1 align="center">LARAVEL</h1>

## Configurações iniciais do Laravel

### Iniciando servidor Laravel

```php
php artisan serve
```

### Artisan console help

### Mostra informações especificas do comando informado

```php
php artisan help [make:controller]
```

## Controller

### Criando um controller

```php
php artisan make:controller [ExemploController]
```

### Com métodos básicos

```php
php artisan make:controller [ExemploController] --resource
```

## Model

### Criar modelo no singular

```php
php artisan make:model [Exemplo]
```

### Criar modelo no sigular + migration no plural

```php
php artisan make:model [Exemplo] -m
```

## Migration

### Criar migration no plural

```php
php artisan make:migration [create_exemplos_table]
```

### Informa ao Laravel que esta sendo criado uma tabela

```php
php artisan make:migration [create_exemplos_table] --create=exemplos
```

### Criando uma tabela no banco de dados com migration

```php
php artisan migrate
```

### Resetando banco de dados com migrate

```php
php artisan migrate:reset
```

### Reverter e migrar seeder em um único comando

```php
php artisan migrate:fresh --seed
```

### Reverter step especificos

```php
php artisan migrate:rollback --step=1
```

## Seeder

### Criando uma classe Seeder

```php
php artisan make:seed [UsersTableSeeder]
```

### Iserindo no banco de dados com Seeder

```php
php artisan db:seed
```

```php
php artisan db:seed --class=UsersTableSeeder
```

### Limpar views compiladas do cache

```php
php artisan view:clear
```

## Referências

- Pesquisa

  - [Laravel Docs](https://laravel.com/docs/9.x)

### Wakatime

Tempo gasto no IDE para este repositório, rastreado automaticamente com [wakatime](https://wakatime.com/) .

[![wakatime](https://wakatime.com/badge/github/JuniorLima22/cli-laravel.svg)](https://wakatime.com/badge/github/JuniorLima22/cli-laravel)

### Autor

> Made with 💙 by JUNIOR LIMA 👋 <a href="https://www.linkedin.com/in/JuniorLima22/" target="_blank">See my LinkedIn</a> • GitHub <a href="https://github.com/JuniorLima22" target="_blank">@JuniorLima22</a>

<p align="center">
<sub><a href="#top" align="center">↑ voltar para o topo ↑</a></sub>
</p>