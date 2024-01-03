#### .Prettierrc

#### Install Prettier
```
npm install --save-dev --save-exact prettier
```
ou
```
yarn add --dev --exact prettier
```
ou
```
# Vá em Extensions ( CTRL + Shift + C ) no VSCode e pesquise por Prettier ( Você deve instalar o Prettier - Code formatter )
# Após a instalaçao:

# 1º passo:
# Aperte na Engrenagem ( lado esquerdo inferior do VSCode ) -> Settings -> Pesquise por Default formatter -> Escolha o prettier

# 2º passo:
# Pesquiser por Format on save -> Selecione para ativar 
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

