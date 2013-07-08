Règles de style
===============

Les règles de style et de nomenclature pour nos projets de développement.

Ces règles de style s'appliquent à tous nos projets de développement de
logiciels, sauf si une exigence du client stipule le contraire.

Définitions
-----------

PascalCase : Aucun espacement entre les mots d'un identifiant et chaque mot
commence par une lettre majuscule. Par exemple : ClientAddress,
InvoiceLineNumber, Member.

CamelCase : Aucun espacement entre les mots d'un identifiant et chaque mot
commence par une lettre majuscule à l'exception du premier mot. Dans ce
document, lorsque nous faisons référence au CamelCase, on sous-entend
lowerCamelCase. Il est inutile de spécifier la casse du premier mot car nous
utilisons le terme PascalCase pour identifier le upperCamelCase. Par exemple :
clientAddress, invoiceLineNumber, member.

SnakeCase : Le caractère underscore '_' pour séparer les mots, toutes les
lettres en minuscule. Aussi connu sous le nom de UnderscoreCase. Par exemple :
client_address, invoice_line_number, member.

UpperSnakeCase : Même chose que SnakeCase mais avec toutes les lettres en
majuscule. Par exemple : CLIENT_ADDRESS, INVOICE_LINE_NUMBER, MEMBER.

HyphenSeparatedCase : Le caractère hyphen '-' pour séparer les mots, toutes les
lettres en minuscule. Par exemple : client-address, invoice-line-number, member.

Règles de nomenclature par technologie
--------------------------------------

### HTML, Jade

* Les noms des éléments et attributs sont en minuscules.
* Les noms de classes et les valeurs des attributs id sont en
  HyphenSeparatedCase.

### CSS, Stylus

* Les noms de classes sont en HyphenSeparatedCase.
* Les valeurs des propriétés sont en minuscules.

### Java, Groovy

* http://www.oracle.com/technetwork/java/javase/documentation/codeconvtoc-136057.html

### JSON

* Les noms des propriétés sont en SnakeCase.

### Javascript, CoffeeScript

* Les noms de variables et de fonctions sont en CamelCase.
* Les noms de classes sont en PascalCase.
* Les noms des propriétés dans un objet Javascript doivent suivre les règles de
  JSON uniquement si l'objet est destiné à être sérialisé en JSON.