# Curious — Design System

Fonte única de verdade da identidade visual da Curious (staycurious.com.br).
Manual online: https://claude.ai/code/artifact/963335a9-1813-49df-8cbe-a8fd9b34d90a
Repositório: https://github.com/ogabrielromano/curious-design-system (público)

## Estrutura da pasta

| Pasta | Conteúdo |
|---|---|
|  `docs/` | `index.html` — o manual completo, autocontido (fontes, logos e downloads embutidos). **É este arquivo que sobe para o domínio.** |
| `Logos/` | Arquivos oficiais da marca: logotipo e símbolo ¿ em SVG (vetorial, em curvas) e PNG (fundo branco/preto). |
| `Fontes/` | `Aileron - Fonte Curious.zip` — Regular, Italic, SemiBold, Bold e Black (licença CC0, uso livre). A Cambon (fonte do logo) é comercial e não fica aqui. |
| `Diretrizes IA/` | `curious-diretrizes-ia.md` — cole em qualquer IA junto com o pedido para o material sair na identidade da marca. |
| `_Arquivados/` | Duplicatas e versões antigas. Não usar. |

## Como publicar o manual no domínio

O manual é publicado automaticamente pelo **GitHub Pages** a partir da pasta `docs/` (branch `main`):

- URL do Pages: https://ogabrielromano.github.io/curious-design-system/
- Domínio próprio: `marca.staycurious.com.br` (configurado via `docs/CNAME` — requer um registro DNS `CNAME marca → ogabrielromano.github.io` no provedor do domínio).

Ao atualizar a identidade: edite o manual, substitua o `docs/index.html`, mantenha `Logos/`, `Fontes/` e `Diretrizes IA/` em sincronia e faça `git push` — o site publica sozinho em ~1 minuto.

## Regras de ouro (resumo)

- Paleta 100% monocromática: preto `#181818`, branco `#FFFFFF` e cinzas `#F5F5F5` / `#E0E0E0` / `#8E8E8E` / `#5F5F5F`. **Sem cor de acento.**
- Fonte de trabalho: **Aileron** (fallback Arial/Helvetica). Cambon só no logo.
- Logo sempre a partir dos arquivos de `Logos/` — nunca digitado com fonte.

*Design System v1.5 · julho 2026*
