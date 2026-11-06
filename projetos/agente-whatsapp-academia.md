# Gestão de aulas e atendente por áudio

**Segmento:** Academia de tênis

Sistema de aulas e quadras conectado a um agente que entende mensagens e áudio.

## O problema

A equipe precisava remarcar aulas e consultar vagas pelo WhatsApp, respeitando a ocupação das quadras e o acesso de cada aluno às próprias informações.

## O que construí

- Aplicação para alunos e painel administrativo com permissões.
- Grade de aulas e quadras, créditos por faltas e remarcações.
- Agente conectado ao sistema para consultar e executar operações autorizadas.
- Transcrição de áudio na infraestrutura própria e memória por conversa.

## Decisão técnica

A identidade usada nas operações vem do canal, não de uma declaração no texto da conversa. A regra de ocupação da quadra fica no banco para atender diferentes caminhos de reserva.

## Fluxo resumido

Texto ou áudio → transcrição quando necessária → agente → permissões → agenda.

## Na operação

Alunos podem tratar de aulas pelo canal de atendimento, com operações vinculadas às regras do sistema.

## Ferramentas usadas

React, Supabase, n8n, Claude, Whisper, Docker e VPS Linux.

[Ver apresentação e telas no portfólio](https://brunopireth.com.br/cases/agente-whatsapp-academia)

---

Este estudo apresenta o projeto por segmento. Código-fonte, dados e configurações da operação permanecem privados.

[Todos os projetos](README.md) · [Perfil](../README.md)
