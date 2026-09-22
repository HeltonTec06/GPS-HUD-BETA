# GTA GAME GPS V17

Versão de teste do GPS gamer com câmera 3D adaptativa para celular, tablet e computador.

## Google 3D opcional

A V17 possui um ponto de integração opcional com o **Google Maps 3D / Photorealistic 3D** para a pequena cena de início da rota. O HTML contém `GOOGLE_3D_API_KEY` vazio por padrão.

Para ativar:
1. Crie um projeto no Google Cloud.
2. Ative a API necessária para Maps JavaScript / 3D Maps e configure faturamento conforme as regras do Google.
3. Crie uma chave com restrição por HTTP referrer para o domínio do GitHub Pages.
4. Coloque a chave no campo `GOOGLE_3D_API_KEY` do `index.html`.
5. Publique novamente.

Não extraia, baixe ou faça scraping de dados do Google Earth. A integração usa somente as APIs oficiais e deve manter as atribuições exigidas pelo Google.

Sem chave, o app usa a câmera 3D nativa do MapLibre como fallback.
