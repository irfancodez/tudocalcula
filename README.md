# TudoCalcula — site estático

Site de calculadoras trabalhistas brasileiras (pt-BR), HTML/CSS/JS puro, sem build.

## Estrutura
- `index.html` — página inicial
- `calculadora-salario-liquido/` e `calculadora-decimo-terceiro-salario/` — calculadoras no ar
- `sobre/`, `contato/`, `privacidade/`, `termos/`, `aviso-legal/` — páginas institucionais
- `sitemap.xml`, `robots.txt`

## Publicação (Cloudflare Pages)
1. Suba esta pasta para um repositório GitHub chamado `tudocalcula` (público).
2. Cloudflare → Workers & Pages → Create → Pages → Connect to Git → selecione o repositório.
3. Framework preset: None · Build command: (vazio) · Output directory: /
4. Deploy → o site fica em https://tudocalcula.pages.dev

## Ao ligar o domínio próprio
Troque `tudocalcula.pages.dev` pelo domínio em: canonical das páginas, `sitemap.xml` e `robots.txt`, e atualize o e-mail em `contato/`.
