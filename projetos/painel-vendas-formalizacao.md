# Painel de vendas e formalização comercial

**Segmento:** Vendas

Metas, funil e formalização conectados aos dados da operação.

## O problema

Os números estavam distribuídos em planilhas com formatos diferentes, e a formalização de uma venda exigia montar um e-mail manualmente. Era preciso conciliar as fontes sem esconder inconsistências.

## O que construí

- Leitura de planilhas e registro de dados inconsistentes para conferência.
- Painel de vendas, metas e histórico por canal.
- Funil integrado ao CRM, com confirmação da atualização antes de avançar.
- Montagem da formalização e proteção contra envio duplicado.

## Decisão técnica

Um dado inconsistente é mostrado para revisão, em vez de corrigido silenciosamente. A automação precisa preservar a rastreabilidade da informação que a equipe usa para decidir.

## Fluxo resumido

Planilha e CRM → validação → painel e funil → formalização.

## Na operação

A equipe acompanha vendas e metas em um painel e reduz etapas manuais na formalização.

## Ferramentas usadas

Next.js, Supabase, n8n, Google Planilhas, Pipedrive e Claude.

[Ver apresentação e telas no portfólio](https://brunopireth.com.br/cases/painel-vendas-formalizacao)

---

Este estudo apresenta o projeto por segmento. Código-fonte, dados e configurações da operação permanecem privados.

[Todos os projetos](README.md) · [Perfil](../README.md)
