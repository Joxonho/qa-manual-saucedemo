# CT-001 — Login com nome de usuário vazio

**Objetivo:** Verificar se o sistema impede o login quando o nome de usuário está vazio.

**Pré-condição:** Estar na página de login do SauceDemo, sem estar autenticado.

## Passos para execução

1. Acessar a página de login do SauceDemo.
2. Deixar o campo Username vazio.
3. Preencher o campo Password com a senha de demonstração `secret_sauce`.
4. Clicar no botão Login.

**Resultado esperado:** O sistema deve impedir o login e apresentar uma mensagem informando que o nome de usuário é obrigatório.
**Resultado observado:** Epic Sadface: Username is required


**Status da execução:** PASSED

**Evidência:** ![Evidência da execução](./CT-001%20Login%20Usuario%20Vazio%20Passed.png)
