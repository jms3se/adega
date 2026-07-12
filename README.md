# Adega

Aplicação front-end desenvolvida para facilitar a descoberta de estabelecimentos e produtos a partir da localização informada pelo usuário. O projeto simula um fluxo de compra em que o usuário pesquisa um local, escolhe um fornecedor e navega por produtos disponíveis em uma experiência organizada e visualmente consistente.

## Objetivo do projeto

A ideia central do projeto é demonstrar a construção de uma interface moderna e modular para um cenário de e-commerce/marketplace local, com foco em:

- busca por localização;
- listagem de fornecedores próximos;
- navegação para a página de produtos;
- interação com itens de catálogo;
- organização de estado e dados em uma arquitetura React + Redux.

Esse projeto é interessante como exemplo de portfólio porque reúne conceitos importantes de desenvolvimento frontend, como componentização, gerenciamento de estado, consumo de APIs GraphQL e estruturação de uma aplicação com múltiplas páginas.

## O que a aplicação faz

A experiência do usuário é dividida em três etapas principais:

1. Pesquisa de localização
   - O usuário informa um local para encontrar estabelecimentos próximos.

2. Seleção de fornecedor
   - A aplicação exibe uma lista de lojas/fornecedores compatíveis com a região pesquisada.

3. Visualização de produtos
   - Após selecionar um fornecedor, o usuário acessa uma página com produtos e pode controlar a quantidade desejada de cada item.

## Funcionalidades principais

- Interface com navegação entre páginas utilizando React Router.
- Gerenciamento de estado global com Redux.
- Consumo de dados via Apollo Client e GraphQL.
- Componentização com React e Styled Components.
- Estrutura organizada em camadas de componentes, containers e páginas.
- Estilização baseada em um design system próprio.

## Tecnologias utilizadas

- React
- React Router
- Redux
- Apollo Client / GraphQL
- Styled Components
- Webpack
- Babel
- Jest
- ESLint

## Arquitetura do projeto

A estrutura do projeto foi organizada para separar responsabilidades e facilitar a manutenção:

- src/components: componentes reutilizáveis e visuais da interface.
- src/containers: conexão entre componentes e estado global.
- src/config/api: integração com APIs e consultas GraphQL.
- src/redux-flow: actions, reducers, constants e configuração do store.
- src/designSystem: tokens de design, cores, tipografia e estilos globais.

## Estrutura de pastas

- src/App.jsx: configuração principal da aplicação e definição das rotas.
- src/components/Pages: páginas da interface.
- src/components/Organisms: blocos maiores de interface.
- src/components/Atoms e Molecules: componentes menores e reutilizáveis.
- src/redux-flow: fluxo completo de estado da aplicação.
- webpack.config.js: configuração de build da aplicação.
- package.json: scripts, dependências e configuração do projeto.

## Como executar localmente

Pré-requisitos:

- Node.js instalado
- npm ou yarn disponível

Passos:

```bash
npm install
npm start
```

O projeto pode ser executado em modo de desenvolvimento e a aplicação estará disponível no ambiente local configurado pelo Webpack Dev Server.

## Testes

O projeto já conta com estrutura de testes utilizando Jest, com suporte a testes de componentes e fluxo de estado.

## Considerações

Este repositório representa uma implementação frontend com foco em experiência de usuário, organização de código e uso de ferramentas modernas do ecossistema React. Ele pode ser utilizado como referência para demonstrar conhecimentos em arquitetura de interfaces, consumo de APIs e estruturação de aplicações escaláveis.
