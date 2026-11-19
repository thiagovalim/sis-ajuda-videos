# sis-ajuda-videos

Lista pública que liga cada guia da Central de Ajuda do Sis ao vídeo (ou à playlist) do canal
[SoftConn Sistemas](https://www.youtube.com/channel/UCgOVNk-1s3EbrZnOZO0h08A) no YouTube.

O sistema lê o `videos.json` deste repositório para acender o botão do YouTube no cabeçalho de cada tela e o
*Assistir* da Central de Ajuda — sem precisar de uma versão nova do sistema.

⛔ **Não edite à mão.** Este repositório é DERIVADO: a lista nasce no repositório do Sis, passa pela revisão e pelos
testes de lá, e é publicada aqui pelo `scripts/publicar-videos-da-ajuda.py publicar`.

Formato (`versao` 1):

```json
{ "versao": 1, "videos": [ { "guia": "caixa", "tipo": "video", "id": "AbCdEfGhIjK", "titulo": "…" } ] }
```

`tipo` é `video` ou `playlist`; um link por guia.
