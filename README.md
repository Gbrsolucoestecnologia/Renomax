# Renomax Energia Solar — Landing Page

Site institucional de página única para a Renomax Energia Solar (Fortaleza/CE).

## Estrutura

```
index.html          → página completa (HTML + CSS + JS inline)
assets/img/          → imagens (logo, galeria, clientes, posters)
assets/video/        → vídeos (hero, institucional, depoimentos)
```

## Publicar com GitHub Pages

1. Vá em **Settings → Pages** neste repositório.
2. Em "Source", escolha **Deploy from a branch**.
3. Selecione a branch `main` e a pasta `/ (root)`.
4. Salve. O site fica disponível em `https://<usuario>.github.io/Renomax/` em alguns minutos.

Para usar um domínio próprio, configure os registros DNS do domínio apontando para o GitHub Pages e adicione o domínio em Settings → Pages → Custom domain.

## Visualizar localmente

Basta abrir `index.html` num servidor local (ex: `python3 -m http.server`) — não abra direto como arquivo, pois os vídeos não carregam via `file://`.
