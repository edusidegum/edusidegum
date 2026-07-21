# projeto-loja-virtual.html — Documento Confidencial

Página de escopo e pricing para projeto de **Loja Virtual + Presença Institucional + Integrações**.

---

## Visão Geral

Documento técnico-comercial **confidencial**. Apresenta componentes que elevam a complexidade, faixas de valor praticadas em 2026, fontes de mercado que corroboram os valores e justificativas de posicionamento como Arquiteto de Soluções.

---

## Status de Indexação

**NÃO indexável. NÃO rastreável.** Esta página é protegida contra indexação e rastreio por **todos** os robots, inclusive crawlers de LLM/IA:

- `noindex, nofollow, noarchive, nosnippet, noimageindex, notranslate, none`
- Bloqueio explícito de **18 crawlers de IA/LLM**: GPTBot, CCBot, ClaudeBot, Anthropic-AI, PerplexityBot, Google-Extended, Amazonbot, Bytespider, Cohere-AI, Meta-ExternalAgent, AI2Bot, Diffbot, ImagesiftBot, Omgili, OmgiliBot, FacebookBot, TwitterBot
- `referrer: no-referrer`
- `Cache-Control: no-store, no-cache` + `Pragma: no-cache`

---

## Como Esta Página Recebe Relevância

Embora **não indexada**, esta página é **referenciada como página do autor** a partir de `sobre.html` (página canônica indexável). A relevância flui por **referência cruzada**, não por rastreio direto:

```
sobre.html (indexável, canônica)
   │
   ├── referencia → projeto-loja-virtual.html (não-indexada, confidencial)
   │
   └── autoridade E-E-A-T do autor flui por associação
```

O motor de busca / LLM indexa o **autor** (via `sobre.html`); o documento confidencial herda credibilidade por pertencer ao mesmo autor, sem ser rastreado diretamente.

---

## Proteções Aplicadas

### Anti-cópia (browser)

| Proteção | Implementação |
|---|---|
| Seleção de texto | `user-select: none` global |
| Arrastar imagens | `user-drag: none` + `pointer-events: none` |
| Botão direito | `contextmenu` bloqueado |
| Copiar/Recortar | `copy`, `cut` bloqueados |
| Atalhos teclado | Ctrl+A/S/P/O/U, F12, Ctrl+Shift+I/J/C bloqueados |
| Impressão | `@media print` vazio + `beforeprint` esconde conteúdo |
| DevTools | Detecção por timing (`debugger`) + diferença de janela → `blur(20px)` |
| Console | Métodos `console.*` neutralizados + limpeza a 500ms |

### Anti-rastreio

- Meta robots completo (`noindex, nofollow, noarchive, nosnippet, noimageindex, notranslate, none`)
- Bloqueio de crawlers de IA/LLM (18 user-agents)
- Sem referrer, sem cache

---

## Stack Técnico

- **Mesmo CSS/UX de `sobre.html`** (parallax multi-camada, orbs flutuantes, scroll progress, reveal animations, glassmorphism)
- **HTML5** semântico
- **JavaScript** vanilla (proteções + animações)
- **Acessibilidade mantida**: `prefers-reduced-motion`, skip link, focus-visible, ARIA labels
- **Tipografia**: Inter + JetBrains Mono

---

## Estrutura

1. **Hero** — "Loja Virtual + Presença Institucional + Integrações"
2. **Componentes** — 5 cards (integração com base existente, frete, gateway, catálogo 50 produtos, sem manutenção)
3. **Faixas de Valor 2026** — 3 cards (Básico, Médio [destacado como Recomendado], Completo)
4. **Fontes** — AtomTI, Metodoviral, Moggy, Own Web
5. **Justificativas** — 4 pontos de posicionamento (briefing, integração, entrega única, diferencial LLM/SEO)
6. **CTA** — WhatsApp (mensagem pré-preenchida)

---

## Confidencialidade

Conteúdo comercial confidencial. **Não distribuir.** Acesso controlado via referência do autor a partir de `sobre.html`.

---

## Autor

**Edu Sidegum**  
Bacharel em Sistemas de Informação  
Arquitetura de Soluções Digitais  

---

## Licença

Conteúdo confidencial de uso restrito do autor e destinatários autorizados. Estrutura de código reutilizável sob decisão do autor.
