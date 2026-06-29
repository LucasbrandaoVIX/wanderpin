# wanderpin 🌍📍

Um mapa pessoal das suas viagens — coloque pins nas cidades que já visitou e veja os países que conheceu pintados com a própria bandeira (bem suave).

App de arquivo único: é só abrir o `index.html` no navegador. Sem instalação, sem build.

## Funcionalidades

- **Buscar cidade** com autocomplete (sugestões enquanto digita) — cai um pin com a bandeira do país.
- **Duplo-clique no mapa** para marcar um ponto manualmente.
- **Países visitados** ganham a própria bandeira como fundo, bem translúcida.
- **Clusters por país**: bolinhas amontoadas do mesmo país viram uma bolha maior com a contagem.
- **Declutter entre países**: pins de países diferentes que se sobrepõem se afastam automaticamente.
- **Centros turísticos** ganham pin maior com anel dourado e ⭐.
- **Lista lateral** com tudo agrupado por país, contadores e remoção rápida.
- Tudo salvo no navegador (`localStorage`) — fecha e abre depois sem perder nada.

## Como usar

Abra o `index.html` em qualquer navegador. Requer conexão com a internet para os tiles do mapa, busca de cidades (Nominatim/OpenStreetMap) e imagens de bandeira (flagcdn).

## Stack

- [Leaflet](https://leafletjs.com/) + tiles escuros da CARTO
- [Leaflet.markercluster](https://github.com/Leaflet/Leaflet.markercluster)
- Geocoding: [Nominatim](https://nominatim.org/) (OpenStreetMap)
- Contornos dos países: [Natural Earth](https://www.naturalearthdata.com/)
- Bandeiras: [flagcdn](https://flagcdn.com/)

## Licença

MIT
