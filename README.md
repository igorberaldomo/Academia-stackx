Esse é um SPA (single page aplication) em react + node que contém 4 elemento o header, o content, a imagem e o footer

para ver a pagina web

0º npm install

1º cd ./academia-stackx

2º npm run start

no terminal
npm install gh-pages --save-dev

alterar uuupackage.json
{
  "homepage": "https://https://igorberaldomo.github.io/Academia-stackx/",
  ...,
  "scripts": {
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build",
    ...
  }
}

no terminal:
    npm run deploy

no github:  
    no Settings-> Pages
        Branch
            select gh-pages /root 
            click save

    reload Settings->Pages
        get link in visit your site