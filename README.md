# Html e CSS

## Estrutura base de um arquivo HTML

```html
<!DOCTYPE html>
<html lang="PT-BR">
    <head>
        <title>
            Pagina de exemplo estrutura basica
        </title>
        <meta charset="utf-8">
        <meta name="author" content="Luis">
        <meta name="description" content="lista de documentos">
        <meta name="keywords" content="html5">
    </head>
    <body>

    </body>
</html>
```

## Formatando fontes

```html
      <style>
            h1{
                font-family: Arial, Helvetica, sans-serif;
                font-size: 40px;
                font-style: normal;
                font-variant: small-caps; /*usado para deixar o texto como se fosse Maiúsculas */
                color: black; /*Pode ser cor ou valor Hexadecimal ex. #000000*/
            }
            p{
                font-variant: small-caps;
                text-align: left;
                text-decoration: line-through;/*Faz um risco no texto*/
                text-indent: 20px; /*Margin inicial do parágrafo*/
                text-transform: lowercase;
            }
     </style>
```

## Propriedades display

## Display block
Ocupa 100% da area disponível e gerando quebra de linha, ficando sempre um embaixo do outro
```html
Display block

    <p>
    <h1><h2><h3><h4><h5><h6>
    <div>
    <ul>, <ol>,<li>
    <footer>       
```

## Display inline
Não gera quebra de linha, ficam todos na mesma linha, ocupando sempre a largura necessaria da TAG
```html
Display inline

    <a>
    <strong>,<b>
    <em>, <i>
    <span>
    <img>       
```