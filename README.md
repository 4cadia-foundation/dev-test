# O trabalho por aqui na 4CADIA Factory

Que tal fazer parte de um time com atitude? Participar de uma das maiores disrupções no mercado? Ter a oportunidade de trabalhar com tecnologias e conceitos inovadores, como:

* Práticas ágeis
* Blockchain
* Cloud (AWS, IBM, Google Cloud e afins)
* Data Science
* Escalabilidade, CI e CD
* Micro services e aplicações distribuídas
* Git utilizando Gitflow
* Angular/React/Vue
* NodeJS/NestJS/Express
* Bootstrap/Material Design
* TDD e BDD

# Tecnologias/Padrões

Caso precise escolher, sugerimos utilizar as seguintes tecnologias :

* Linguagem de programação Typescript (preferencialmente) ou Javascript
* Qualquer Framework de estilo 
* Angular 2+ (preferencialmente), Vue.js, React ou Deno
* Flux (Redux, Vuex, etc)
* NodeJS, NestJS e/ou Express
* Testes (Que achar necessário)
* MongoDB, Postgre, CassandraDB, Redis, ou qualquer outra tecnologia NoSQL similar (se necessário)
* Qualquer tecnologia ou padrão complementar as citadas anteriormente são permitidas com as devidas justificativas no README.

Caso tenha familiaridade com outras tecnologias e queira utilizar no lugar de alguma dessas, favor justificar no README juntamente com o motivo e prós e contras.
Temos preferência pelas linguagens (em ordem decrescente de utilização):

* C# e/ou .net
* Go
* Python
* C e/ou C++
* Rust
* Java
* Ruby
* PHP

# A Prova

Você será avaliado pela qualidade do código, pela modularidade, pela legibilidade, pela criatividade e pela quantidade de funcionalidades básicas e extra.
Não se preocupe em cumprir todo o escopo, caso não tenha disponibilidade/habilidade no momento do teste. 
**Importante**: Se preocupe mais em **cumprir bem** e **documentar bem** tudo que se propor a fazer, e deixar bem claro aquilo que escolheu deliberadamente não desenvolver.

## Prazo de entrega

Prazo 1 semana.

## Tarefas

### Crie uma Single Page para um Open Banking (Você cria o layout e nome, os textos pode utilizar Lorem Ipsum). 

O layout e por sua conta, seja criativo.
Qualquer funcionalidade extra é bem vinda para agregar na solução básica proposta.

Vincule na single page a aplicação solicitada abaixo, redirecionando para Login.

### Crie uma API onde terá os seguintes metodos:

* Register
* Login
* Extrato
* Saldos

### Desenvolva uma aplicação frontend para vinculo das APIs, deve conter, Registro, Login, Dashboard(com saldos) e Extrato de movimentos.

O layout e por sua conta, seja criativo.
Qualquer funcionalidade extra é bem vinda para agregar na solução básica proposta.

### Crie o banco de dados de sua escolha para administrar as informações.

Utilize a melhor arquitetura de dados e tecnologia de banco de dados que achar melhor.
Qualquer implementação é válida, desde que seja justificada. Exemplos: Guardar os dados num json para utilizar no frontend mockado :heavy_check_mark:; Guardar os dados em formato de documentos no google firebase :heavy_check_mark:; Guardar os dados dentro de um banco SQL ou NoSQL que sobe num container junto com o backend :heavy_check_mark:.

### Documentação e arquitetura

No arquivo README do projeto explique o funcionamento e a solução adotada na sua implementação do desafio.
É permitido utilizar templates, bibliotecas, e componentes prontos de outros projetos, porém precisam estar **explicitamente** descritos no README.

**Importante:** Favor destacar no README os pontos positivos nos quais você deseja ser avaliado, e evidenciar quais as partes você gostaria de excluir da avaliação. Isso permite que você complete o teste mais rapidamente se desejar, dando atenção somente a algumas àreas específicas, sem grandes prejuízos à sua avalização de qualidade do código.

### Cobertura de testes unitários

Utilize qualquer ferramenta que achar melhor para realização dos testes unitários.
Faça a cobertura de testes que achar necessário, e justifique no README a abordagem utilizada.
Caso queira demonstar domínio na metodologia de TDD, faça commits separados para cada uma das fases para cada feature implementada: elaboração dos testes -> codificação -> refação.

## Avaliação

Os principais critérios de avaliação são:

* Usabilidade
* Raciocínio lógico na construção da solução
* Qualidade de código
* Documentação do projeto (readme)
* Performance

Serão avaliados também os critérios de:

* Criatividade
* Documentação de código
* Responsividade
* Acessibilidade
* Apresentação visual
* Cobertura de testes

## Sugestões

* Documentar **antes** de desenvolver, sempre que possível
* Fazer commits com frequência, com boa descrição do que foi feito
* Utilizar o [Lighthouse](https://developers.google.com/web/tools/lighthouse) (ou similar) para medir a qualidade do frontend da aplicação
* Utilizar as *badges* no readme ([sugestão](https://github.com/dwyl/repo-badges)) para indicar a cobertura de testes, status de build, vulnerabilidades e afins
* Utilizar o [Swagger](https://swagger.io/) ou similar para facilitar os testes e documentação das APIs (se necessário)
* Utilizar o Inglês como linguagem padrão para o código e documentação
* utilizar o [SonarQube](https://www.sonarqube.org/) (ou similar) para medir a qualidade do código
