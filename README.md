# Atlas da Infraestrutura

Mapa interativo da infraestrutura de transporte no Brasil, organizado por modal.

## Visualização

A página permite consultar feições do OpenStreetMap por área do mapa e filtrar:

- Rodovias principais
- Ferrovias
- Hidrovias
- Portos e terminais
- Aeródromos

Aproxime o mapa até uma região ou município, marque os modais e clique em **Buscar na área do mapa**. Clique nas feições para abrir uma ficha com os atributos disponíveis. Os dados são colaborativos e sua cobertura varia; não constituem inventário oficial ou completo.

## Publicação

O workflow em `.github/workflows/pages.yml` publica o conteúdo no GitHub Pages a cada atualização da branch `main`. Na primeira publicação, confirme em **Settings → Pages** que a origem de publicação está definida como **GitHub Actions**.

## Fontes

- Mapa base e feições: [OpenStreetMap](https://www.openstreetmap.org/copyright)
- Busca de localidades: [Nominatim](https://nominatim.org/)
- Consulta das feições: [Overpass API](https://wiki.openstreetmap.org/wiki/Overpass_API)

A aplicação é estática; os serviços públicos do OpenStreetMap são consultados diretamente pelo navegador.
