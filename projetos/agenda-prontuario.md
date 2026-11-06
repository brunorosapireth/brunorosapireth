# Agenda e prontuário integrados ao atendimento

**Segmento:** Saúde

Sistema sob medida com agenda, permissões por função e integração com agentes de IA.

## O problema

O sistema anterior limitava a integração com o atendente. A equipe e o agente precisavam consultar e atualizar a mesma agenda, com regras de acesso próprias para o trabalho clínico e administrativo.

## O que construí

- Calendário com janelas de atendimento e pré-reservas com validade.
- Prontuário com separação entre acesso clínico e administrativo.
- Retificação de registros assinados, preservando autoria e histórico.
- API com permissões por escopo, proteção contra gravações duplicadas e modo de simulação.

## Decisão técnica

O controle de conflito de horários fica no banco de dados. A integração nasce das operações que o atendente precisa executar, mantendo a mesma regra para a tela e para a API.

## Fluxo resumido

Equipe ou agente → API com permissões → regras de agenda → banco de dados.

## Na operação

Agenda, registro clínico e atendimento passam a trabalhar juntos, com acesso separado por função.

## Ferramentas usadas

Next.js, TypeScript, PostgreSQL e Docker.

[Ver apresentação e telas no portfólio](https://brunopireth.com.br/cases/agenda-prontuario)

---

Este estudo apresenta o projeto por segmento. Código-fonte, dados e configurações da operação permanecem privados.

[Todos os projetos](README.md) · [Perfil](../README.md)
