# CT-007 — Visualizar detalhes de um produto

## Identificação

- **ID:** CT-007
- **Sistema:** SauceDemo
- **Funcionalidade:** Catálogo de produtos — visualização dos detalhes de um produto
- **Tipo de teste:** Funcional — cenário positivo
- **Data da execução:** 12/11/2026

## Objetivo

Verificar se, ao clicar em um produto no catálogo, o sistema abre a página de detalhes correspondente e apresenta as informações do produto.

## Pré-condições

- O usuário deve estar autenticado no SauceDemo.
- O usuário deve estar na página de listagem de produtos.

## Dados de teste

- **Produto:** Sauce Labs Fleece Jacket

## Passos para execução

1. Na listagem de produtos, clicar no nome **Sauce Labs Fleece Jacket**.
2. Verificar se a página de detalhes do produto é aberta.
3. Conferir se a página exibe o nome, a imagem, a descrição e o preço do produto selecionado.

## Resultado esperado

A página de detalhes do **Sauce Labs Fleece Jacket** deve ser exibida, apresentando o nome, a imagem, a descrição e o preço correspondentes ao produto selecionado.

## Resultado obtido

A página de detalhes do **Sauce Labs Fleece Jacket** foi aberta. Foram exibidos a imagem da jaqueta, o nome do produto, sua descrição, o preço e o botão **Add to cart**.

## Status

**PASSED** ✅

## Justificativa

O sistema abriu corretamente a página do produto selecionado e exibiu as informações previstas no resultado esperado.

## Evidência

Print da página de detalhes capturado durante a execução. **Pendente de salvar e anexar ao repositório.**

> Depois de salvar a imagem na mesma pasta deste arquivo, com o nome `CT-007-evidencia.png`, a referência abaixo a exibirá no GitHub.

![Evidência do CT-007 — Detalhes do Sauce Labs Fleece Jacket](CT-007-evidencia.png)
