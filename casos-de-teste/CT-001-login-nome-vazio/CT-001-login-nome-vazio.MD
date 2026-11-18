# CT-001 — Login com nome de usuário vazio

## Identificação

- **ID:** CT-001
- **Funcionalidade:** Login
- **Sistema:** SauceDemo
- **Tipo de teste:** Funcional — cenário negativo

## Objetivo

Verificar se o sistema impede o login quando o campo Username está vazio.

## Pré-condições

- O sistema SauceDemo deve estar acessível.
- O usuário deve estar na página de login.
- Não deve existir uma sessão autenticada.

## Dados de teste

- **Username:** (vazio)
- **Password:** `secret_sauce`

## Passos para execução

1. Acessar a página de login do SauceDemo.
2. Deixar o campo Username vazio.
3. Preencher o campo Password com `secret_sauce`.
4. Clicar no botão **Login**.

## Resultado esperado

O sistema deve impedir o login, manter o usuário na página de autenticação e apresentar a mensagem:

`Epic sadface: Username is required`

## Resultado obtido

Após clicar em Login com o campo Username vazio, o sistema permaneceu na página de login e exibiu a mensagem de erro:

`Epic sadface: Username is required`

## Status

**PASSED**

## Justificativa

O teste foi considerado aprovado porque o sistema impediu a autenticação e apresentou a mensagem de obrigatoriedade do campo Username, conforme o resultado esperado.

## Evidência da execução

![Evidência da execução](./CT-001%20Login%20Usuario%20Vazio%20Passed%20%281%29.png)

