# CT-005 — Remover produto do carrinho de compras

**Sistema:** SauceDemo  
**Funcionalidade:** Carrinho de compras — remoção de produto  
**História de usuário:** HU-002 — Gerenciamento de produtos no carrinho de compras  
**Critério de aceitação:** CA-02 — Remover produto

## Objetivo
Verificar se o sistema permite remover um produto do carrinho de compras e se o contador do carrinho é atualizado.

## Pré-condições
- O usuário deve estar autenticado no SauceDemo.
- Deve haver pelo menos um produto adicionado ao carrinho de compras.

## Dados de teste
- **Usuário:** `standard_user`
- **Senha:** `secret_sauce`
- **Produto utilizado:** [preencher com o nome do produto realmente utilizado]

## Passos para execução
1. Acessar o SauceDemo.
2. Fazer login com credenciais válidas.
3. Adicionar um produto ao carrinho.
4. Acessar o carrinho de compras.
5. Clicar em **Remove** no produto adicionado.
6. Verificar se o produto deixou de aparecer no carrinho.
7. Verificar se o contador do carrinho foi atualizado.

## Resultado esperado
O produto removido deve deixar de aparecer no carrinho de compras, e o contador do carrinho deve ser atualizado.

## Resultado obtido
[Preencher após conferir o comportamento observado durante a execução.]

## Status
**PENDING — Aguardando registro e validação do resultado obtido.**

## Justificativa
[Registrar com suas palavras por que o resultado observado atende ou não ao resultado esperado.]

## Evidência da execução
![Evidência CT-005 — Remoção de produto do carrinho](./CT-005-remover-produto-carrinho.png)

> **Nota:** Salve a captura de tela com o nome `CT-005-remover-produto-carrinho.png` na mesma pasta deste documento para que a imagem apareça no GitHub. O link só funcionará depois de enviar a imagem.
