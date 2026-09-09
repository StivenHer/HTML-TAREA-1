# Manual del proyecto HTML Tarea 1 y Tarea 3

## Descripción

En este proyecto se crearon diferentes páginas web a partir de imágenes de
referencia. Cada página fue desarrollada únicamente con HTML y conserva el
nombre numérico del ejercicio correspondiente.

Todos los documentos cuentan con la estructura básica de HTML, metadatos en la
cabecera y una indentación de 2 espacios.

## Estructura básica utilizada

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="author" content="Tu nombre completo">
  <meta name="keywords" content="palabras relacionadas con la página">
  <meta name="description" content="descripción de la página">
  <title>imagen1</title>
</head>
<body>
  <!-- Contenido de la página -->
</body>
</html>
```

## Trabajo realizado en cada página

### 1.html

Se creó una receta de berenjenas fritas. Se utilizaron títulos, párrafos y
saltos de línea para organizar los ingredientes y la preparación.

### 2.html

Se creó una página personal con una lista numerada de enlaces favoritos.

### 3.html

Se trabajaron listas anidadas. Dentro del primer elemento de una lista numerada
se agregó una lista secundaria con viñetas.

### 4.html

Se creó una página de noticias sobre programas educativos. Se utilizaron
títulos de diferentes niveles, párrafos, texto en negrita y texto en cursiva.

### 5.html

Se creó una lista de destinos turísticos. Los países aparecen en una lista
principal y las ciudades se organizaron en listas numeradas secundarias.

### 6.html

Se creó una página personal con enlaces externos que permiten visitar Google,
Aldea Global y un manual de HTML.

### Punto 7

No se creó `7.html` porque la imagen de referencia no era legible. En su lugar,
se agregó `7.html` al archivo `.gitignore` para evitar que Git lo incluya si se
crea accidentalmente.

### 8.html

Se creó una página de conciertos que utiliza las imágenes locales
`concert_logo.png` y `concert.jpg.jpg`.

### 9.html

Se construyeron dos tablas para mostrar las llegadas y salidas de un aeropuerto.
Las tablas contienen encabezados, filas, columnas y bordes.

### 10.html

Se creó una página de recetas con un logotipo, enlaces, una lista de
ingredientes y una lista numerada para explicar la preparación.

### 11.html

Se desarrolló un formulario de registro con campos de texto, correo, edad,
género, lista desplegable, comentarios, aceptación de condiciones y botón de
registro.

### 12.html

Se agregó un reproductor de audio con controles. El archivo utilizado es
`audio.mp3` y su creador es Djmks.

### 13.html

Se agregó un reproductor de video con controles. El archivo utilizado es
`video.mp4` y su creador es TBIT.

## Etiquetas utilizadas y su función

| Etiqueta | Función |
| --- | --- |
| `<!DOCTYPE html>` | Indica que el documento utiliza HTML5. |
| `<html>` | Contiene todo el documento HTML. |
| `<head>` | Guarda la información de configuración que no aparece directamente en la página. |
| `<meta>` | Define datos como la codificación, el autor, las palabras clave y la descripción. |
| `<title>` | Establece el título que aparece en la pestaña del navegador. |
| `<body>` | Contiene todos los elementos visibles de la página. |
| `<header>` | Representa el encabezado de una página o sección. |
| `<main>` | Contiene el contenido principal de la página. |
| `<footer>` | Representa el pie de página. |
| `<h1>` | Define el título principal. |
| `<h2>` y `<h3>` | Definen títulos secundarios y subtítulos. |
| `<p>` | Crea un párrafo. |
| `<br>` | Realiza un salto de línea. |
| `<b>` | Muestra el texto en negrita. |
| `<i>` | Muestra el texto en cursiva. |
| `<ol>` | Crea una lista numerada. |
| `<ul>` | Crea una lista con viñetas. |
| `<li>` | Representa un elemento dentro de una lista. |
| `<a>` | Crea un enlace mediante el atributo `href`. |
| `<img>` | Inserta una imagen mediante el atributo `src`. |
| `<table>` | Crea una tabla. |
| `<tr>` | Crea una fila dentro de una tabla. |
| `<th>` | Crea una celda de encabezado en una tabla. |
| `<td>` | Crea una celda de datos en una tabla. |
| `<form>` | Agrupa los controles de un formulario. |
| `<label>` | Describe el dato que debe ingresar el usuario. |
| `<input>` | Crea campos de texto, correo, números, opciones y casillas. |
| `<select>` | Crea una lista desplegable. |
| `<option>` | Define una opción dentro de una lista desplegable. |
| `<textarea>` | Crea un campo para escribir textos largos. |
| `<button>` | Crea un botón. |
| `<audio>` | Inserta un reproductor de audio. |
| `<video>` | Inserta un reproductor de video. |
| `<source>` | Indica la ubicación y el tipo de un archivo multimedia. |

## Atributos importantes

| Atributo | Función |
| --- | --- |
| `lang="es"` | Indica que el contenido está escrito en español. |
| `charset="UTF-8"` | Permite mostrar correctamente tildes y caracteres especiales. |
| `href` | Indica el destino de un enlace. |
| `src` | Indica la ubicación de una imagen, audio o video. |
| `alt` | Proporciona una descripción alternativa de una imagen. |
| `controls` | Muestra los controles de reproducción de audio o video. |
| `type` | Indica el tipo de campo o formato multimedia. |
| `id` | Identifica un elemento de manera única. |
| `name` | Asigna un nombre al dato enviado desde un formulario. |
| `placeholder` | Muestra un ejemplo dentro de un campo. |

## Cómo ejecutar el proyecto

1. Abrir la carpeta del proyecto en Visual Studio Code.
2. Seleccionar cualquiera de los archivos `.html`.
3. Abrir el archivo en el navegador o utilizar la extensión Live Server.
4. Verificar que las imágenes, el audio y el video estén en la misma carpeta y
   tengan exactamente el mismo nombre escrito en el código.

El proyecto no necesita instalaciones ni dependencias adicionales.

## Control de versiones y publicación

El proyecto se administró con Git y se publicó en dos repositorios remotos:
GitHub y GitLab. Los archivos y commits son los mismos, pero cada plataforma
tiene un nombre de remoto diferente.

### Creación de la llave SSH

Antes de conectar el proyecto con GitLab, se creó una llave SSH desde
PowerShell con el siguiente comando:

```powershell
ssh-keygen -t ed25519 -C "correo@ejemplo.com"
```

Después de ejecutar el comando, se presionó `Enter` para utilizar la ubicación
propuesta. También se podía escribir una contraseña para proteger la llave.

La llave pública se copió con este comando:

```powershell
Get-Content $env:USERPROFILE\.ssh\id_ed25519.pub | Set-Clipboard
```

El contenido copiado se agregó en la sección de llaves SSH de la cuenta de
GitLab. Solamente se debe compartir el archivo `id_ed25519.pub`; la llave
privada `id_ed25519` nunca se debe compartir, publicar ni subir al repositorio.

Debido a que la conexión por el puerto 22 estaba bloqueada, se comprobó la
conexión de GitLab mediante el puerto alternativo 443:

```powershell
ssh -T -p 443 git@altssh.gitlab.com
```

La primera vez apareció una solicitud para confirmar la identidad del servidor.
Después de verificar que se trataba de GitLab, se escribió `yes`.

### Configuración de los repositorios remotos

Primero se revisaron los repositorios configurados:

```powershell
git remote -v
```

El repositorio de GitHub ya estaba registrado con el nombre `origin`. Luego se
agregó el repositorio de GitLab con el nombre `gitlab` y usando el puerto 443:

```powershell
git remote add gitlab ssh://git@altssh.gitlab.com:443/stiven.hernandez.pere/html-tarea-1.git
git remote -v
```

En este proyecto, los remotos quedaron organizados de esta manera:

- `origin`: repositorio de GitHub.
- `gitlab`: repositorio de GitLab.
- `main`: rama principal del proyecto.

### Guardar y publicar modificaciones

Después de modificar un archivo en Visual Studio Code, los cambios se guardan
en Git mediante los siguientes comandos:

```powershell
git status
git add .
git commit -m "Actualizar proyecto"
```

Para publicar únicamente en GitHub se utiliza:

```powershell
git push origin main
```

Para publicar únicamente en GitLab se utiliza:

```powershell
git push gitlab main
```

Para publicar los mismos cambios en las dos plataformas se ejecutan ambos
comandos:

```powershell
git push origin main
git push gitlab main
```

Al realizar la primera publicación en GitLab no fue necesario crear otro commit,
porque el commit que ya se había enviado a GitHub también estaba guardado en el
repositorio local. Un mismo commit puede enviarse a varios repositorios remotos.

## Créditos de recursos

- Audio creado por Djmks.
- Video creado por TBIT.
- `concert_logo.png`: recurso de Vecteezy creado por Andres Ramos. Requiere
  atribución según la licencia gratuita de Vecteezy.
- `concert.jpg.jpg`: imagen proveniente de Pexels y obtenida mediante un artículo
  de Radio Nacional de Colombia. Utilizada de acuerdo con la licencia gratuita
  de Pexels.
- Las demás imágenes deben incluir su autor, enlace original y licencia de uso.

## Autor del proyecto

Stiven Hernandez