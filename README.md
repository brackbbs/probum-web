# Probum

Plataforma B2B de apoio técnico-jurídico para auditoria em saúde suplementar.

Três sub-aplicações:
- **Probum Triagem** — análise protocolar (alto custo + cotidianas)
- **Probum Quesitos** — quesitos técnico-jurídicos sob demanda
- **Probum Doutrina** — pareceres especializados sob demanda

## Stack

Frontend estático em HTML único (`index.html`) + Supabase JS SDK via CDN. Backend: Supabase (Postgres + Auth + Storage). Sem framework, sem build.

## Desenvolvimento local

Abrir `index.html` direto no navegador. Não precisa servidor.

## Deploy

Netlify ou Vercel apontando pra este repositório. Domínio: probum.com.br.

## Estrutura

- `index.html` — aplicação inteira
- `supabase-config.js` — credenciais públicas do Supabase (URL + anon key)
- `01_schema.sql` — schema inicial do banco (não versionado; rodar manualmente no Supabase)

---
© Fabio Brack · 2026
