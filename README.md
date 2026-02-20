# Plataforma Inteligente de Chamados - Power Platform

## 📌 Visão Geral

Projeto de arquitetura de solução utilizando Power Platform para modernização do processo de abertura e gestão de chamados internos.

## 🎯 Objetivo

Criar um fluxo inteligente que:

- Permita abertura de chamados via Power Apps
- Utilize IA para organizar solicitações em linguagem natural
- Armazene dados estruturados no SharePoint
- Automatize encaminhamento com Power Automate
- Disponibilize indicadores no Power BI

## 🏗 Arquitetura da Solução

Usuário  
↓  
Power Apps  
↓  
SharePoint  
↓  
Power Automate  
↓  
IA (Padronização e Classificação)  
↓  
Time Técnico  
↓  
Power BI (Indicadores)

## 📊 Benefícios Esperados

- Redução de retrabalho
- Comunicação clara entre áreas
- Monitoramento de SLA
- Governança e rastreabilidade
- Apoio de IA no processo

## 🚀 Roadmap de Implementação

- Fase 1 — Planejamento e Escopo
- Fase 2 — Modelagem de Dados
- Fase 3 — Desenvolvimento do App
- Fase 4 — Automação
- Fase 5 — Integração com IA
- Fase 6 — Indicadores
- Fase 7 — Testes e Consolidação



## 🗺 Diagrama da Arquitetura

```mermaid
flowchart TD

A[Usuário] --> B[Power Apps<br>Interface de Abertura]
B --> C[SharePoint<br>Base Estruturada]
C --> D[Power Automate<br>Fluxo Automatizado]
D --> E[IA<br>Classificação e Padronização]
E --> F[Time Técnico]
F --> G[Power BI<br>Indicadores e SLA]