# 🐞 QA Manual — SauceDemo

![QA Manual](https://img.shields.io/badge/QA-Manual-blue)
![Testes](https://img.shields.io/badge/Testes-Funcionais-success)
![Status](https://img.shields.io/badge/Projeto-Em%20Desenvolvimento-orange)

## 📌 Sobre o projeto

Este repositório reúne estudos e práticas em **Quality Assurance (QA)**, com foco em testes manuais de software.

O projeto utiliza a aplicação SauceDemo como ambiente de testes para desenvolver habilidades de planejamento, elaboração e execução de casos de teste, análise de resultados, documentação de evidências e identificação de comportamentos inesperados.

## 🎯 Objetivos

- Elaborar casos de teste funcionais.
- Aplicar cenários positivos e negativos.
- Validar resultados esperados e obtidos.
- Trabalhar com histórias de usuário e critérios de aceitação.
- Desenvolver rastreabilidade entre requisitos e casos de teste.
- Registrar evidências de execução.
- Praticar a documentação de defeitos.
- Desenvolver uma suíte de testes de regressão.

## 🖥️ Aplicação utilizada

| Informação | Descrição |
|---|---|
| Aplicação | SauceDemo |
| URL | https://www.saucedemo.com/ |
| Tipo | Aplicação web de comércio eletrônico |
| Abordagem | Testes manuais |
| Categoria | Testes funcionais |

## 📂 Estrutura do repositório

```text
qa-manual-saucedemo/
│
├── README.md
│
├── casos-de-teste/
│   ├── CT-001-login-nome-vazio/
│   ├── CT-002-login-credenciais-invalidas/
│   ├── CT-003-login-credenciais-validas/
│   ├── CT-004-adicao-produto-carrinho/
│   ├── CT-005-remover-produto-carrinho/
│   ├── CT-006-remover-um-produto-com-dois-itens/
│   └── CT-007-visualizar-detalhes-do-produto/
│
└── requisitos/
    ├── HU-001-login.md 
    └── HU-002-gerenciamento-carrinho.md
```

## 📋 Casos de teste documentados

| ID | Cenário | Tipo | Status |
|---|---|---|---|
| [CT-001](casos-de-teste/CT-001-login-nome-vazio/CT-001-login-nome-vazio.MD) | Login com usuário vazio | Negativo | PASSED |
| [CT-002](casos-de-teste/CT-002-login-credenciais-invalidas/CT-002-login-credenciais-invalidas.md) | Login com senha incorreta | Negativo | PASSED |
| [CT-003](casos-de-teste/CT-003-login-credenciais-validas/CT-003-login-credenciais-validas.md) | Login com credenciais válidas | Positivo | PASSED |
| [CT-004](casos-de-teste/CT-004-adicao-produto-carrinho/CT-004-adicao-produto-carrinho.md) | Adicionar produto ao carrinho | Positivo | PASSED |
| [CT-005](casos-de-teste/CT-005-remover-produto-carrinho/CT-005-remover-produto-carrinho.md) | Remover o único produto do carrinho | Positivo | PASSED |
| [CT-006](casos-de-teste/CT-006-remover-um-produto-com-dois-itens/CT-006-remover-um-produto-com-dois-itens.md) | Remover um produto mantendo o outro | Positivo | PASSED |
| [CT-007](casos-de-teste/CT-007-visualizar-detalhes-do-produto/CT-007-visualizar-detalhes-de-um-produto.md) | Visualizar detalhes de um produto | Positivo | PASSED |

**Total: 7 casos de teste documentados.**

Os resultados, passos de execução, dados de teste, justificativas e evidências estão registrados individualmente nos documentos correspondentes.

## 📝 Requisitos e rastreabilidade

O projeto utiliza histórias de usuário e critérios de aceitação para relacionar os requisitos aos cenários de teste.

**HU-002 — Gerenciamento do carrinho de compras**

[Consultar história de usuário e critérios de aceitação](requisitos/HU-002-gerenciamento-carrinho.md)

Critérios documentados:

- **CA-01:** Adicionar produto ao carrinho.
- **CA-02:** Remover produto do carrinho.

Os casos CT-004, CT-005 e CT-006 estão vinculados a esses critérios de aceitação.

## 🐛 Relatório de defeito simulado

Durante os estudos também foi desenvolvido um exercício de documentação de bug:

**Cenário:** Produto adicionado não aparece no carrinho de compras.

**Produto:** Sauce Labs Backpack.

O exercício contempla:
- Título do defeito.
- Passos para reprodução.
- Resultado esperado.
- Resultado obtido.

**Importante:** trata-se de uma simulação didática para praticar a elaboração de relatórios de defeitos, não de um bug real comprovado na aplicação.

## 🔄 Testes de regressão

Está em desenvolvimento uma suíte de testes de regressão para verificar se funcionalidades essenciais continuam operando corretamente após alterações no sistema.

Funcionalidades previstas:

- Autenticação de usuários.
- Catálogo de produtos.
- Gerenciamento do carrinho.
- Finalização de compras (checkout).

## 🧠 Competências em desenvolvimento

- Quality Assurance (QA Manual).
- Planejamento e elaboração de casos de teste.
- Testes funcionais positivos e negativos.
- Análise de resultados esperados e obtidos.
- Histórias de usuário e critérios de aceitação.
- Rastreabilidade de requisitos.
- Registro e organização de evidências.
- Documentação de defeitos.
- Testes de regressão.
- Git e GitHub.

## 👩‍💻 Autora

**Joseane Oliveira**

Projeto pessoal de estudos e desenvolvimento profissional na área de Quality Assurance, com foco em testes manuais e qualidade de software.

---

*Este portfólio está em constante evolução, acompanhando o desenvolvimento das minhas habilidades em QA.*
