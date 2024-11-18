# HTML

Elaboración de documentos web mediante lenguajes de marcas
Código: UTF1841

## plugins que usaremos

- HTML CSS Support
- Auto Rename Tog
- Liver Server (ya estaba)
- Prettier (ya estaba)
- CSS Peek
- Live Share
- Markdownlint
- Markdown All in One

### optativos

- Image Preview
- Peacock
- Reload

## configuración Settings

1. A nivel global el **json**
2. En cada proyecto me creo el archivo .editorconfig con btn derecho "Generate editor config"

👌

Bootcamp, Barcelona

...json
{
{
"terminal.integrated.defaultProfile.windows": "Command Prompt",
"files.autoSave": "onFocusChange",
"editor.formatOnSave": true,
"editor.formatOnPaste": true,
"editor.defaultFormatter": "esbenp.prettier-vscode",
"[html]": {
"editor.defaultFormatter": "vscode.html-language-features"
},
"cSpell.language": "en, es",
"editor.minimap.enabled": false,
"workbench.settings.applyToAllProfiles": ["editor.formatOnSave"],
"diffEditor.ignoreTrimWhitespace": false,
"workbench.iconTheme": "eq-material-theme-icons",
"workbench.colorTheme": "Dracula Theme"
}
}

## Fundamentos

Vamos a buscar información a MDn

- textos
- elementos embeding: audio, img, video
- tablas
- formularios

webs:

- https://developer.mozilla.org/en-US/docs/Web/HTML
- [web.dev](https://web.dev/?hl=es-419)
- https://web.dev/learn?hl=es-419
- en inglés: https://web.dev/learn/html/welcome?continue=https%3A%2F%2Fweb.dev%2Flearn%2Fhtml#article-https://web.dev/learn/html/welcome&hl=es-419
- en español: https://web.dev/learn/html/welcome?continue=https%3A%2F%2Fweb.dev%2Flearn%2Fhtml&hl=es-419#article-https://web.dev/learn/html/welcome&hl=es-419
-
- https://manz.dev/ en español

Cursos en code academy

- https://www.codecademy.com
- https://www.freecodecamp.org/learn/2022/responsive-web-design/

## SEO

## Introducción al HTML

- HTML Hipertext Markup Lenguage
- XML
  ...xml
  <libro>
  <titulo>Yo robot</titulo>
  <autor>Isaac Asimov</autor>
  </libro>
  ...

-JSON a venir a relegar la importancia de xml como lenguaje de presentación de los datos
...json
{
"titulo": "Yo robot",
"autor": "Isaac Asimov"
}
...

- Estándar [W3C] https://www.w3.org/ entidad en la que participan las empresas Google, Apple, Firefox... + el actual responsable del mantenimiento es https://whatwg.org/

- https://caniuse.com/ me da los soportes de cualquier cosa que yo pregunte si se puede usar. Qué navegadores soportan o no esos elementos que quiero poner (ahora, p.e., para imágenes hay una nueva extensión .webp)

Importancia:

- Estructura. Se tiene que validad
- Si no lo hago bien tienen efecto en SEO (Search Engine Optimization) //SEM (son los que pagan)//
- Accesibilidad, gente con ciertas limitaciones
- Usabilidad (UX)
- Performance (el tiempo que tarda en cargar)

- Etiquetas.
- Atributos. Pueden ser universales o específicos
- Comentarios (ctrl + Ç) me coloca <!--  -->
