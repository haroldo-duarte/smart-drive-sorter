# Smart Drive Sorter

Aplicação para organização inteligente do Google Drive via OpenAI, com segurança reforçada.

## Estrutura do Projeto

- **backend/**: Servidor Express, autenticação, integração Google Drive e OpenAI, fila de jobs.
- **frontend/**: React, UI dos cartões e painel, autenticação, integração.

## Setup Rápido

1. Configure seu `.env` (veja exemplos em cada diretório).
2. Siga o checklist Google Cloud do escopo para ativar APIs e criar credenciais.
3. Rode `npm install` e `npm run dev` em cada parte.

## Segurança

- Cookies HTTPOnly + Secure + SameSite=Lax
- OpenAI API Key criptografada (AES-256-GCM) no backend
- Tokens Google nunca expostos no frontend
- CORS restrito, Helmet, CSP

## Critérios de Aceitação

Veja o escopo completo para garantir conformidade e segurança máxima.

## Licença

MIT
