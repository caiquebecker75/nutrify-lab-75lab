# NUTRIFY LAB · 75 LAB × Nutrify

Apresentação comercial em HTML, **44 telas**, uma ideia por tela, com arco narrativo completo.

**Objetivo do projeto:** estruturar a 75 LAB como braço estratégico e operacional das ativações
de Integral, Nutrify e Darkness, assumindo desde o desenvolvimento da experiência até a execução
no PDV, logística, gestão da equipe e mensuração dos resultados, com foco em conversão e venda.

## Estrutura narrativa
| Capítulo | Telas | O que entrega |
|---|---|---|
| Abertura | 01 a 04 | Manifesto, capa, agenda visual e quem assina |
| 01 · O desafio | 05 a 08 | Decupagem do briefing, problema aparente x real, objetivo, o acordo |
| 02 · O contexto | 09 a 13 | Mercado, canal, jornada do shopper, mapa competitivo, tendências |
| 03 · A tese | 14 a 15 | O insight e a oportunidade |
| 04 · A solução | 16 a 29 | Reveal do Nutrify Lab, Routine Lab e Move Lab |
| 05 · A operação | 30 a 38 | Divisão do trabalho, equipe, conversão, rastreamento, medição, benefícios, resultados |
| 06 · O fecho | 39 a 44 | Cronograma, investimento, 360, próximo passo, encerramento, institucional |

## Experiência
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
