# HU-001 — Login de usuário

**Tipo:** História de usuário didática  
**Sistema:** SauceDemo  
**Funcionalidade:** Login

## História de usuário

Como usuário cadastrado do SauceDemo,
quero fazer login com minhas credenciais,
para acessar a página de produtos do sistema.

## Critérios de aceitação

### CA-01 — Login com credenciais válidas

**Dado que** o usuário esteja na página de login
e não possua sessão autenticada,

**Quando** informar o nome de usuário `standard_user`
e a senha `secret_sauce` e clicar em **Login**,

**Então** o sistema deverá permitir a autenticação
e direcioná-lo à página de produtos, exibindo a
lista de produtos sem mensagens de erro.

### CA-02 — Impedir login com credenciais inválidas

**Dado que** o usuário esteja na página de login
e não possua sessão autenticada,

**Quando** informar um nome de usuário válido
e uma senha incorreta e clicar em **Login**,

**Então** o sistema deverá impedir a autenticação,
permanecer na página de login e apresentar
uma mensagem de erro.

### CA-03 — Exigir preenchimento do nome de usuário

**Dado que** o usuário esteja na página de login
e o campo **Username** esteja vazio,

**Quando** preencher o campo **Password**
e clicar em **Login**,

**Então** o sistema deverá impedir a autenticação,
permanecer na página de login e apresentar
a mensagem de obrigatoriedade do nome de usuário.

## Observação de QA

Estes requisitos foram elaborados para fins
didáticos, com base nos cenários de testes manuais
do SauceDemo.

Não representam documentação oficial do sistema.

O CT-002 verifica especificamente a combinação
de usuário válido e senha incorreta.

Portanto, ele não comprova sozinho o comportamento
para todos os tipos de credenciais inválidas,
como usuário inexistente ou não cadastrado.

Esse cenário poderá exigir um caso de teste adicional.

## Casos de teste relacionados

- CT-001 — Login com nome de usuário vazio
- CT-002 — Login com usuário válido e senha incorreta
- CT-003 — Login com credenciais válidas
