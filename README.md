🧭 Sessió 1 — HTML bàsic i HTML semàntic
🎯 Objectius

Entendre què és HTML i com s’estructura una pàgina web.

Conèixer les etiquetes bàsiques (html, head, body, títols, paràgrafs…).

Introduir l’HTML semàntic i la seva utilitat.

Crear l’esquelet d’un lloc web que s’ampliarà a les següents sessions.

📌 1. Estructura mínima d’un document HTML

Tot document HTML5 comença així:

<!DOCTYPE html>
<html lang="ca">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Títol de la pàgina</title>
</head>

<body>

</body>
</html>

🔍 Què fa cada etiqueta?

<!DOCTYPE html> → indica que és HTML5

<html> → arrel del document

<head> → informació per al navegador (metadades, títol, imports...)

<title> → text que apareix a la pestanya del navegador

<body> → tot el contingut visible

📌 2. Etiquetes bàsiques de contingut
Títols
<h1>Títol principal</h1>
<h2>Subtítol</h2>

Paràgrafs i text enriquit
<p>Això és un paràgraf.</p>
<p><strong>Text en negreta</strong> i <em>cursiva</em>.</p>

Llistes
<ul>
    <li>Element 1</li>
    <li>Element 2</li>
</ul>

📌 3. HTML semàntic

Utilitzem etiquetes que descriuen el propòsit del contingut:

header → capçalera

nav → menú de navegació

main → contingut principal

section → secció temàtica

article → contingut independent

aside → informació complementària

footer → peu de pàgina

Exemple complet dins del <body>
<body>
    <header>
        <h1>El meu lloc web</h1>
    </header>

    <nav>
        <ul>
            <li>Inici</li>
            <li>Articles</li>
            <li>Contacte</li>
        </ul>
    </nav>

    <main>
        <section>
            <h2>Benvinguda</h2>
            <p>Text introductori de la secció principal.</p>
        </section>

        <article>
            <h3>Títol d'un article</h3>
            <p>Primer paràgraf de l'article.</p>
            <p>Segon paràgraf de l'article.</p>
        </article>
    </main>

    <aside>
        <p>Informació complementària.</p>
    </aside>

    <footer>
        <p>&copy; 2025 El meu lloc web</p>
    </footer>
</body>

📝 Activitat de la sessió

Crea un fitxer index.html amb:

L’estructura HTML5 completa

Un <header> amb el títol del web

Un <nav> amb una llista (encara sense enllaços)

Un <main> amb:

Una <section> amb títol i paràgraf

Un <article> amb dos o tres paràgrafs

Un <aside> amb informació secundària

Un <footer> simple

Aquest serà l’esquelet base del teu projecte web per a tot el curs.

✅ Resultat final de la sessió

Els alumnes acaben amb una pàgina HTML:

Correctament estructurada

Semàntica

Llesta per afegir imatges, enllaços i navegació real a la Sessió 2
