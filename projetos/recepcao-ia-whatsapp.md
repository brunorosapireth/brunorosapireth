# Atendimento com IA para clínicas

**Segmento:** Saúde

WhatsApp integrado à agenda, com regras de atendimento e encaminhamento para a equipe.

## O problema

A equipe recebia dúvidas, pedidos de agendamento, remarcações e comprovantes no mesmo canal. A agenda precisava conversar com o atendimento, sem deixar informações importantes dependerem apenas da resposta de um modelo.

## O que construí

- Atendimento pelo WhatsApp com consulta de horários e integração à agenda.
- Agendamento, remarcação e cancelamento pelas ferramentas do sistema.
- Agrupamento de mensagens e respeito às janelas de atendimento.
- Pausa do agente quando a equipe assume e encaminhamento com resumo.

## Decisão técnica

A IA prepara a resposta, mas uma camada de regras em código confere informações antes do envio. Valores vêm da tabela cadastrada; pedidos de orientação clínica seguem para a equipe.

## Fluxo resumido

Mensagem → organização da conversa → agente → validação em código → resposta ou equipe.

## Na operação

Atendimento conectado à agenda e casos que exigem uma pessoa encaminhados com contexto.

## Ferramentas usadas

n8n, Claude, Node.js, PostgreSQL, Supabase e WhatsApp.

[Ver apresentação e telas no portfólio](https://brunopireth.com.br/cases/recepcao-ia-whatsapp)

---

Este estudo apresenta o projeto por segmento. Código-fonte, dados e configurações da operação permanecem privados.

[Todos os projetos](README.md) · [Perfil](../README.md)
