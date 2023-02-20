# Exemplo de como criar layouts com CSS3 e HTML5

![GitHub repo size](https://img.shields.io/github/repo-size/JaimeMS/HTML5-CSS3?style=plastic)

Exemplos simples de como criar layouts com HTML5 e CSS3 usando três técnicas diferentes
- float
- flex box
- grid

# HTML5 e CSS3

![HTML5 e CSS3](https://github.com/JaimeMS/JaimeMS/blob/main/img/HTML5-e-CSS3-1024x576.jpg) 

## Site de referência
* [W3Schools](https://www.w3schools.com/default.asp)

## Formas de trabalhar com CSS
* Inline
```
	<p style="font-family: Arial, Helvetica, sans-serif;"></p>
```
* Incorporado
```
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Exemplo 2</title>
	<style type="text/css">		
		.cabecalho h1 {
			font-family:Arial, Helvetica, sans-serif; 
			padding: 15px;
			text-align: center;
			background-color: #888;
		}
	</style>
</head>
<body>
	<main role="main" class="container">
		<header class="cabecalho">
			<h1>Cabeçalho</h1>
		</header>
	</main>
</body>
</html>
```
* Arquivo exteno
```
 <link rel="StyleSheet" href="css/meuCss.css" type="text/css" />
```

## Importar um arquivo CSS dentro de outro arquivo CSS
```
@import url('meuCss.css');
```

## Padronização da W3C
- Site utilizado para verificar o estágio que determinada tecnologia se encontra
[Can I use](https://caniuse.com/)

## Prefixos Proprietários
| Prefixo  | Motor de Renderização   |
| -------  | -------- |
| -webkit- | WebKit    |
| -moz-    | Mozilla Foundation        |
| -o-      | Opera   |
| -ms-     | Trident (a.k.a MSHTML)    |
 

