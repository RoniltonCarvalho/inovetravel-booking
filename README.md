
# inovetravel (protótipo Booking-like)

Protótipo estático com busca de Voos e Hotéis priorizando os mais baratos.

- Frontend: React (UMD) + Tailwind via CDN (single `index.html`)
- Sem build step: basta abrir `index.html` no navegador ou publicar no GitHub Pages.

## Rodar localmente
Abra o arquivo `index.html` no navegador.

## Publicar no GitHub Pages
1. Crie um repositório no GitHub (ex.: `inovetravel`).
2. Envie os arquivos deste zip para a branch `main`.
3. Em Settings → Pages, selecione `Deploy from a branch` e aponte para `main`/root.
4. Acesse a URL exibida pelo GitHub Pages.

## Próximos passos
- Conectar APIs reais (Amadeus/Duffel/Skyscanner para voos; Expedia/Booking/HotelBeds para hotéis).
- Adicionar filtros (paradas, horários, políticas de cancelamento, avaliação, bairro etc.).
- Implementar autenticação e checkout.
