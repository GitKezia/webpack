# WebPack
Responsável pela separação de código. Utilizado, em frameworks, gerenciamento das dependências.

site: https://webpack.js.org

- Empacotador de módulos JS
- Utilizado por diversos frameworks modernos como React, Angular...
- Trabalha com o Node.js

## Instalação

1. Iniciar o projeto no diretório
```
npm init -y
```

2. Instalar o WebPack como dependência de desenvolvimento
```
npm install --save-dev webpack webpack-cli

npx webpack --config webpack.config.js

http-server nome da pasta com html
```

## Trabalhando com HTML
É necessário trabalhar com plugin para ampliar as possibilidades de uso, instalação:

```
npm install --save-dev html-webpack-plugin
```
## Adicionando CSS

Para trabalhar com estilos também compensa adicionar algumas extensões:

- node-sass: compilador de sass para node;
- sass-loader: carrega para o Webpack compilar;
- style-loader: injeta estilos na árvore de objetos (DOM);s
- css-loader: interpreta diretivas do CSS (import,..);
- extract: extrai CSS do JS.

´´´
npm install --save-dev node-sass sass-loader style-loader css-loader min-css-extract-plugin.

## Melhorando a compatibilidade do JS com Babel

Babel tranforma o código jS para uma versão com maior compatibilidade para navegadores antigos.

```
npm install --save-dev @babel/core @babel/preset-env babel-loader
```
## Trabalhando com imagens 
Adicionar file loader

```
npm install --save-dev file-loader
```

