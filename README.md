# Controller-Fin

App desenvolvido segundo o que foi solicitado no enunciado da prova.

Descrição das questões: Em uma universidade foi solicitado o desenvolvimento de um aplicativo web para controlar o financiamento de projetos. Cada projeto está descrito como se segue: • nome; • área (tecnológica, humanas, médica); • prazo (em dias); • orçamento (de R$ 5.000,00 a R$ 100.000,00) Desenvolva um aplicativo web:

Página principal com dois menus: “Dashboard” e “Projetos”
No menu “Projetos”, adicionar um formulário para inserir projeto
No menu “Dashboard”, mostrar um painel com as seguintes informações dos projetos:
A porcentagem do orçamento total destinada a cada área
Os 5 projetos mais caros ordenados pelo valor do orçamento
Orçamento total
Para inserir um projeto utilizar a api localizada em https://projeto-prova.herokuapp.com/projeto. Enviar um POST para https://projeto-prova.herokuapp.com/projeto com o conteúdo:

{ "nome": "projeto xpto", "area": "MEDICA", "prazo": 50, "orcamento": 16000.00 }

Para ler os dados projeto: GET: https://projeto-prova.herokuapp.com/projeto

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
