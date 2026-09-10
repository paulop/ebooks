# Uma Nova Renda — Projeto

## Objetivo

Criar o portal https://umanovarenda.com para pessoas que desejam iniciar uma nova fonte de renda através de profissões, prestação de serviços ou pequenos negócios.

O conteúdo deve ensinar de forma simples e prática:

- O que é a profissão
- O que o profissional faz
- Perfil e comportamento
- Mentalidade necessária
- Como começar do zero
- Ferramentas necessárias
- Investimento inicial
- Como conseguir os primeiros clientes
- Como cobrar
- Potencial de renda
- Erros comuns
- Plano de ação

O foco é **conteúdo útil e educativo**, não uma loja ou página de vendas.

---

# Arquitetura

O site é **100% estático**: apenas HTML, CSS, JavaScript e imagens. Sem PHP, Node.js, banco de dados, SSR ou API de renderização.

## Regra obrigatória de URL

Toda URL corresponde a uma pasta física com `index.html`:

```
/carpintaria/index.html
/criacao-de-moveis/index.html
```

Nunca criar `/carpintaria.html` ou `/carpintaria.php`.

---

# Estrutura

```
/
├── index.html
├── robots.txt
├── sitemap.xml
├── assets/
│   ├── css/style.css
│   ├── js/main.js
│   └── images/
├── carpintaria/index.html
├── criacao-de-moveis/index.html
├── pedreiro/index.html
├── serralheiro/index.html
├── ferramentas/
│   ├── index.html
│   └── furadeira/index.html
├── guias/
│   ├── index.html
│   └── como-conseguir-clientes/index.html
├── sobre/index.html
└── afiliados/index.html
```

Novas páginas seguem o padrão `/nome-da-pagina/index.html`.

---

# URLs

- Minúsculas, sem acentos, sem caracteres especiais
- Palavras separadas por hífen
- Curtas e descritivas

---

# Conteúdo das profissões

Cada profissão segue esta estrutura:

1. Introdução
2. O que faz o profissional
3. Perfil ideal
4. Mentalidade
5. Como começar do zero
6. Ferramentas necessárias
7. Investimento inicial
8. Como conseguir clientes
9. Quanto pode ganhar *(estimativa)*
10. Erros comuns
11. Plano de ação de 30 dias
12. Perguntas frequentes
13. Conteúdos relacionados
14. Conclusão

A renda é sempre apresentada como **estimativa**, nunca como garantia.

---

# SEO

Todas as páginas devem ter:

- `<title>` único, meta description, canonical, Open Graph
- HTML semântico com H1/H2/H3 organizados
- Breadcrumbs, links internos, `alt` em imagens
- Schema.org (Article, FAQPage quando aplicável)
- Todas as URLs públicas no `sitemap.xml`

---

# Design

- Mobile First, carregamento rápido, boa legibilidade
- Transmitir confiança, simplicidade e profissionalismo
- CSS em `/assets/css/style.css`; JS somente quando necessário

---

# Afiliados

Monetização via links de afiliados de ferramentas e equipamentos. Sempre como **recomendação contextual**, nunca venda agressiva.

Botões: *Ver opções / Pesquisar modelos / Consultar opções / Comparar modelos*

Nunca: *Compre agora / Oferta imperdível / Última chance*

---

# Escalabilidade

Templates reutilizáveis para adicionar novas profissões rapidamente.  
Meta inicial: **50 profissões × 6–10 conteúdos ≈ 300–500 páginas estáticas**.

---

# Regra principal

**O usuário deve encontrar conteúdo realmente útil para começar uma nova profissão. Os links de afiliados entram naturalmente como indicação das ferramentas necessárias.**

**O resultado final é um site estático onde cada URL corresponde fisicamente a uma pasta com `index.html`.**