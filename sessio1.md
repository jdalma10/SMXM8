# Sessió 1 — Introducció a HTML, Etiquetes bàsiques i Semàntica
🧭 Índex

1. Què és HTML?

2. Anatomia d’una etiqueta

3. Estructura mínima d’una pàgina HTML

4. Etiquetes bàsiques

4.1 Títols

4.2 Paràgrafs

4.3 Enllaços

4.4 Imatges

4.5 Llistes

4.6 Contenidors

5. HTML Semàntic

5.1 Etiquetes principals

5.2 Exemple complet

##  1. Què és HTML?

HTML (HyperText Markup Language) és un llenguatge de marcat que serveix per estructurar el contingut d’una pàgina web.

HTML no és un llenguatge de programació:
➡ no té funcions
➡ no té variables
➡ no té lògica condicional

És un sistema basat en etiquetes (tags) que indiquen què és cada part del document.

## 2. Anatomia d’una etiqueta

Un element HTML acostuma a tenir aquesta forma:

<p class="missatge">Hola món!</p>


Parts:

<p> → etiqueta d’obertura

class="missatge" → atribut

Hola món! → contingut

</p> → etiqueta de tancament

Elements sense tancament (void elements):

<img>, <br>, <hr>, <input>, <meta>, <link>

## 3. Estructura mínima d'una pàgina HTML
<!DOCTYPE html>
<html lang="ca">
  <head>
    <meta charset="UTF-8">
    <title>La meva primera pàgina</title>
  </head>
  <body>
    <h1>Hola món!</h1>
    <p>Això és un paràgraf.</p>
  </body>
</html>


Parts principals:

<!DOCTYPE html> → declara HTML5

<html> → arrel del document

<head> → informació no visible

<body> → contingut mostrable

## 4. Etiquetes bàsiques
### 4.1 Títols
<h1>Títol principal</h1>
<h2>Subtítol</h2>
<h3>Secció</h3>


Hi ha 6 nivells: de h1 a h6.

### 4.2 Paràgrafs
<p>Això és un paràgraf.</p>

### 4.3 Enllaços
<a href="https://example.com">Visita la web</a>


Atributs útils:

<a href="https://example.com" target="_blank" rel="noopener noreferrer">
  Obre en nova pestanya
</a>

### 4.4 Imatges
<img src="foto.jpg" alt="Descripció de la imatge">


ℹ alt és important per accessibilitat.

### 4.5 Llistes
Llista ordenada
<ol>
  <li>Primer</li>
  <li>Segon</li>
</ol>

Llista no ordenada
<ul>
  <li>Element A</li>
  <li>Element B</li>
</ul>

### 4.6 Contenidors
<div>Contenidor de bloc</div>
<span>Element en línia</span>


<div> → ocupa tot l’ample disponible

<span> → només ocupa el seu contingut

## 5. HTML Semàntic

L’HTML semàntic dona significat al contingut.
Afavoreix:

Accessibilitat

SEO

Organització

Llegibilitat del codi

### 5.1 Etiquetes principals
Estructura de pàgina
<header>Capçalera</header>
<nav>Navegació</nav>
<main>Contingut principal</main>
<footer>Peu de pàgina</footer>

Organització del contingut
<section>Secció temàtica</section>
<article>Article independent</article>
<aside>Contingut lateral</aside>

Etiquetes de text semàntic
<strong>Text important</strong>
<em>Text amb èmfasi</em>

### 5.2 Exemple complet
<!DOCTYPE html>
<html lang="ca">
<head>
  <meta charset="UTF-8">
  <title>Pàgina semàntica</title>
</head>
<body>

<header>
  <h1>Apunts de desenvolupament web</h1>
</header>

<nav>
  <ul>
    <li><a href="#html">HTML</a></li>
    <li><a href="#css">CSS</a></li>
  </ul>
</nav>

<main>
  <article id="html">
    <h2>Introducció a HTML</h2>
    <p>HTML és el llenguatge que estructura una pàgina web.</p>
  </article>

  <section>
    <h3>Etiquetes bàsiques</h3>
    <p>Com ara <code>p</code>, <code>h1</code>, <code>img</code>…</p>
  </section>
</main>

<footer>
  <p>© 2025 — Apunts Web</p>
</footer>

</body>
</html>
