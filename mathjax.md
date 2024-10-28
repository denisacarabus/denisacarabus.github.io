<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

![text descriptiv imagine](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=1100)

[Homepage](index.md)

# Inserarea ecuatiilor si formulelor ' MathJax'

**Sintaxa:**

Formulele 'MathJax' sunt inserate in aceeasi linie daca sunt plasate intr-o pereche de simblouri '$'

*Exemplu:* Aceasta este o ecuatie: $a=bc$ 

Formulele 'latex' (prin 'MathJax') se introduc pe rand nou intre doua perechi de simboluri '$$'

Exemplu :

$$a=b^2$$


#  Ridicarea la putere ( superscript)

Se foloseste meta_caracterul 'Latex' : '^'

Exemplu:

$$a=10^7$$

# 'Subscript' 

Se foloseste meta-caracterul 'Latex': '_'

*Exemplu:*

$$a_i = b^c$$

# Gruparea elementelor din formule 

Elementele din formule se grupeaza prin meta-caracterele '{' si '}'

$$ 10^{10} $$


# Litere grecesti 

*exemple:*

'\alpha' - alpha litera mica ($$\alpha$$)

'\Alpha' - alpha litera mare ($$\Alpha$$)


# Parantezele 

- Parantezele rotunde se scriu direct (nu au un inteles special 'Latex')
- Parantezele drepte  se scriu direct (nu au un inteles special 'Latex')
- Acoladele,deoarece sunt metacaractere de grupare, vor fi rederizate corect daca sunt `escapate` de intelesul lor,special,punand in fata lor  `metacaracterul` `\`

  *Exemple:*

  $$a= (b+c)^{3x}-[3+6x] $$

  #Fractiile

  `\frac{numarator}{numitor}`

$$ a=\frac{(a+b}{(d-c)} $$

# Semnele de multiplicare si diviziune 

*Exemple:*

$$ a=c+10  \times x $$

$$ a=c+10 \cdot x  $$

$$ a =b \div c $$

# Suma de la i=0 la n 

**Exemplu:**

$$ \sum_{i=0}^n i^2 = \frac{(a+b) \times (b+c)}{6} $$


# Integrale 

**Exemple:**

$$ \int_0^1 x^4 dx $$
