# Teste para candidatos Superh


> Esse teste é público. Candidatos para o teste devem implementar a aplicação solicitada e fazer um pull request com a solução do mesmo.

## Objetivo do desafio
Criar uma aplicação web que implemente um CRUD de veículos com as seguintes características:

### Carro:
- Montadora (Chevrolet, Ford, Honda, ...)
- Modelo (Monza, Fusion, Maverick, ...)
- Cor (azul, verde, vermelho, ...)
- Kilometragem (0km, 5000km, 12000km, ...)
- Motor (1.0, 1.4, 2.0, ...)


A aplicação é apenas um CRUD sem usuários (não existe autenticação). Deve ser possível:
- Inserir, editar e deletar uma montadora, um modelo ou um veículo
- Pesquisar os veículos disponíveis com a possibilidade de filtrar por quaisquer características ou combinação de características disponíveis. Também deve ser possível filtrar por faixas de valores. Por exemplo:
* Motos da BMW com kilometragem menor que 10000km;
* Carros Chevrolet com motor maior que 1.4

A interface de uso fica a critério do desenvolvedor. A UI/UX da aplicação não será avaliada.

## Requisitos:
- A aplicação deve executar as operações de CRUD através de chamadas AJAX. É um diferencial positivo se a aplicação for uma SPA (single-page application). Outro diferencial bastante positivo é o frontend ser desenvolvido em AngularJS.
- Backend desenvolvido em qualquer linguagem dinâmica. É um diferencial positivo se for desenvolvido em CodeIgniter. É mais positivo ainda se utilizar o framework CakePHP.
- Processo de desenvolvimento versionado via Git em algum repositório público do github.
- Readme que explique como rodar o projeto e como executar quaisquer scripts necessários.
- A aplicação deve possuir um script que popula o banco inicialmente com alguns veículos para demonstração.

## Critérios de avaliação:
- Modelagem do banco de dados. Você tem toda a liberdade de criar quantas tabelas ou campos achar necessários.
- Organização do código: desacoplamento e legibilidade contam.
- Automatização de tarefas.
- Flexibilidade do sistema para adição/remoção de funcionalidades.
- O front só será avaliado segundo o código Javascript. Não se preocupe com o HTML/CSS.

## Como vamos avaliar:
- Vamos subir a aplicação e acessar via localhost:<alguma-porta>. Vamos cadastrar/editar/deletar algumas entidades. Vamos listar os veículos segundo diferentes combinações de filtros. Vamos analisar as chamadas AJAX feitas durante essa utilização.
- Vamos ler o código.

## O que nós gostamos:
- Arquitetura que favorece a escalabilidade do sistema.
- Hierarquia clara entre componentes.
- Gostamos do padrão REST, mas não ficamos limitado a ele.