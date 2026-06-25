# SPM Tech — Portfólio estático

Portfólio profissional para serviços de:

- Migração de dados ERP
- Performance SQL
- Diagnóstico técnico de banco
- Relatórios e BI operacional
- Integrações e validação de dados

## Como editar

Arquivos principais:

- `index.html`: conteúdo do site
- `styles.css`: visual
- `script.js`: menu mobile e ano automático

Antes de publicar, altere no `index.html`:

1. WhatsApp no link `https://wa.me/5500000000000`
2. E-mail `contato@spmtech.com.br`
3. Domínio, se quiser incluir nos metadados
4. Cases anonimizados com números reais permitidos
5. Nome completo ou assinatura comercial, se desejar

## Como testar localmente

Abra o arquivo `index.html` no navegador.

Ou rode um servidor local:

```bash
python -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000
```

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub, por exemplo: `spm-tech`
2. Envie estes arquivos para a branch principal
3. Vá em Settings > Pages
4. Em "Build and deployment", selecione "Deploy from a branch"
5. Selecione a branch `main` e a pasta `/root`
6. Salve

## Como publicar no Netlify

1. Acesse Netlify
2. Escolha "Add new site"
3. Você pode arrastar a pasta do projeto ou conectar o GitHub
4. Configure domínio próprio depois, se quiser

## Como publicar na Vercel

1. Acesse Vercel
2. Importe o repositório do GitHub
3. Como é HTML/CSS/JS puro, não precisa de framework
4. Publique e configure domínio próprio

## Recomendação prática

Para a primeira versão:

- GitHub Pages se quiser custo zero e simplicidade
- Netlify se quiser arrastar a pasta e publicar rápido
- Vercel se futuramente quiser migrar para Next.js

Para a SPM Tech hoje, GitHub Pages ou Netlify são suficientes.
