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

---

# Páginas publicadas

## Estrutura base
- [x] `/index.html` — Homepage
- [x] `/sobre/index.html` — Sobre o site
- [x] `/afiliados/index.html` — Política de afiliados
- [x] `/robots.txt`
- [x] `/sitemap.xml`
- [x] `/assets/css/style.css`
- [x] `/assets/js/main.js`

## Profissões
- [x] `/carpintaria/` — Como ser carpinteiro
- [x] `/pedreiro/` — Como ser pedreiro
- [x] `/serralheiro/` — Como ser serralheiro
- [x] `/criacao-de-moveis/` — Como criar e vender móveis

## Ferramentas
- [x] `/ferramentas/` — Hub de ferramentas
- [x] `/ferramentas/furadeira/` — Guia da furadeira · afiliado: [Parafusadeira Furadeira The Black Tools 2 Baterias + 145 Acessórios](https://meli.la/2qqJnzx)
- [x] `/ferramentas/nivel-a-laser/` — Guia do nível a laser · afiliado: [Kit Nível A Laser Verde 12 Linhas + Suporte + Tripé](https://meli.la/1WugZ8H)
- [x] `/ferramentas/serra-circular/` — Guia da serra circular · afiliado: [Serra Circular Makita HS7010 7.1/4pol 1600W](https://meli.la/24kvkhy)

## Guias
- [x] `/guias/` — Hub de guias
- [x] `/guias/como-conseguir-clientes/` — Como conseguir os primeiros clientes

---

# Próximas páginas

## Profissões (próximas)
- [x] `/eletricista/` — Como ser eletricista
- [x] `/encanador/` — Como ser encanador
- [x] `/pintor/` — Como ser pintor
- [x] `/gesseiro/` — Como ser gesseiro
- [x] `/soldador/` — Como ser soldador
- [x] `/mecanico/` — Como ser mecânico
- [x] `/chaveiro/` — Como ser chaveiro
- [x] `/jardineiro/` — Como ser jardineiro
- [x] `/barbeiro/` — Como ser barbeiro
- [x] `/cabeleireiro/` — Como ser cabeleireiro
- [x] `/manicure/` — Como ser manicure
- [x] `/costureira/` — Como ser costureira
- [x] `/confeiteira/` — Como ser confeiteira
- [x] `/fotografo/` — Como ser fotógrafo
- [x] `/tecnico-em-informatica/` — Como ser técnico em informática
- [x] `/lavador-de-veiculos/` — Como ser lavador de veículos
- [x] `/instalador-de-ar-condicionado/` — Como instalar ar-condicionado

## Conteúdo complementar (carpintaria)
- [x] `/carpintaria/como-ser-carpinteiro/`
- [ ] `/carpintaria/ferramentas-para-carpinteiro/`
- [ ] `/carpintaria/quanto-ganha-um-carpinteiro/`
- [ ] `/carpintaria/como-conseguir-clientes/`
- [ ] `/carpintaria/como-fazer-orcamento/`
- [ ] `/carpintaria/como-cobrar-por-servico/`
- [ ] `/carpintaria/erros-de-carpinteiro-iniciante/`

## Ferramentas (próximas)

### Prioridade 1 — citadas nas profissões já publicadas
- [x] `/ferramentas/serra-circular/` — Serra circular · afiliado: [Serra Circular Makita HS7010 7.1/4pol 1600W](https://meli.la/24kvkhy) · usada em: carpintaria, criação de móveis
- [x] `/ferramentas/parafusadeira/` — Parafusadeira · afiliado existente: [Parafusadeira Furadeira The Black Tools 2 Baterias + 145 Acessórios](https://meli.la/2qqJnzx) · usada em: carpintaria, criação de móveis, pedreiro
- [x] `/ferramentas/lixadeira/` — Lixadeira orbital · usada em: carpintaria, criação de móveis, serralheiro
- [x] `/ferramentas/esmerilhadeira/` — Esmerilhadeira · usada em: serralheiro
- [x] `/ferramentas/martelete/` — Martelete · usada em: pedreiro, eletricista, instalador de ar-condicionado
- [x] `/ferramentas/maquina-de-solda/` — Máquina de solda · usada em: serralheiro, soldador
- [x] `/ferramentas/serra-tico-tico/` — Serra tico-tico · usada em: carpintaria, criação de móveis

### Prioridade 2 — profissões futuras
- [x] `/ferramentas/compressor-de-ar/` — Compressor de ar · usada em: pintor, serralheiro
- [x] `/ferramentas/pistola-de-pintura/` — Pistola de pintura · usada em: pintor
- [x] `/ferramentas/alicate-universal/` — Alicate universal · usada em: eletricista, serralheiro
- [x] `/ferramentas/multimetro/` — Multímetro · usada em: eletricista, técnico em informática
- [x] `/ferramentas/kit-encanador/` — Kit encanador · usada em: encanador
- [x] `/ferramentas/maquina-de-cortar-cabelo/` — Máquina de cortar cabelo · usada em: barbeiro, cabeleireiro

## Guias (próximos)
- [x] `/guias/como-fazer-orcamento/`
- [x] `/guias/como-usar-whatsapp-para-conseguir-clientes/`
- [x] `/guias/como-abrir-mei/`
- [x] `/guias/como-cobrar-por-servico/`