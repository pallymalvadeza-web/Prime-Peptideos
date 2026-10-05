# Lista de preços online (edita pelo Google Planilhas)

Você edita os produtos numa planilha do Google (inclusive pelo celular) e a página atualiza sozinha.

## Passo a passo
1. **Planilha:** crie uma planilha em planilhas.google.com. Na linha 1 coloque os títulos: `Marca/Categoria`, `Produto`, `Preço (R$)`. Preencha os produtos a partir da linha 2 (preço só número, ex.: 199,90).
2. **Publicar:** menu **Arquivo > Compartilhar > Publicar na Web**. Escolha a aba da lista, formato **Valores separados por vírgulas (.csv)** e clique em **Publicar**. Copie o link.
3. **Colar o link:** abra `config.js`, cole o link em `planilhaCsv: "..."`. Preencha também o WhatsApp, se quiser o botão de pedir.
4. **Hospedar a página:** envie `index.html` e `config.js` para um site gratuito (GitHub Pages ou Netlify Drop, arrastando a pasta em app.netlify.com/drop).
5. **Atualizar preços:** é só editar a planilha. A página mostra a mudança em alguns minutos (o Google leva um tempo para atualizar a publicação).

## Observação
O responsável pela lista responde pelo conteúdo publicado. Confira se todos os produtos podem ser vendidos legalmente.
