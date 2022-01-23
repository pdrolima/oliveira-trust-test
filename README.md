## Desafio Oliveira Trust

### Tecnologias utilizadas
* PHP 8.0
* Laravel 8
* AlpineJS

---
Aplicação que faz a conversão da nossa moeda nacional para uma moeda estrangeira, aplicando
algumas taxas e regras de negócio.

**Instruções:**

Clone o projeto:

```bash
$ git clone git@github.com:webmasterdro/oliveira-trust-test.git
```

Instale as dependências do projeto:

```bash
$ composer install
$ cp .env.example .env # Configure as credenciais do banco de dados
$ php artisan key:generate
```

Rodando as migrates e testes:

```bash
$ php artisan migrate --seed
$ php artisan test
```

Acessando o projeto ([http://127.0.0.1:8000/](http://127.0.0.1:8000/))

```bash
$ php artisan serve
```
---
**Usuario de teste:**

Email: admin@admin.com

Password: admin
