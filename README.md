# Junior Machado Fotografia

Site de portfólio do fotógrafo Junior Machado (Florianópolis). Página única em HTML e CSS puros, sem build: é só abrir o `index.html` ou publicar a pasta em qualquer hospedagem estática (GitHub Pages, Vercel, Netlify).

## Estrutura

```
index.html              página completa (textos, estilos e scripts)
assets/portfolio/       fotos do portfólio, 2048 px no lado maior
assets/junior-about.jpg foto da praia da seção Sobre (ainda falta adicionar)
```

As fotos de `assets/portfolio/` têm o nome da categoria na frente:
`campanha-`, `gastronomia-`, `eventos-`, `shows-`, `esporte-`, `retratos-`, `bastidores-`.

## Publicar no GitHub Pages

Settings → Pages → Source: *Deploy from a branch* → branch `main`, pasta `/ (root)`.

## Pendências

- **Foto do Sobre:** salvar a foto da praia como `assets/junior-about.jpg`. Enquanto ela não estiver lá, o carrossel mostra só a foto dos bastidores.
- **Fotos que faltam no portfólio (7):** Show & Festivais (JRM_2744, DSC_7346, DSC_7137, JRM_9864, JRM_8572, JRM_4780) e Retratos (DSC_8138). Reduzir para 2048 px, salvar em `assets/portfolio/` e acrescentar um `<figure class="card">` na fileira da categoria, igual aos outros.
- **Logos das marcas:** a faixa de marcas mostra os nomes escritos. Para trocar pelos logos, salvar os SVGs em `assets/logos/` e substituir cada `<span class="brand">` por um `<img>`.

## Contatos usados no site

- WhatsApp: (48) 98867-1837 (`https://wa.me/5548988671837`)
- Instagram: @juniormachadofotografo
- E-mail: photojrmachado@gmail.com
