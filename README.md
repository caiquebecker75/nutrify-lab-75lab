# NUTRIFY LAB · 75 LAB × Nutrify

Apresentação comercial em HTML, **13 telas**, cada uma com composição própria.

**Objetivo do projeto:** estruturar a 75 LAB como braço estratégico e operacional das ativações
de Integral, Nutrify e Darkness, assumindo desde o desenvolvimento da experiência até a execução
no PDV, logística, gestão da equipe e mensuração dos resultados, com foco em conversão e venda.

## As 13 telas
| # | Tela | Composição |
|---|---|---|
| 01 | Abertura | Manifesto com anel de busca e contador de 188 milhões |
| 02 | O desafio | Quatro falas da reunião contra o par aparente e real |
| 03 | O contexto | Três indicadores, barras por canal e mapa de posicionamento |
| 04 | NUTRIFY LAB | Reveal com dois cartões de formato clicáveis |
| 05 | Routine Lab | Passos animados, números e a demo funcional no tablet |
| 06 | Move Lab | Foto em sangria, passos e o voucher de amostra |
| 07 | O acordo | Duas colunas enfrentadas com seta central |
| 08 | A operação | Quatro papéis e o diagrama das três frentes regionais |
| 09 | Rastreamento | One Shot contra On Timing e o fluxo até a decisão |
| 10 | Mensuração | Funil, três níveis e as metas do piloto |
| 11 | Cronograma | Gantt com gates nas fases de decisão |
| 12 | Investimento | Preço, o que está incluso e três cenários |
| 13 | Próximo passo | Fecho com os dados institucionais |

## Experiência
- Transição cinematográfica: cortina dupla varrendo a tela mais escala e desfoque, com direção invertida ao voltar
- Cabeçalho fixo com as duas marcas e o capítulo corrente
- Cursor customizado em dois tons, desligado em toque
- Fundo vivo com blobs e grade em deriva lenta
- Lightbox em todas as imagens, com setas, ESC, clique fora e navegação por teclado
- Demo funcional do Routine Lab: quatro perguntas clicáveis e resultado calculado
- Passo a passo animado em sequência contínua
- Números com contagem progressiva
- Navegação: setas, espaço, roda do mouse, swipe, `M` índice, `N` e `P` por capítulo
- `prefers-reduced-motion` respeitado, foco visível, imagens com alt e aria-label

## Investimento
R$ 1.008,84 por loja e por dia de ativação, com promotor, supervisor, coordenação, uniforme,
insumos, refeição, deslocamento, app de campo, BI e a experiência inclusos.
Projeto de 30 lojas e 96 diárias: R$ 96.848,89. Piloto de 2 lojas e 6 diárias: R$ 6.053,06.
Base no orçamento de promotoria, com fee 12%, BV 20% e impostos 19% aplicados.

## Fontes dos dados de mercado
- BRASNUTRI com dados Euromonitor: R$ 7,6 bi em 2025, alta de 15%
- Projeção de R$ 13,8 bi até 2030
- Future Market Insights: crescimento médio de 9,5% ao ano entre 2026 e 2036
- IFEPEC: participação por canal (farmácia 48%, e-commerce 24%, supermercado 15%, especializada 8%)
- Social SA: 188 milhões de buscas pela categoria em um ano

## Arquitetura
Arquivo único `index.html` sem build e sem dependência externa além das fontes do Google
(Archivo, Space Grotesk, Space Mono). Imagens em `assets/`, JPEG progressivo de 1680 px.
Deploy por GitHub Pages.

---
© 75 LAB · *Ideia boa é a que acontece.*
