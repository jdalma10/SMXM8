📘 Apunts d’HTML i CSS

Curs de 12 sessions — Document navegable en Markdown

Índex

Sessió 1 — Introducció al web i estructura HTML bàsica

Sessió 2 — Text, paràgrafs i format

Sessió 3 — Enllaços i navegació interna

Sessió 4 — Imatges i atributs

Sessió 5 — Llistes i estructura semàntica HTML5

Sessió 6 — Taules i organització de dades

Sessió 7 — Introducció al CSS i selectors

Sessió 8 — Colors, tipografies i unitats

Sessió 9 — Caixes (box-model), marges i padding

Sessió 10 — Layout amb Flexbox

Sessió 11 — Layout amb Grid

Sessió 12 — Publicació i estructura final del projecte

<a id="sessió-1"></a>⭐ Sessió 1 — Introducció al web i estructura HTML bàsica
🎯 Objectius

Entendre què és HTML.

Crear un primer document HTML correctament estructurat.

📄 Contingut
<!DOCTYPE html>
<html lang="ca">
<head>
    <meta charset="UTF-8">
    <title>El meu primer web</title>
</head>
<body>
    <h1>Hola món!</h1>
    <p>Aquest és el meu primer document HTML.</p>
</body>
</html>

🧩 Tasca

Crea un arxiu index.html amb aquesta estructura i obre'l al navegador.

➡️ Torna a l’índex

<a id="sessió-2"></a>✏️ Sessió 2 — Text, paràgrafs i format
🎯 Objectius

Ús de títols h1–h6

Paràgrafs, salts i etiquetes de format

📄 Contingut
<h1>Títol principal</h1>
<h2>Subtítol</h2>

<p>Aquest és un <strong>paràgraf important</strong>.</p>
<p>Podem fer <em>cursiva</em>, <u>subratllat</u> i <br> fer salts de línia.</p>

🧩 Tasca

Crear una pàgina amb com a mínim 3 nivells de títols i 3 paràgrafs formats.

➡️ Torna a l’índex

<a id="sessió-3"></a>🔗 Sessió 3 — Enllaços i navegació interna
🎯 Objectius

Enllaços externs i interns

Ancoratges dins del mateix document

📄 Contingut
<a href="https://www.wikipedia.org" target="_blank">Visita Viquipèdia</a>

<a href="#seccio1">Ves a la secció 1</a>

<h2 id="seccio1">Secció 1</h2>
<p>Contingut de la secció.</p>


➡️ Torna a l’índex

<a id="sessió-4"></a>🖼️ Sessió 4 — Imatges i atributs
🎯 Objectius

Afegir imatges

Atributs alt, width, height

📄 Contingut
<img src="imatges/foto.jpg" alt="Foto de prova" width="300">


➡️ Torna a l’índex

<a id="sessió-5"></a>📚 Sessió 5 — Llistes i estructura semàntica HTML5
🎯 Objectius

Llistes ordenades i no ordenades

ETIQUETES semàntiques (header, nav, main, footer)

📄 Contingut
<ul>
    <li>Element A</li>
    <li>Element B</li>
</ul>

<ol>
    <li>Primer</li>
    <li>Segon</li>
</ol>

<header><h1>Capçalera</h1></header>
<nav>Menú de navegació</nav>
<main>Contingut principal</main>
<footer>Peu de pàgina</footer>


➡️ Torna a l’índex

<a id="sessió-6"></a>📊 Sessió 6 — Taules i organització de dades
🎯 Objectius

Construir taules

Fusionar cel·les

📄 Contingut
<table border="1">
    <tr>
        <th>Nom</th><th>Edat</th>
    </tr>
    <tr>
        <td>Anna</td><td>20</td>
    </tr>
</table>


➡️ Torna a l’índex

<a id="sessió-7"></a>🎨 Sessió 7 — Introducció al CSS i selectors
🎯 Objectius

Afegir CSS intern i extern

Selectors bàsics

📄 Contingut
<link rel="stylesheet" href="estils.css">

<style>
    p { color: blue; }
    #titol { font-size: 2rem; }
    .destacat { background: yellow; }
</style>


➡️ Torna a l’índex

<a id="sessió-8"></a>🌈 Sessió 8 — Colors, tipografies i unitats
🎯 Objectius

Colors (nom, hex, rgb)

Tipografies i mides

📄 Contingut
body {
    color: #333;
    font-family: Arial, sans-serif;
    font-size: 16px;
}

h1 {
    color: rgb(200, 50, 50);
}


➡️ Torna a l’índex

<a id="sessió-9"></a>📦 Sessió 9 — Box Model: marges, padding i bordes
🎯 Objectius

Entendre com funciona el model de capses

📄 Contingut
.caixa {
    width: 200px;
    margin: 20px;
    padding: 10px;
    border: 2px solid black;
}


➡️ Torna a l’índex

<a id="sessió-10"></a>🧱 Sessió 10 — Layout amb Flexbox
🎯 Objectius

Crear dissenys flexibles

📄 Contingut
.container {
    display: flex;
    gap: 10px;
}

.container div {
    flex: 1;
    background: lightgray;
}


➡️ Torna a l’índex

<a id="sessió-11"></a>🔲 Sessió 11 — Layout amb CSS Grid
🎯 Objectius

Crear graelles avançades

📄 Contingut
.grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 15px;
}


➡️ Torna a l’índex

<a id="sessió-12"></a>🚀 Sessió 12 — Publicació i estructura final del projecte
🎯 Objectius

Organitzar un projecte complet

Preparar-lo per publicar-lo

📁 Estructura recomanada
projecte/
│ index.html
│ estils.css
└─ imatges/

🌐 Publicació

GitHub Pages

Netlify

Vercel

➡️ Torna a l’índex
