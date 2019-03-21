# Instruções do modulo 4 de nodejs

Essas são instruções de importações para o modulo 4 de node

### Instalando adonis

```
npm install -g @adonisjs/cli
```

### Criar a api

```
adonis new -h
adonis new (nome da api) --api-only
```

### Iniciar o servidor

```
adonis serve --dev
```

### Instalando o eslint

```
npm install -D eslint
npx eslint --init
```

### Iniciar o banco de dados

```
adonis migration:run
```

### Criação do controller

```
adonis make:controller User
```

### Listar todas as rotas

```
adonis route:list
```

### Rollback nas migrations

```
adonis migration:rollback
```

### Instalando modulo de e-mail

```
1 - adonis install @adonisjs/mail
2 - @adonisjs/mail/providers/MailProvider ( Adicionar nos providers)

MAIL_HOST=smtp.mailtrap.io
MAIL_PORT=2525
MAIL_USERNAME=2777e70a027947
MAIL_PASSWORD=6146d04474914c
```
