# Curious — Design System

Fonte única de verdade da identidade visual da Curious (staycurious.com.br).
Manual online: https://claude.ai/code/artifact/963335a9-1813-49df-8cbe-a8fd9b34d90a
Repositório: https://github.com/ogabrielromano/curious-design-system (privado)

## Estrutura da pasta

| Pasta | Conteúdo |
|---|---|
| `Site/` | `index.html` — o manual completo, autocontido (fontes, logos e downloads embutidos). **É este arquivo que sobe para o domínio.** |
| `Logos/` | Arquivos oficiais da marca: logotipo e símbolo ¿ em SVG (vetorial, em curvas) e PNG (fundo branco/preto). |
| `Fontes/` | `Aileron - Fonte Curious.zip` — Regular, Italic, SemiBold, Bold e Black (licença CC0, uso livre). A Cambon (fonte do logo) é comercial e não fica aqui. |
| `Diretrizes IA/` | `curious-diretrizes-ia.md` — cole em qualquer IA junto com o pedido para o material sair na identidade da marca. |
| `_Arquivados/` | Duplicatas e versões antigas. Não usar. |

## Como publicar o manual no domínio

O `Site/index.html` é um arquivo único, sem dependências — basta hospedar:

- **Subdomínio (recomendado):** crie `marca.staycurious.com.br` apontando para qualquer hospedagem estática (Netlify, Vercel, Cloudflare Pages, ou o próprio servidor) e suba o `index.html`.
- **Caminho no site atual:** se o site principal permitir (Framer tem limitações para páginas custom), suba como `staycurious.com.br/marca/index.html`.

Ao atualizar a identidade: edite o manual, substitua o `index.html` e mantenha os arquivos de `Logos/`, `Fontes/` e `Diretrizes IA/` em sincronia — o manual é a referência final.

## Regras de ouro (resumo)

- Paleta 100% monocromática: preto `#181818`, branco `#FFFFFF` e cinzas `#F5F5F5` / `#E0E0E0` / `#8E8E8E` / `#5F5F5F`. **Sem cor de acento.**
- Fonte de trabalho: **Aileron** (fallback Arial/Helvetica). Cambon só no logo.
- Logo sempre a partir dos arquivos de `Logos/` — nunca digitado com fonte.

*Design System v1.5 · julho 2026*
