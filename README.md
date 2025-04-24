# Form Email

Criando um formulário simples que envia as requisições via e-mail por meio da API FORMSUBMIT

## 1. Criando o formulário

Na criação do formulário usei elementos praticados em aula, tal como a boa prática do HTML Semântico, utilizando forms, names, labels, etc.. isso será importante para implementar a parte funcional no projeto.

## 2. Deixando o formulário funcional

Para adicionar funcionalidade no formulário, usei de uma API, combinada com tags do HTML Semântico para realizar o envio dos dados do formulário para o meu email.

Uma tag muito importante foi o <form>, que possibilitou a criação e funcionalidade de um input do tipo submit, outra parte chave foi utilizar o seguinte comando para configurar o endereço que será enviado as informações do formulário 

```bash
  form action="https://formsubmit.co/gustavo.r.silva33@aluno.senai.br" method="post">
```

Configurando assim tanto o endereço destino como o metodo post.

## Comandos Git para criar e publicar repositório

Iniciando repositório

```bash
  git init
```

Adicionando arquivos no repositório

```bash
  git add .
```

Adiciona o nickname

```bash
  git config --global user.name "meu_nome"
```

Adiciona o email

```bash
  git config --global user.email "meu_email"
```

Commitando arquivos

```bash
  git commit -m "Initial Commit"
```

Conectando o repositório local ao remoto

```bash
  git remote add origin https://github.com/gustavorgsilva/formEmail.git
```

Commitando arquivos

```bash
  git commit -m "Initial Commit"
```

Conectando historicos dos repositórios 
```bash
  git pull origin main --allow-unrelated-histories
```

Commitando arquivos

```bash
  git push origin main
```