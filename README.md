# L3C API

Projeto de API para gestão esportiva, com regras de negócio, persistência de dados, elegibilidade, partidas e integrações externas.

## Arquitetura prevista
NestJS, Prisma e PostgreSQL.

## Minha atuação
Levantamento de requisitos, modelagem de regras, validação de integrações e diagnóstico de falhas com apoio de IA.

## Estado deste repositório
Repositório inicial de documentação; não representa a API completa em produção.

---

## Referência operacional preservada

### l3c-api

API oficial L3C Stats (NestJS / Prisma)

Este repositório receberá o código da API de produção. **Ainda não existe implantação automática.**

Fluxo planejado: `feature/*` → testes → PR → homologação → publicação autorizada.

Antes de migrar: backup do banco, compatibilidade de schema Prisma, índices, importação GoChamps, vínculos dos jogos do Master e conservação de dados esportivos.

**Não enviar:** `.env` real, `DATABASE_URL`, tokens, credenciais, backups ou bancos de produção.
