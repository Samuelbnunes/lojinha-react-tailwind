# Catálogo de Produtos com Carrinho - React + Tailwind

Este projeto é uma aplicação web desenvolvida em React e estilizada com Tailwind CSS, que simula um catálogo de produtos com funcionalidade de carrinho de compras. O objetivo é demonstrar como consumir uma API de produtos, exibir os itens em um layout moderno e permitir ao usuário adicionar produtos ao carrinho, visualizando-os em tempo real através de um modal.

## Funcionalidades

- Listagem de produtos consumidos de uma API externa
- Visualização de detalhes básicos dos produtos (imagem, nome, preço)
- Adição de produtos ao carrinho de compras
- Exibição do número de itens no carrinho no cabeçalho
- Modal para visualizar os produtos adicionados ao carrinho
- Estilização responsiva utilizando Tailwind CSS

## Começando

Para rodar este projeto localmente:

```bash
npm install
npm run dev
```

## EstruturaAdd commentMore actions

- O componente `Header` exibe o nome da loja e o número de produtos no carrinho.
- O componente `ProductCatalog` lista os produtos e permite adicioná-los ao carrinho.
- O contexto `CartContext` gerencia o estado global do carrinho.