# 🐞 QA Manual — SauceDemo

## Sobre o projeto

Este repositório apresenta meus estudos e práticas em Quality Assurance (QA), com foco em testes manuais de software.

O projeto foi desenvolvido durante minha formação em QA, utilizando a aplicação SauceDemo para praticar técnicas de teste, documentação de cenários, análise de resultados e elaboração de relatórios de defeitos.

## Aplicação utilizada

**Nome:** SauceDemo

**Site:** https://www.saucedemo.com/

**Tipo:** Aplicação web de comércio eletrônico utilizada para prática de testes de software.

## Objetivo do projeto

Aplicar conhecimentos de QA Manual por meio de:

- Elaboração de casos de teste.
- Execução de testes funcionais.
- Validação de resultados esperados e obtidos.
- Identificação de comportamentos inesperados.
- Documentação de testes.
- Registro de evidências de execução.
- Elaboração de relatórios de defeitos.

## Casos de teste realizados

### CT-001 — Login com nome de usuário vazio

**Tipo:** Teste negativo.

**Objetivo:** Verificar se o sistema impede o login quando o campo de usuário não é preenchido.

**Resultado esperado:** O sistema deve impedir o acesso e apresentar uma mensagem de obrigatoriedade.

**Resultado observado:** A aplicação apresentou a mensagem:

"Epic sadface: Username is required"

**Status registrado:** PASSED.

### CT-002 — Login com senha incorreta

**Tipo:** Teste negativo.

**Objetivo:** Verificar se o sistema impede o acesso quando são utilizadas credenciais inválidas.

**Resultado esperado:** O sistema deve impedir o login e informar que as credenciais não correspondem.

**Resultado observado:** A aplicação apresentou a mensagem:

"Epic sadface: Username and password do not match any user in this service"

**Status registrado:** PASSED.

### CT-003 — Login com credenciais válidas

**Tipo:** Teste positivo.

**Objetivo:** Verificar se o usuário consegue acessar a aplicação utilizando credenciais válidas.

**Resultado esperado:** O sistema deve realizar a autenticação e redirecionar o usuário para a página de produtos.

**Resultado observado:** O login foi realizado e o usuário foi redirecionado para a página de produtos.

**Status registrado:** PASSED.

## Relatório de bug simulado

Durante os estudos, também foi elaborado um exercício de documentação de defeitos.

**Cenário:** Produto adicionado não aparece no carrinho de compras.

**Produto:** Sauce Labs Backpack.

**Resultado esperado:** O produto adicionado deve aparecer no carrinho.

**Resultado descrito na simulação:** O produto não aparece no carrinho de compras.

**Observação importante:** Este relatório foi desenvolvido como exercício didático de documentação de bugs. Não representa um defeito real comprovado na aplicação SauceDemo.

## Testes de Regressão

Este projeto também contempla o desenvolvimento de uma suíte de testes de regressão para a aplicação SauceDemo.

O objetivo é verificar se funcionalidades essenciais continuam funcionando corretamente após alterações no sistema.

Funcionalidades previstas para os testes:

- Autenticação de usuários.
- Catálogo de produtos.
- Carrinho de compras.
- Finalização de compras (checkout).

Os casos de teste, resultados e evidências serão documentados conforme sua execução.## Evidências e documentação

Os casos de teste serão organizados em documentos técnicos, acompanhados das evidências de execução disponíveis.

As próximas etapas incluem:

- Revisão e padronização dos casos de teste.
- Documentação do ambiente de execução.
- Organização das evidências reais.
- Registro dos resultados de execução.
- Documentação do relatório de bug simulado.

## 🐞 Competências em Desenvolvimento

- 🔍 Quality Assurance (QA Manual).
- 🧪 Planejamento e elaboração de casos de teste.
- ✅ Execução de testes funcionais.
- 🔐 Testes positivos e negativos de autenticação.
- 📋 Análise de resultados esperados e obtidos.
- 🐛 Elaboração de relatórios de defeitos (prática simulada).
- 📸 Registro e organização de evidências de testes.
- 🔄 Planejamento e desenvolvimento de suítes de testes de regressão.
- 🛒 Testes de funcionalidades de comércio eletrônico.
- 📂 Documentação técnica e organização de projetos no GitHub.


## Autora

**Joseane Oliveira**

Profissional em formação na área de Quality Assurance (QA), com foco em testes manuais, testes funcionais e testes de APIs REST.

Projeto integrante do meu portfólio de QA.
