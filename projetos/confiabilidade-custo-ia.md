# Controle de custo e confiabilidade de agentes

**Segmento:** Infraestrutura de IA

Limites de chamadas, registro de uso e validações antes da publicação.

## O problema

Um agente pode repetir chamadas e aumentar o gasto quando uma configuração falha. Um alerta posterior não interrompe esse comportamento; a operação precisava de limites aplicados durante a execução.

## O que construí

- Intermediação das chamadas para registrar uso e aplicar limites.
- Reaproveitamento de contexto e escolha de modelo conforme a tarefa.
- Interrupção de chamadas quando o padrão ultrapassa os limites configurados.
- Configuração versionada, ensaio de publicação e monitoramento das execuções.

## Decisão técnica

O limite atua no caminho da chamada. Quando ele é atingido, a execução é interrompida e a equipe recebe o motivo, em vez de depender apenas de um aviso depois do consumo.

## Fluxo resumido

Automação → controle de uso e limites → modelo → registro e monitoramento.

## Na operação

A operação ganha limites de consumo e um caminho de conferência para mudanças no agente.

## Ferramentas usadas

Node.js, Claude, n8n, Docker, GitHub e VPS Linux.

[Ver apresentação e telas no portfólio](https://brunopireth.com.br/cases/confiabilidade-custo-ia)

---

Este estudo apresenta o projeto por segmento. Código-fonte, dados e configurações da operação permanecem privados.

[Todos os projetos](README.md) · [Perfil](../README.md)
