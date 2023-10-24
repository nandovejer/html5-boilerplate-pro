# HTML5 boilerplate como un Profesional

**Estructura de una documento**

1. DOCTYPE
2. HTML
3. HEAD
4. BODY

## DOCTYPE

La declaración `<!DOCTYPE>` no es una etiqueta en el sentido tradicional, sino una instrucción para el navegador web sobre la versión de HTML que el documento está utilizando. Esto ayuda al navegador a renderizar el contenido correctamente de acuerdo con las especificaciones de esa versión particular de HTML.

Las declaraciones `<!DOCTYPE>` no tienen atributos como las otras etiquetas en HTML. Solo hay una declaración `<!DOCTYPE>` permitida y debe ser la primera cosa en el documento HTML, antes del elemento `<html>`.

A lo largo de los años, las diferentes versiones de HTML han tenido diferentes declaraciones `<!DOCTYPE>`. Aquí hay algunos ejemplos:

- **HTML 5**: `<!DOCTYPE html>`
- **HTML 4.01 Strict**: `<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">`
- **HTML 4.01 Transitional**: `<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">`
- **HTML 4.01 Frameset**: `<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN" "http://www.w3.org/TR/html4/frameset.dtd">`
- **XHTML 1.0 Strict**: `<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">`
- **XHTML 1.0 Transitional**: `<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">`
- **XHTML 1.0 Frameset**: `<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Frameset//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-frameset.dtd">`
- **XHTML 1.1**: `<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN" "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">`

## HTML

El elemento `<html>` es el elemento raíz de un documento HTML. Los atributos principales que puedes utilizar con la etiqueta `<html>` son:

- **lang**:
  Este atributo define el idioma principal del documento. Ejemplo: `<html lang="es">`

- **dir**:
  Este atributo define la dirección del texto en el documento, ya sea de izquierda a derecha (`ltr`) o de derecha a izquierda (`rtl`).Ejemplo: `<html dir="ltr">`

- **prefix**: Este atributo se utiliza para definir los prefijos de espacio de nombres que se utilizarán en el documento. Ejemplo: `<html prefix="og: http://ogp.me/ns#">`

- **xml:lang**: Similar al atributo `lang`, pero utilizado en documentos XHTML.
  Ejemplo: `<html xml:lang="es">`

- **class**: Aunque no es común, el atributo `class` también puede ser utilizado en la etiqueta `<html>` para aplicar estilos. Ejemplo: `<html class="mi-clase">`

- **id**: Similar al atributo `class`, el atributo `id` también puede ser utilizado en la etiqueta `<html>`. Ejemplo: `<html id="mi-id">`

- **style**: Este atributo permite aplicar estilos en línea al elemento `<html>`. Ejemplo: `<html style="background-color:blue;">`

- **title**: Aunque no es común, y no es una práctica recomendada, el atributo `title` también puede ser utilizado en la etiqueta `<html>`. Ejemplo: `<html title="Título">`

## BODY

El elemento `<body>` en HTML representa el contenido principal de un documento HTML. Aquí hay una lista de algunos atributos que se pueden utilizar con la etiqueta `<body>`, junto con ejemplos de cada uno:

- **style**: Define estilos en línea para el elemento `<body>`. Ejemplo: `<body style="background-color:blue;">`

- **class**:Asigna una o más clases al elemento `<body>`. Ejemplo: `<body class="mi-clase">`

- **id**: Asigna un identificador único al elemento `<body>`. Ejemplo: `<body id="mi-id">`

- **onload**: Define un script para ser ejecutado cuando la página ha terminado de cargar. Ejemplo: `<body onload="miFuncion()">`

- **onunload**: Define un script para ser ejecutado cuando la página está a punto de ser descargada. Ejemplo: `<body onunload="miFuncion()">`

- **onafterprint**: Define un script para ser ejecutado después de que el documento haya sido impreso. Ejemplo: `<body onafterprint="miFuncion()">`

- **onbeforeprint**: Define un script para ser ejecutado antes de que el documento sea impreso. Ejemplo: `<body onbeforeprint="miFuncion()">`

- **onbeforeunload**: Define un script para ser ejecutado antes de que la página esté a punto de ser descargada. Ejemplo: `<body onbeforeunload="miFuncion()">`

## HEAD, la etiqueta clave

1. Title
2. Meta tags
3. Link
4. Script

### Title

La etiqueta `<title>` en HTML es utilizada para definir el título del documento, que es el texto que se muestra en la pestaña del navegador o en la barra de título, dependiendo del navegador. También es utilizado por los motores de búsqueda para determinar el título de la página en los resultados de búsqueda.

```html
<title>Título de la Página</title>
```

### Meta Tags

Las metaetiquetas (metatags) en HTML proporcionan información sobre la página web a los navegadores y a los motores de búsqueda. Aunque hay muchas metaetiquetas, algunas son más cruciales que otras para el SEO (Optimización de Motores de Búsqueda) y la funcionalidad básica del site.

#### Meta Charset

```html
<meta charset="UTF-8" />
```

Especifica la codificación de caracteres utilizada en la página, lo cual es crucial para la correcta visualización del contenido.

#### Meta Viewport

```html
<meta name="viewport" content="width=device-width, initial-scale=1" />
```

Controla cómo se debe escalar la página en diferentes dispositivos, esencial para el diseño responsivo.

#### Meta Description

```html
<meta name="description" content="Descripción de la página" />
```

Estas etiquetas son vitales para el SEO y ayudan a los motores de búsqueda a entender de qué trata la página.

#### Meta Keywords

```html
<meta name="keywords" content="palabra1, palabra2, palabra3" />
```

Aunque ya no es tan relevante para el SEO, permite especificar palabras clave relacionadas con el contenido de la página.

#### Meta Robots

```html
<meta name="robots" content="index,follow" />
```

Instruye a los motores de búsqueda sobre cómo deben indexar y seguir los enlaces en la página.

#### Meta Author

```html
<meta name="author" content="Nombre del Autor" />
```

Proporciona información sobre el autor de la página.

#### Meta Refresh

```html
<meta http-equiv="refresh" content="30" />
```

Se utiliza para refrescar automáticamente la página después de un cierto período de tiempo.

#### Meta Language

```html
<meta http-equiv="content-language" content="es" />
```

Indica el idioma principal de la página.

#### Meta Open Graph y Twitter Card

```html
...
```

Ayudan a controlar cómo se muestra el contenido en las plataformas de redes sociales cuando se comparte una página.

#### Geo-Tagging

```html
<meta name="geo.region" content="US-TX" />
<meta name="geo.placename" content="Houston" />
<meta name="geo.position" latitude;longitude"> <meta name="ICBM"
latitude;longitude">
```

Proveen información sobre la ubicación geográfica relacionada con tu sitio web o páginas individuales, lo que puede ayudar en las clasificaciones de búsqueda local y permitir una mejor orientación para las consultas geográficamente relevantes.

#### Indexed/Archived MetaTag

```html
<meta name="googlebot" content="index, follow, available_after2023-12-01" />
```

Permite especificar un rango de fechas en el que los motores de búsqueda pueden indexar o archivar tu página web, lo cual puede ser útil para promociones temporales, contenido sensible al tiempo, o cualquier instancia donde la indexación más allá de una fecha específica sea desfavorable.

#### MetaTheme Color

```html
<meta name="theme-color" content="#ffffff" />
```

Utilizada para especificar el color del tema de la página web en los navegadores móviles.

#### MetaRating

```html
<meta name="rating" content="general" />
```

Utilizada para especificar la clasificación de edad del contenido de la página.

#### MetaGenerator

```html
<meta name="generator" content="WordPress 5.8" />
```

A veces utilizada para indicar el software utilizado para crear la página.

#### MetaRevisit-After

```html
<meta name="revisit-after" content="30 days" />
```

Sugerencia para los motores de búsqueda sobre cuándo deben volver a visitar la página para la indexación.

#### MetaAbstract

```html
<meta name="abstract" content="Resumen de la página" />
```

Proporciona un resumen breve del contenido de la página.

#### Copyright

```html
<meta name="copyright" content="Nombre del Autor" />
```

Indica el derecho de autor de la página.

#### MetaDesigner

```html
<meta name="designer" content="Nombre del Diseñador" />
```

Indica el diseñador de la página o el sitio web.

#### MetaIdentifier-URL

```html
<meta name="identifier-URL" content="https//www.ejemplo.com" />
```

URL única y permanente que se asigna a la página.

#### MetaApplication-name

```html
<meta name="application-name" content="Nombre de la Aplicación" />
```

Esta metaetiqueta especifica el nombre de la aplicación web si el sitio web es una aplicación web.

#### MetaGenerator

```html
<meta name="generator" content="WordPress 5.6" />
```

Esta metaetiqueta puede ser utilizada para especificar el software o editor utilizado para crear la página.

#### MetaGoogle-site-verification

```html
<meta name="google-site-verification" content="código_de_verificación" />
```

Utilizada para verificar la propiedad del sitio web en la consola de búsqueda de Google.

#### MetaMsvalidate

```html
<meta name="msvalidate.01" content="código_de_verificación" />
```

Similar a la de verificación de Google, pero para la herramienta Bing Webmaster Tools.

#### MetaPdomain_verify

```html
<meta name="pdomain_verify" content="código_de_verificación" />
```

Utilizada para verificar la propiedad del sitio web en Pinterest.

#### MetaTheme-color

```html
<meta name="theme-color" content="#color_hex" />
```

Esta metaetiqueta especifica el color del tema de la barra de direcciones en los navegadores móviles.

#### MetaTwittercard

```html
<meta name="twittercard" content="summary" />
```

Utilizada para especificar cómo se mostrará el contenido del sitio web cuando se comparta en Twitter.

#### MetaTwittersite

```html
<meta name="twittersite" content="@nombre_de_usuario" />
```

Especifica la cuenta de Twitter del propietario del sitio web.

#### MetaFormat-detection

```html
<meta name="format-detection" content="telephone=no" />
```

Controla la detección de formato, como la detección de números de teléfono.

#### MetaX-UA-Compatible

```html
<meta http-equiv="X-UA-Compatible" content="IE=edge" />
```

Utilizada para especificar la versión de Internet Explorer en la que el sitio web debe ser renderizado.

### Link

El elemento `<link>` en HTML es utilizado para establecer relaciones entre el documento actual y otros recursos externos. Aquí hay varios tipos de relaciones que puedes especificar usando el atributo rel junto con el elemento `<link>`, cada uno con su respectivo

#### Link Canonical

```html
<link rel="canonical" href="URL_CANÓNICA" />
```

Ayuda a evitar contenido duplicado señalando la versión "oficial" de una página a los motores de búsqueda.

#### Stylesheet (Hoja de estilo)

```html
<link rel="stylesheet" href="styles.css" />
```

Para vincular una hoja de estilo externa.

#### Alternate (Alternativo)

```html
<link rel="alternate" hreflang="es" href="pagina-es.html" />
```

Para proporcionar una versión alternativa del documento, como una versión en otro idioma o formato.

#### favicon

```html
<link rel="icon" href="favicon.ico" type="image/x-icon" />
```

Para especificar un icono para el documento, como un favicon.

#### Preload

```html
<link rel="preload" href="font.woff2" as="font" type="font/woff2" crossorigin />
```

Para precargar recursos específicos.

#### Prefetch

```html
<link rel="prefetch" href="page2.html" />
```

Para cargar en segundo plano recursos que se utilizarán en la próxima navegación.

#### Next

```html
<link rel="next" href="page3.html" />
```

Para indicar la ubicación del siguiente documento en una secuencia de documentos.

#### Prev

```html
<link rel="prev" href="page1.html" />
```

Para indicar la ubicación del documento anterior en una secuencia de documentos.

#### Search

```html
<link
  rel="search"
  href="/open-search.xml"
  type="application/opensearchdescription+xml"
/>
```

Para vincular a un documento que describe la herramienta de búsqueda para el sitio.

#### Author

```html
<link rel="author" href="author.html" />
```

Para vincular a un documento que proporciona información sobre el autor del documento.

#### License

```html
<link rel="license" href="license.txt" />
```

Para vincular a un documento que describe la licencia bajo la cual se proporciona el contenido.

#### Help

```html
<link rel="help" href="help.html" />
```

Para vincular a un documento que proporciona ayuda sobre el documento.

### Script

El elemento `<script>` en HTML se utiliza para incrustar o referenciar código ejecutable, generalmente JavaScript, en un documento HTML. Hay varios tipos y usos para el elemento `<script>` dependiendo de los atributos y la posición en el documento. Aquí se presentan algunos de ellos junto con ejemplos:

#### Script Incrustado

```html
<script type="text/javascript">
  alert("¡Hola, Mundo!");
</script>
```

Un script que está directamente dentro del documento HTML.

#### Script Externo

```html
<script type="text/javascript" src="script.js"></script>
```

Un script que se referencia desde un archivo externo.

#### Script Asíncrono

```html
<script type="text/javascript" src="script.js" async></script>
```

Un script que se ejecutará de forma asíncrona tan pronto como esté disponible.

#### Script Diferido

```html
<script type="text/javascript" src="script.js" defer></script>
```

Un script que se ejecutará después de que el documento haya sido completamente parseado.

#### Script en línea

```html
<button onclick="alert('¡Hola, Mundo!');">Haz clic en mí</button>
```

Un evento que desencadena la ejecución de un script.

#### Script de Módulo

```html
<script type="module">
  import { funcion } from "./modulo.js";
  funcion();
</script>
```

Un script que se trata como un módulo y puede importar otros módulos.

#### Script NOSCRIPT

```html
<noscript>
  Este sitio web requiere JavaScript para funcionar correctamente.
</noscript>
```

Un mensaje o contenido alternativo que se mostrará si el scripting está deshabilitado en el navegador.

#### Script JSON-LD (JavaScript Object Notation for Linked Data)

```html
<script type="application/ld+json">
  {
    "@context": "http://schema.org",
    "@type": "Person",
    "name": "John Doe",
    "jobTitle": "Graduate research assistant"
  }
</script>
```

Un script utilizado para incrustar datos estructurados en una página.

#### Script de Plantilla (Template)

```html
<script type="text/x-handlebars-template" id="template">
  <div>{{mensaje}}</div>
</script>
```

Un script que contiene una plantilla que será procesada por código JavaScript.
