# Opdracht 1 — Semantisch of niet?

| Semantisch | Niet-semantisch |
| --- | --- |
| `<header>` | `<div>` |
| `<nav>` | `<span>` |
| `<main>` | |
| `<article>` | |
| `<p>` | |
| `<section>` | |
| `<aside>` | |
| `<footer>` | |

## Semantische elementen: waarvoor bedoeld?

- `<header>`: de kop van een pagina of sectie, met bijvoorbeeld het logo, de titel en de navigatie.
- `<nav>`: een blok met de belangrijkste navigatielinks van de website.
- `<main>`: de hoofdinhoud van de pagina; die komt maar één keer per pagina voor.
- `<article>`: een zelfstandig stuk inhoud dat ook los te lezen is, zoals een nieuwsbericht of blogpost.
- `<p>`: een alinea tekst.
- `<section>`: een thematische groep inhoud, meestal met een eigen kop.
- `<aside>`: aanvullende informatie naast de hoofdinhoud, zoals een zijbalk of een quote.
- `<footer>`: de voet van een pagina of sectie, met bijvoorbeeld copyright en contactgegevens.

## Niet-semantische elementen: wanneer gebruik je ze wél?

- `<div>`: als je een blok alleen nodig hebt voor de opmaak (bijvoorbeeld een wrapper voor flexbox of een kaart) en er geen semantisch element bij past.
- `<span>`: als je een stukje tekst binnen een regel een eigen stijl wilt geven, bijvoorbeeld één woord een andere kleur, zonder dat het extra betekenis heeft.

## Bonus

In de paginabron van de homepage van nos.nl (16 november 2026) telde ik deze semantische structuurelementen:

| Element | Aantal |
| --- | --- |
| `<nav>` | 2 |
| `<main>` | 1 |
| `<section>` | 8 |
| `<aside>` | 1 |
| `<footer>` | 1 |
| `<header>` | 0 |
| `<article>` | 0 |

Totaal: **13** semantische structuurelementen (plus 52 `<p>`-elementen). Opvallend: de site gebruikt geen `<header>` en geen `<article>`.
