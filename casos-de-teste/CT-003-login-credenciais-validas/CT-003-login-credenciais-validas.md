# CT-003 — Login com credenciais válidas

## Identificação
- **ID:** CT-003
- **Funcionalidade:** Login
- **Sistema:** SauceDemo
- **Tipo de teste:** Funcional
- **Status registrado:** PASSED

## Objetivo
Verificar se o sistema permite a autenticação quando são informadas credenciais válidas.

## Pré-condições
- O sistema SauceDemo deve estar acessível.
- O usuário deve estar na página de login.
- Não deve existir uma sessão autenticada.

## Dados de teste
- **Usuário:** conforme credenciais válidas utilizadas na execução original.
- **Senha:** conforme credenciais válidas utilizadas na execução original.

## Passos para execução
1. Acessar a página de login do SauceDemo.
2. Informar credenciais válidas.
3. Clicar no botão **Login**.
4. Observar a página para a qual o sistema direciona o usuário.

## Resultado esperado
O sistema deve autenticar o usuário e direcioná-lo à página de produtos.

## Resultado obtido
O login foi realizado e o usuário foi redirecionado para a página de produtos do site.

## Status
**PASSED**

## Justificativa
O teste foi considerado aprovado porque o comportamento observado correspondeu ao resultado esperado: o acesso foi permitido e a página de produtos foi exibida.

## Evidência da execução
Adicionar aqui a captura de tela real da execução.

<!-- Exemplo após adicionar o PNG à mesma pasta:
![Evidência do CT-003](./CT-003-login-credenciais-validas.png)
-->
