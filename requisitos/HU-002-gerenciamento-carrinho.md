# HU-002 — Gerenciamento do carrinho de compras

**Tipo:** História de usuário didática  
**Sistema:** SauceDemo  
**Funcionalidade:** Carrinho de compras

## História de usuário

Como usuário autenticado do SauceDemo,
quero adicionar e remover produtos do carrinho de compras,
para gerenciar os itens que pretendo comprar.

## Critérios de aceitação

### CA-01 — Adicionar produto ao carrinho

**Dado que** o usuário esteja autenticado e o carrinho esteja vazio,

**Quando** adicionar o produto Sauce Labs Backpack ao carrinho,

**Então** o produto deverá constar no carrinho com quantidade 1, e o contador deverá indicar 1 item.

### CA-02 — Remover produto do carrinho

**Dado que** o usuário esteja autenticado e possua produtos no carrinho,

**Quando** remover um produto,

**Então** o produto selecionado deverá ser removido, os demais produtos deverão permanecer no carrinho e a quantidade de itens deverá ser atualizada.

## Observação de QA

Estes requisitos foram elaborados para fins didáticos, com base nos cenários de testes manuais do SauceDemo. Não representam documentação oficial do sistema.

O comportamento visual do contador quando o carrinho fica vazio (ocultação ou exibição do número zero) permanece sem definição neste requisito.

## Casos de teste relacionados

- CT-004 — Adicionar produto ao carrinho
- CT-005 — Remover produto do carrinho
- CT-006 — Remover um produto de um carrinho com dois itens
