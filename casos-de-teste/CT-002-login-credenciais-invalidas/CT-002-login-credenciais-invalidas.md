# CT-002 — Login com usuário válido e senha incorreta

## Identificação

- **ID:** CT-002
- **Funcionalidade:** Login
- **Sistema:** SauceDemo
- **Tipo de teste:** Funcional — cenário negativo
- - **História de usuário:** [HU-001 — Login de usuário](../../requisitos/HU-001-login.md)
- **Critério de aceitação:** [CA-02 — Impedir login com credenciais inválidas](../../requisitos/HU-001-login.md#ca-02--impedir-login-com-credenciais-inválidas)

## Objetivo

Verificar se o sistema impede a autenticação quando são informados um nome de usuário válido e uma senha incorreta.

## Pré-condições

- O sistema SauceDemo deve estar acessível.
- O usuário deve estar na página de login.
- Não deve existir uma sessão autenticada.

## Dados de teste

- **Username:** `standard_user`
- **Password:** `12345` (senha incorreta)

## Passos para execução

1. Acessar a página de login do SauceDemo.
2. Preencher o campo Username com `standard_user`.
3. Preencher o campo Password com `12345`.
4. Clicar no botão **Login**.
5. Verificar se o sistema impede o acesso e apresenta a mensagem de erro.

## Resultado esperado

O sistema deve impedir a autenticação, manter o usuário na página de login e apresentar a mensagem:

`Epic sadface: Username and password do not match any user in this service`

## Resultado obtido

O sistema impediu o acesso e apresentou a mensagem:

`Epic sadface: Username and password do not match any user in this service`

## Status

**PASSED**

## Justificativa

O teste foi considerado aprovado porque o sistema impediu a autenticação com a senha incorreta e apresentou a mensagem de erro correspondente, conforme o resultado esperado.

## Evidência da execução

![Evidência CT-002 — Login com credenciais inválidas](./CT-002credenciais-invalidas.png)
