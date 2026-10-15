# Comparativo de Carros

Landing page em um arquivo só (HTML + CSS + JS, com as fotos dos cards inline em base64; as galerias dos Favoritos ficam em `fotos/` e só baixam quando o carro é aberto) comparando 17 versões de 15 modelos (o T2 e o Tank 300 aparecem em duas versões) do mercado brasileiro para ajudar uma decisão de compra em família.

🔗 **Versão online:** https://davidrobert.github.io/cars/

## Modelos comparados

| Modelo | Tipo | Preço (out/2026) | Potência |
|---|---|---|---|
| Fiat Toro Ultra T270 MHEV | Picape híbrida leve (4x2) | R$ 206.490 | 176 cv |
| Caoa Chery Tiggo 8 Pro PHEV | SUV 7 lug. PHEV | R$ 249.990 | 279 cv |
| Jetour S08 Premium | SUV 7 lug. PHEV | R$ 259.900 | 339 cv (soma dos motores) |
| GWM Haval H7 | SUV PHEV flex 4x4 | R$ 261.000 | 370 cv |
| Kia Sportage EX Prestige MHEV | SUV híbrido leve | R$ 267.190 | 178 cv |
| Jetour T2 Advance | SUV PHEV (4x2) | R$ 289.900 | 359 cv (soma dos motores) |
| Ram Rampage R/T Flex | Picape compacta 4x4 | R$ 275.990 | 272 cv |
| GWM Haval H6 GT Flex | SUV coupé PHEV | R$ 326.000 | 393 cv |
| Jeep Commander Blackhawk Flex | SUV 7 lug. | R$ 329.990 | 272 cv |
| GWM Tank 300 Hi4-T | SUV off-road PHEV | R$ 342.000 | 394 cv |
| Jetour T2 XWD 4x4 | SUV PHEV 4x4 | R$ 349.900 | 597 cv (soma dos motores) |
| GWM Tank 300 TerraForce | SUV off-road PHEV (série especial) | R$ 350.000 | 394 cv |
| GAC GS9 Ultra | SUV PHEV 6 lug. | R$ 379.990 | 500 cv |
| BYD Atto 8 | SUV PHEV 7 lug. | R$ 399.990 | 488 cv |
| GWM WEY 07 | SUV PHEV 6 lug. | R$ 429.000 | 517 cv |
| Denza B5 GS | SUV off-road PHEV | R$ 449.000 | 677 cv |
| Jeep Wrangler Rubicon | Off-road extremo | R$ 529.990 | 272 cv |

## Funcionalidades

- **Favoritos** — a lista de carros da família, que já vem com Tiggo 8 Pro PHEV, Haval H7, Rampage R/T, Commander Blackhawk e Tank 300 TerraForce. Dá pra adicionar e remover pela estrela (☆/★) dos cards e do detalhe do carro, ou pelo botão "+ Adicionar carro" (até 6), com "Desfazer". As colunas trocam de lugar arrastando o nome (computador), pelas setas ◀ ▶ ou pelo painel "Organizar" (celular). A lista fica salva no aparelho; "Copiar link" gera um endereço `#favoritos=...` pra mandar pra outra pessoa, e "Restaurar padrão" volta à lista inicial. O comparativo tem 13 critérios em 5 grupos (preço e revenda, espaço e família, desempenho, economia, segurança), com o melhor e o pior de cada linha e um veredito "melhor para". No celular vira uma grade com os carros lado a lado: até 5 cabem sem rolagem lateral, e com 6 só a grade rola, com os nomes fixos. As 17 versões têm galeria de 5 fotos, com crédito na legenda, e ficha conferida em out/2026 (versão, medidas, ISOFIX, airbags, NCAP, reboque, recarga, porta-malas em número comparável, garantia, itens de série e fontes); um carro que entrar sem ficha aparece com "dados resumidos". Há também glossário e fontes
- **Celular** — menu "Seções" no topo e painel de pesos (Tuning) começando fechado
- **Serve pra nossa família?** — checklist por carro com os requisitos da família (2 bebês-conforto simultâneos, carrinho duplo no porta-malas/caçamba coberta, segurança mínima, revenda em 4 anos, uso em SP, viagem mensal e adulto entre as crianças), com veredito, selo no card e bloco no detalhe do carro. Vira a métrica **Família** do score, com peso máximo no preset Família
- Cards com specs prioritárias (preço, potência, porta-malas, comprimento, autonomia)
- **Teto de orçamento de R$ 300 mil** — carro acima dele fica com o preço em vermelho (cards, tabela e Favoritos) e o selo "Preço alto". Pra mudar, edite `PRICE_LIMIT` no `index.html`
- Filtros por cenário (família, off-road, economia, viagem, etc.)
- Tabela comparativa completa com destaque pro melhor/pior em cada critério
- Recomendações por uso real (off-road, performance, família, etc.)
- Prós e contras de cada modelo
- Votação familiar interativa (salva no `localStorage`)
- Imprime/exporta pra PDF

## Disclaimer

Preços, fichas técnicas e consumos levantados em **outubro/2026** em fontes oficiais: sites, configuradores e fichas técnicas dos fabricantes; consumo e autonomia elétrica da tabela **PBEV 2026 do Inmetro**; depreciação pela **Tabela FIPE de out/2026**. A autonomia total é calculada como tanque × consumo na estrada (Inmetro) + autonomia elétrica (PHEV). Confirme tudo na concessionária antes de comprar.

Imagens via Wikimedia Commons (CC-BY/CC-BY-SA), sites oficiais e kits de imprensa das marcas — uso ilustrativo. Nos Favoritos, as fotos são de divulgação das marcas ou, quando a marca não tem a vista (porta-malas, banco traseiro), de revistas e testes automotivos, sempre com o crédito na legenda.
