# review

Revisão do código cujo repositório se encontra em:https://github.com/nuk/codemood

## 💡 Opniões:

1 - Após seguir o <b>Getting</b> Started da documentação : [documentação](https://guides.rubyonrails.org/getting_started.html), 
percebi que a estrutura é padrão que o rails cria. No entanto, como não havia package.json, creio que ele não rode.

```package.json
{
  "name": "blog",
  "private": true,
  "dependencies": {
    "@rails/ujs": "^6.0.0",
    "turbolinks": "^5.2.0",
    "@rails/activestorage": "^6.0.0",
    "@rails/actioncable": "^6.0.0"
  },
  "version": "0.1.0"
}

```

2 - No READ ME o autor fala que é um projeto em desenvolvimento também.

3- banco de dados parece que é o <b>Sqlite</b>
```

3 -  Não possui generators:

Rails:
  - application_record
  - assets
  - benchmark
  - channel
  - controller
  - generator
  - helper
  - integration_test
  - jbuilder
  - job
  - mailbox
  - mailer
  - migration
  - model
  - resource
  - scaffold
  - scaffold_controller
  - system_test
  - task
```
Percebi, ao seguir um tutorial paralelo:

Rodei:

```
rails g scaffold Alien name:string age:integer

```

Este comando(rails g scaffold...) gera os arquivos seguindo a arquitetura de aplicativos Rails, ou seja, ele cria um arquivo de modelo, controlador, helper e as views necessárias.
E no código oferecido não tem eles.

Criando banco de dados:
```
rake db:migrate

```
