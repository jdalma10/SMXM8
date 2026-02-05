# 🟦 Sessió: HTML Semàntic

## 🎯 Objectius de la sessió
Al final de la sessió l’alumnat haurà de ser capaç de:

- Entendre què és l’HTML semàntic  
- Diferenciar entre etiquetes semàntiques i no semàntiques  
- Utilitzar correctament les principals etiquetes semàntiques  
- Estructurar una pàgina web amb sentit i ordre  

---

## ⏱️ Durada suggerida  
👉 60–90 minuts

---

## 1️⃣ Què és l’HTML semàntic? (10 min)

**Explicació curta:**

HTML semàntic significa utilitzar etiquetes que **descriuen el significat del contingut**, no només l’aspecte visual.

❌ No semàntic:

```html
<div>
  <div>Menú</div>
  <div>Contingut principal</div>
  <div>Peu de pàgina</div>
</div>
✅ Semàntic:

html
Copia el codi
<header>Menú</header>
<main>Contingut principal</main>
<footer>Peu de pàgina</footer>
Avantatges
Millor per a accessibilitat

Millor per a cercadors (SEO)

Codi més clar i professional

2️⃣ Principals etiquetes semàntiques (15 min)
Etiqueta	Per a què serveix
<header>	Capçalera del web
<nav>	Menú de navegació
<main>	Contingut principal
<section>	Seccions temàtiques
<article>	Contingut independent
<aside>	Barra lateral
<footer>	Peu de pàgina

3️⃣ Exemple complet (15 min)
html
Copia el codi
<!DOCTYPE html>
<html>
<head>
  <title>Pàgina Semàntica</title>
</head>
<body>

<header>
  <h1>El meu web</h1>
  <nav>
    <a href="#">Inici</a>
    <a href="#">Sobre mi</a>
    <a href="#">Contacte</a>
  </nav>
</header>

<main>
  <section>
    <h2>Qui soc</h2>
    <p>Sóc estudiant de programació web.</p>
  </section>

  <article>
    <h2>El meu primer article</h2>
    <p>Aquest és un text independent.</p>
  </article>
</main>

<aside>
  <p>Notícies ràpides</p>
</aside>

<footer>
  <p>© 2026 El meu web</p>
</footer>

</body>
</html>
4️⃣ Activitat pràctica (20–30 min)
Crea una pàgina amb:

1 <header> amb títol i menú

1 <main> amb:

1 <section> “Sobre mi”

1 <article> “El meu hobby”

1 <aside> amb informació extra

1 <footer> amb el teu nom

5️⃣ Preguntes de tancament (10 min)
Per què és millor <header> que <div>?

Quan faries servir <article>?

On posaries el menú: <nav> o <main>?
