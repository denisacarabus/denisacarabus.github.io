![text descriptiv imagine](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=1100)

*Cuprins*

[Elemente avansate de Markdown](avansate.md)

[Formule cu MathJax](mathjax.md)

[Matrici si ecuatii](mathjax2.md)

[Diagrame Mermaid](/Diagrame/mermaid.md)


***

# Implementarea relatiilor in Markdown
 
## Implementarea relatiilor/legaturilor catre alte fisiere

Fisierele accesate prin link-uri pot fi:
1. gazduite pe alte servere(de ex: accesarea unui alt site)
2. gazduite pe serverul site-ului curent

De asemenea, prin aceste link uri se pot accesa si sectiuni din pagina curenta sau sectiuni din alte pagini ale aceluiasi site.

### Sintaxa unui link Markdown

Tipuri de link-uri in markdown:
1. link-uri clasice
2. link-uri referentiate

#### Link-uri clasice

**Variante:
[textul link-ului](https://google.com/)
[textul link-ului](https://google.com/ "accesare site google")

#### Link-uri referentiate

Iata un [link][link1] catre site-ul Google

[link1]: https://google.com/

Varianta prescurtata a link-urilor referentiate:

Iata un link [important] catre site-ul Google

[important]: https://google.com/

#### Link-uri catre imagini

![text descriptiv imagine](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=1100)
