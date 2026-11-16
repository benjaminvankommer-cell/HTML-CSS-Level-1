# Opdracht 2 — Block of inline?

| Element | Block-level of inline? | Mag het binnen een `<p>`? |
| --- | --- | --- |
| `<p>` | block-level | nee |
| `<a>` | inline | ja |
| `<div>` | block-level | nee |
| `<strong>` | inline | ja |
| `<h2>` | block-level | nee |
| `<span>` | inline | ja |
| `<section>` | block-level | nee |
| `<em>` | inline | ja |

Een `<p>` mag alleen inline-inhoud (phrasing content) bevatten. Block-level elementen zoals `<div>`, `<h2>`, `<section>` en een andere `<p>` horen er dus niet in.

## Bonus

Zie `bonus.html`. Als je een `<div>` binnen een `<p>` zet, sluit de browser de `<p>` automatisch af vóór de `<div>`. In de inspector zie je daardoor een lege `<p>`, daarna de `<div>` los, en de afsluitende `</p>` wordt een nieuwe lege alinea. De HTML Validator geeft de fout: *"No p element in scope but a p end tag seen."*
