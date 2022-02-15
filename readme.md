# Configurações iniciais do Laravel

### Iniciando servidor Laravel

```php
php artisan serve
```

### Artisan console help

```php
//Mostra informações especificas do comando informado.
php artisan help <make:controller>
```

### Criando um controller

```php
php artisan make:controller <ExemploController>

//Com métodos básicos
php artisan make:controller <ExemploController> --resource
```

### Criando um model

```php
//Criar modelo no singular
php artisan make:model <Exemplo>
```

```php
//Criar modelo no sigular + migration no plural
php artisan make:model <Exemplo> -m
```

### Criando uma migration

```php
// Criar migration no plural
php artisan make:migration <create_exemplos_table>
```

```php
//Informa ao Laravel que esta sendo criado uma tabela
php artisan make:migration <create_exemplos_table> --create=exemplos
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

### Criando uma classe Seeder

```php
php artisan make:seed <UsersTableSeeder>
```

### Iserindo no banco de dados com Seeder

```php
// Todas as Seeds
php artisan db:seed
```

```php
php artisan db:seed --class=UsersTableSeeder
```

### Limpar views compiladas do cache

```php
php artisan view:clear
```
