# Segurança

Este repositório foi preparado para evitar exposição acidental de dados sensíveis.

## Nunca publicar

- Tokens
- Senhas
- API keys
- Arquivos `.env`
- Bancos de dados reais
- Credenciais de Discord, GitHub, Replit, Roblox ou serviços externos
- Dados pessoais privados

## Como usar variáveis de ambiente

Use `.env.example` como modelo público.

Crie um arquivo `.env` apenas localmente:

```txt
.env
```

O `.gitignore` já bloqueia esse arquivo.

## Áreas restritas

As pastas `areas/javascript`, `areas/typescript` e `areas/sql` têm regras próprias para evitar que conteúdo sensível seja enviado sem querer.

Se quiser publicar algum projeto dessas áreas, revise antes e remova qualquer dado privado.
