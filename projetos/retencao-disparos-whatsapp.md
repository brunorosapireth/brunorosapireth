# Retorno de pacientes e comunicação pelo WhatsApp

**Segmento:** Saúde e relacionamento

Convites e avisos com contexto de conversa, controle de tentativas e registro de envio.

## O problema

Uma mensagem automática pode chegar na hora errada ou repetir um convite para quem já recusou. O envio precisava considerar o histórico da conversa e permitir acompanhamento pela equipe.

## O que construí

- Convites seguindo o prazo definido pelo profissional.
- Leitura do contexto da conversa antes do convite.
- Controle de tentativas e indicação de contatos que não devem receber novos convites.
- Fila de envio, modelos de mensagem e registros para evitar duplicidade.

## Decisão técnica

O prazo de retorno vem do profissional, não da IA. O contexto da conversa participa da decisão de contato, e a equipe acompanha os casos que precisam de intervenção.

## Fluxo resumido

Prazo definido → contexto da conversa → regras de contato → fila → acompanhamento.

## Na operação

A comunicação passa a considerar o histórico e o estado do contato, com registro do que foi enviado.

## Ferramentas usadas

n8n, Claude, WhatsApp e PostgreSQL.

[Ver apresentação e telas no portfólio](https://brunopireth.com.br/cases/retencao-disparos-whatsapp)

---

Este estudo apresenta o projeto por segmento. Código-fonte, dados e configurações da operação permanecem privados.

[Todos os projetos](README.md) · [Perfil](../README.md)
