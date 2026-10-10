# Comparativo de Carros

Landing page autocontida (HTML + CSS + JS, com fotos inline em base64) comparando 12 modelos do mercado brasileiro para ajudar uma decisão de compra em família.

🔗 **Versão online:** https://davidrobert.github.io/cars/

## Modelos comparados

| Modelo | Tipo | Preço (out/2026) | Potência |
|---|---|---|---|
| Fiat Toro Ultra T270 MHEV | Picape híbrida leve (4x2) | R$ 206.490 | 176 cv |
| Caoa Chery Tiggo 8 Pro PHEV | SUV 7 lug. PHEV | R$ 249.990 | 279 cv |
| Ram Rampage R/T Flex | Picape compacta 4x4 | R$ 275.990 | 272 cv |
| Jetour T2 Advance | SUV PHEV | R$ 289.900 | 359 cv (soma dos motores) |
| GWM Haval H6 GT Flex | SUV coupé PHEV | R$ 326.000 | 393 cv |
| Jeep Commander Blackhawk Flex | SUV 7 lug. | R$ 329.990 | 272 cv |
| GWM Tank 300 Hi4-T TerraForce | SUV off-road PHEV (série especial) | R$ 350.000 | 394 cv |
| GAC GS9 Ultra | SUV PHEV 6 lug. | R$ 379.990 | 500 cv |
| BYD Atto 8 | SUV PHEV 7 lug. | R$ 399.990 | 488 cv |
| GWM WEY 07 | SUV PHEV 6 lug. | R$ 429.000 | 517 cv |
| Denza B5 GS | SUV off-road PHEV | R$ 449.000 | 677 cv |
| Jeep Wrangler Rubicon | Off-road extremo | R$ 529.990 | 272 cv |

## Funcionalidades

- **Minha seleção** — os finalistas da família (hoje Tiggo 8 Pro PHEV, Rampage R/T, Commander Blackhawk e Tank 300 TerraForce), cada um na versão mais completa à venda. Tem um comparativo resumido com 13 critérios em 5 grupos (preço e revenda, espaço e família, desempenho, economia, segurança), com o melhor e o pior de cada linha destacados e um veredito "melhor para" por carro. No celular ele vira uma grade com os carros lado a lado, sem rolagem lateral. Cada carro tem galeria de 5 fotos oficiais das marcas, com crédito na legenda, e ficha completa conferida em out/2026 (entre-eixos, reboque, ISOFIX, garantia, consumo com etanol, recarga, itens de série). Há também glossário e fontes. Pra mudar a lista, edite o array `SELECAO` no `index.html`
- **Celular** — menu "Seções" no topo e painel de pesos (Tuning) começando fechado
- **Serve pra nossa família?** — checklist por carro com os requisitos da família (2 bebês-conforto simultâneos, carrinho duplo no porta-malas/caçamba coberta, segurança mínima, revenda em 4 anos, uso em SP, viagem mensal e adulto entre as crianças), com veredito, selo no card e bloco no detalhe do carro. Vira a métrica **Família** do score, com peso máximo no preset Família
- Cards com specs prioritárias (preço, potência, porta-malas, comprimento, autonomia)
- Filtros por cenário (família, off-road, economia, viagem, etc.)
- Tabela comparativa completa com destaque pro melhor/pior em cada critério
- Recomendações por uso real (off-road, performance, família, etc.)
- Prós e contras de cada modelo
- Votação familiar interativa (salva no `localStorage`)
- Imprime/exporta pra PDF

## Disclaimer

Preços, fichas técnicas e consumos levantados em **outubro/2026** em fontes oficiais: sites, configuradores e fichas técnicas dos fabricantes; consumo e autonomia elétrica da tabela **PBEV 2026 do Inmetro**. A autonomia total é calculada como tanque × consumo na estrada (Inmetro) + autonomia elétrica (PHEV). Confirme tudo na concessionária antes de comprar.

Imagens via Wikimedia Commons (CC-BY/CC-BY-SA), sites oficiais e kits de imprensa das marcas — uso ilustrativo. Na Minha seleção, todas as fotos são de divulgação das marcas, com o crédito na legenda.
