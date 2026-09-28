# Buona Crema MAUÁ

Site estático feito com HTML, CSS e JavaScript puro. Não requer instalação de dependências nem etapa de build.

## Publicar pelo GitHub e Vercel

1. Extraia este ZIP.
2. Envie **o conteúdo desta pasta** para a raiz do repositório GitHub. O arquivo `index.html` deve aparecer na raiz, ao lado de `style.css`, `script.js` e `vercel.json`.
3. No Vercel, importe esse repositório e use a raiz do repositório como **Root Directory**.
4. Selecione **Other** como framework. Deixe o **Build Command** vazio; `vercel.json` define a raiz (`.`) como diretório publicado.

Depois da publicação, o endereço principal do projeto deve abrir `index.html`.

## Arquivos

- `index.html` — conteúdo do site e ilustração original em SVG inline.
- `style.css` — estilos e regras responsivas.
- `script.js` — navegação do menu em telas pequenas.
- `vercel.json` — configura a raiz do projeto como diretório estático publicado.

Não há imagens externas ou arquivos de imagem separados; a ilustração do gelato está incorporada no HTML para manter o caminho de assets simples.
