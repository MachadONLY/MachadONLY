# PERU / ATLAS — mapa 3D de viagem (julho de 2027)

Mapa interativo do Peru para planejar uma viagem de casal: Cusco, Vale Sagrado, Ollantaytambo, Machu Picchu, Lima e Huacachina. Inclui datas V1 de 5 a 17 de julho, destinos adicionais, orçamento e controles de terreno 3D/satélite.

## Como visualizar
O site é 100% estático: abra `peru-atlas/index.html` em um navegador com internet. Para hospedar com GitHub Pages, crie um repositório próprio com este arquivo como `index.html` da raiz e configure **Settings → Pages → Deploy from a branch → main / root**. Alternativamente, publique esta pasta no Cloudflare Pages / Netlify.

## Estado da publicação
- Código publicado nesta branch `peru-atlas-v1` do repositório de perfil `MachadONLY/MachadONLY`.
- **GitHub Pages ainda não foi habilitado/validado.** A URL da branch do GitHub é fonte de código, não URL do site.
- Branch criada para não alterar a página de perfil nem projetos existentes.

## Informação geográfica e qualidade dos dados
- Os pinos usam coordenadas geográficas de referência para cidades e locais, em WGS84.
- O relevo vem de tiles raster de elevação (Mapterhorn), com exagero vertical 1×, visualizado pelo MapLibre GL.
- Fundo cartográfico © OpenStreetMap/CARTO; opção imagem © Esri.
- **Conexões no mapa são esquemáticas** e não seguem necessariamente a geometria real de rodovias, ferrovias ou corredores aéreos. Não use essas linhas para navegação. Os horários e datas não são bilhetes confirmados.
- Ollantaytambo ↔ Águas Calientes é trecho **ferroviário**; Águas Calientes ↔ Machu Picchu é **ônibus** (ou trilha).
- Machu Picchu Circuito 2-A/2-B é uma intenção pendente de ingresso; não se presume disponibilidade.

## Fontes para verificação
- https://maplibre.org/maplibre-gl-js/docs/examples/3d-terrain/
- https://www.perurail.com/train-schedules-and-frequencies/
- https://transparencia.mincetur.gob.pe/documentos/newweb/portals/0/transparencia/pmi/Anexo_criterio_priorizaci%C3%B3n_sectorial_Zona_desarrollo_tur%C3%ADstico_0425.pdf
- https://www.openstreetmap.org/copyright

## Próximo aprimoramento
Substituir segmentos esquemáticos por GeoJSON verificado dos serviços de transporte/rotas. Conferir disponibilidade comercial de cada hotel, passeio e passagem no calendário definitivo.
