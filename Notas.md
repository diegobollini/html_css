# HTML y CSS

```html
<!DOCTYPE html>
<html lang="es-AR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="wth=device-width, initial-scale=1.0">
    <title>Práctica HTML + CSS</title>
</head>
<body>
    
</body>
</html>
```

### Etiquetas básicas
<etiqueta>
- Texto: negrita, cursiva, títulos, párrafo, etc
- div (para crear "bloques invisibles")

### CSS
- Basico: <style></style> element have mainly the purpose of allowing for quick styling, for example for testing purposes
- Intermedio: etiqueta sytle en el head
```html
	<style type="text/css">
	    p {
	        color: midnightblue;
	    }
	    pre {
	        background-color: navajowhite;
	        color: navy;
	    }
	</style>
```
- Crack: archivo .css externo [<link rel="stylesheet" type="text/css" href="index-3.css">]

### Javascript
- linkear file.js al .html
- para test puede agregarse la etiqueta script

### Emmet extension (KE?)
Ejemplo: p{texto $}*4
```html
<p>texto 1</p>
<p>texto 2</p>
<p>texto 3</p>
<p>texto 4</p>
```

Ejemplo: h1{texto}
```html
<h1>texto</h1>
```

Ejemplo: h1+h2+h3+div
```html
<h1></h1>
<h2></h2>
<h3></h3>
<div></div>	
```

Ejemplo: p{párrafo test}>b{negrita}
```html
<p>párrafo test<b>negrita</b></p>
```

Ejemplo: p>b
```html
<p><b></b></p>
```
Ejemplo: h1+(p>b+b)+h2
```html
<h1></h1>
<p><b></b><b></b></p>
<h2></h2>
```

Ejemplo: a{click aca}+p{acá hay texto}
```html
<a href="">click aca</a>
<p>acá hay texto</p>
```

### Menús horizontales y verticales
- con listas
- con bloques aside, div, nav

### Listas
- desordenadas (no numeradas)
- ordenadas (numeradas)
- de definición

### Degradados (gradient)

### Sombras (x , y)
- de texto (text-shadow)
- de caja (box-shadow)

### Tablas
- fila = tr
- celda = td (table data, column)
- encabezado = th (table header)
- combinar celdas
	- rowspan --> filas
	- colspan --> columnas

### Fuentes de texto
[Google](fonts.google.com)
- Seleccionar fuente/s
	- Embed html: <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100&display=swap" rel="stylesheet">
	- CSS rules: font-family: 'Roboto', sans-serif;

### Favicon (head)
```html
<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
```

### Pseudo clases
- class --> objeto compartido
- id --> identificador único, sólo se utiliza una vez
