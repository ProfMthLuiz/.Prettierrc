#### .Prettierrc

#### Install Prettier
```
npm install --save-dev --save-exact prettier
```
ou
```
yarn add --dev --exact prettier
```

#### Crie um arquivo em seu diretório chamado .Prettierrc
- Conteúdo do arquivo
```
  {
    "singleQuote": true,
    "semi": false,
    "tabWidth": 2,
    "trailingComma": "all",
    "printWidth": 80
  }
```
- <strong>singleQuote:</strong> <i>Use aspas simples em vez de duplas.</i>
- <strong>semi:</strong> <i>Não adicione ponto e vírgula no final das linhas.</i>
- <strong>tabWidth:</strong> <i>Use dois espaços para indentação.</i>
- <strong>trailingComma:</strong> <i>Adicione vírgula no final dos objetos e arrays.</i>
- <strong>printWidth:</strong> <i>Limite de caracteres por linha.</i>


<br>
<br>
<strong>**Saiba mais sobre as configurações do Prettier em seu site oficial:</strong> https://prettier.io/docs/en/options

