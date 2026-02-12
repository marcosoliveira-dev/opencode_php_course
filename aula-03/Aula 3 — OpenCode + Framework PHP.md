---
date: 2026-02-12 11:20:57
created: 2026-02-12 06:44:17
categories:
- Videos / OpenCode
---

# Aula 3 — OpenCode + Framework PHP 

* * *

## <br>

## Objetivo da aula

Nesta aula, vamos dar continuidade ao desenvolvimento do projeto de barbearia utilizando o framework. Teremos como objetivos:

- Desenvolver o módulo de Agenda.
- Desenvolver o módulo de Caixa.
- Compreender como esses módulos se integram à estrutura já existente do sistema.

* * *

## <br>

## <br>

## 1\. Revisão da estrutura do sistema

Antes de iniciar o desenvolvimento, revisar a organização do projeto.

### Estrutura do projeto

#### Principal

- ==Início==
- ==Dashboard==
- ==Profissionais==
- ==Serviços==
- ==Vínculo Serviços==
- ==Atendimentos==

#### ==Agenda==

- ==Agenda Profissional==
- ==Agendamentos==
- ==Agendar==

#### ==Caixa==

- ==Movimento de Caixa==

* * *

## <br>

## <br>

## 2\. Desenvolvimento do módulo de Agenda

- Criar ou ajustar os controllers relacionados à agenda.
- Criar formulários para definição da agenda do profissional.
- Criar formulários para agendamentos.
- Realizar testes básicos de funcionamento.

<br>

<br>

```
Crie um novo programa/módulo no sistema com um item de menu chamado “Agendar”. Esse módulo seguirá o mesmo princípio do programa “Agendamentos”, porém com um formulário simplificado e fluxo de seleção rápida.

O formulário Agendar deve conter os seguintes campos:

Profissional (seleção obrigatória)

Serviço (seleção obrigatória)

Data (obrigatória, preenchida automaticamente com a data atual ao abrir a tela; permitir edição)

Horário (obrigatório, preenchido a partir da seleção de horários disponíveis)

Nome (obrigatório)

Telefone (obrigatório)

Observação (opcional)

```

<br>

* * *

## <br>

## <br>

## 3\. Desenvolvimento do módulo de Caixa

- Criar tela de movimento de caixa.
- Registrar entradas vinculadas a atendimentos.
- Validar gravação das informações no banco de dados.
- Realizar testes básicos de funcionamento.

* * *

## 4\. Testes do sistema

- Realizar testes de cadastro.
- Realizar testes de agendamento.
- Realizar testes de movimentação de caixa.
- Validar registros no banco de dados.

* * *

## Encerramento

Nesta aula, desenvolvemos os módulos de Agenda e Caixa, avançando na implementação das funcionalidades do sistema e compreendendo como esses módulos se integram à aplicação.

Na próxima aula, continuaremos evoluindo o sistema e iniciaremos a implementação e validação de máscaras no campos de formulários e desenvolveremos o dashboard.

<br>