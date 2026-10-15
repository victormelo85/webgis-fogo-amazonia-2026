# Fogo recente na Amazônia

WebGIS público de Acre, Amazonas, Pará e Rondônia. Consulta das fontes: 15/10/2026.

# Fogo recente — WebGIS mensal e decendial

Consulta das fontes em 15/10/2026. Extraia o ZIP e abra `webgis.html` em um navegador, mantendo a pasta `bases` ao lado do HTML. O mapa, os indicadores e as bases territoriais funcionam sem internet; o fundo OpenStreetMap é opcional. As bases são carregadas de arquivos locais conforme a seleção.

## Recorte e disponibilidade

- Estados: Acre, Amazonas, Pará e Rondônia.
- Seletor único de mês e intervalo: julho a outubro de 2026, mês inteiro ou dias 1–10, 11–20 e 21–fim. Outubro parcial até 14/10/2026 (UTC). Gráficos mostram os três intervalos do mês selecionado, sem janela temporal separada.
- Focos: INPE, somente AQUA_M-T, referência comparável entre períodos. Decêndios 1–10, 11–20 e 21–fim. Detecções não são contagens de incêndios.
- Cicatrizes mensais: MapBiomas Monitor do Fogo até setembro de 2026, asset com escala nominal de 30 m, confirmada na consulta Earth Engine.
- Cicatrizes com data estimada por pixel: NASA MODIS MCD64A1 v6.1, nominal 500 m, disponíveis até agosto de 2026. Incluídos julho e agosto. Setembro e outubro permanecem N/D, sem preenchimento artificial.
- MapBiomas é mensal e não foi desagregado em decêndios. MODIS é outro produto, com maior tamanho de pixel e incerteza de data; suas áreas não devem ser somadas nem comparadas como uma única série com MapBiomas.
- Outubro D1 completo, D2 parcial e D3 futuro. Sem fonte é N/D; ausência de detecção num produto disponível é zero.

## Outubro parcial — focos por estado

| UF | Focos AQUA_M-T |
|---|---:|
| AC | 575 |
| AM | 1639 |
| PA | 5549 |
| RO | 215 |

