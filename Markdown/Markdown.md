# El llenguatge Markdown

Markdown es defineix com un **llenguatge de marques lleuger**, amb la finalitat d'escriure utilitzant un format de text pla, fàcil d'escriure i de llegir, i que puga convertir-se a altres formats, com HTML, epub o pdf.

A la web [https://markdown.es/](https://markdown.es/) disposeu de molta informació i un vídeo bastant bo sobre aquest llenguatge i algunes eines que us faciliten la vida a l'hora de generar documents.

Amb Markdown podem formatar el text amb lletres cursives, negretes, capçaleres o enllaços utilitzant únicament text pla, el que fa que l'escriptura siga més simple i eficient, ja que ens evita haver d'estar pensant en el format i ens permet centrar-nos només en el contingut. La seua facilitat d'us i sintaxi clara, junt amb que permet incloure i formatar codi font, fa que siga le llenguatge per excel·lència en llocs com Gihtub per tal de documentar els projectes que allotja.

Veiem un ressum de la sintaxi principal:

* **Capçaleres**

```markdown
# Capçalera de primer nivell
## Capçalera de segon nivell nivell
### Capçalera de tercer nivell nivell
...

```

* **Formatació de text**

```markdown
*Text en cursiva* (compte amb no posar espais darrere el primer * d'inici o davant el * del final)
**Text en negreta** (compte també amb els espais)
***Text en cursiva i negreta***
```

* **Llistes**

```markdown
* Item 1 en llista desordenada
* Item 2 en llista desordenada
* ...
```

```markdown
1. Item 1 en llista ordenada
2. Item 2 en llista ordenada
* ...
```

* **Taules:** Les taules han de tindre una capçalera i un cos, i la seua sintaxi és la següent:

```markdown
| Camp 1 capçalera | Camp 2 capçalera |
|------------------|------------------|
| Valor            | Valor            |
| Altre valor | Altre valor |
```
Cal tindre en compte que podem afegir tants camps com volguem. A més, la línia que separa la capçalera del cos `|---|---|` és obligatòria, però no és necessari que tinga tants caràcters com tinguen les capçaleres.

* **Fragments de codi**

Els fragments de codi els podem posar bé de forma `inline`, escrivint en la mateixa línia el codi que volem escriure tantat entre `'accents oberts'`, o bé si es tracta d'un fragment de codi, podem fer:

```
'''
línia 1
línia 2
etc
'''
```

Per a més informació sobre Markdown podeu consultar:

* La guía de markdown en espanyol: [https://markdown.es/](https://markdown.es/) 
* La sintaxi estesa de markdown a la web: [https://www.markdownguide.org/extended-syntax](https://www.markdownguide.org/extended-syntax)


## Edició de fitxers Markdown

Markdown es un format de text, pel que qualsevol editor de text ens és suficient.

No obstant això, existeixen eines tipus Haroopad o editors Markdown online que proporcionen una finestra partida on podem escriure en format Markdown a una part, i veure'n el resultat en directe al costat.

L'editor VSCode també suporta directament el llenguatge Markdown i ofereix un previsualització del que anem fent. No obstant això, existeixen extensions com *Markdwon All In One* que aporta altres funcionalitats com tecles d'accés ràpid, suport a taules de continguts, entre d'altres.

