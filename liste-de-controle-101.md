# Liste de contrôle 101 

## Structure de répertoires et nomenclatures
- [x] Les noms de dossier sont signifiants et n'ont pas de majuscules, d'espaces ou de caractères spéciaux
- [x] Les noms de fichier sont signifiants et n'ont pas de majuscules, d'espaces ou de caractères spéciaux
- [x] La page se nomme _index.html_ et se situe à la racine du site
- [x] La nomenclature des fichiers est systématique
- [x] La nomenclature des images est systématique (section associée, fonction, etc.)
- [x] Tous les noms de classe sont signifiants et utilisent une nomenclature constante


## Favicon
- [x] Le favicon est fonctionnel et intégré dans toutes les pages 
- [x] Le favicon est signifiant et en lien avec le thème du site

---

## HTML 

### Contenu minimal de l'élément head 
- [x] Doctype: La déclaration du type de document est présent 
- [x] L'élément `html` inclut l'attribut `lang="fr"` (ou "en" si le texte est en anglais). 
- [x] L'élément `charset` définit l'encodage du texte en UTF-8
- [x] Les éléments `meta` (`description`, `keywords`, `author`) sont présents
- [x] L'élément `meta` viewport est présent et complet 
- [x] L'élément `title` est présent et placé après l'élément `charset` 
- [x] Le contenu des éléments `title` est écrit sans faute
- [x] L'élément `link` est bien utilisé pour relier la feuille de styles du document.

### Structure et sémantique
- [x] Les éléments HTML sont utilisés en fonction de leur signification
- [x] Le contenu HTML est écrit dans un ordre logique
- [x] Les éléments de structure sont utilisés selon les règles
- [x] `h1` est unique et décrit le thème de la page
- [x] Les titres (`h1`, `h2`, `h3`, etc.) sont utilisés dans l'ordre et de manière pertinente

### Validité et lisibilité
- [x] Les balises sont correctement imbriquées
- [x] Le code HTML est valide selon le [Validateur HTML du w3c](https://validator.w3.org/)
- [x] Le balisage est indenté correctement et régulièrement

### Hyperliens
- [x] Les liens de la navigation principale sont tous fonctionnels  
- [x] Les liens du contenu sont tous fonctionnels

### Images réactives
- [x] Les images sont imbriquées dans picture (deux sources)

---
## Accessibilité

- [x] Les éléments `a` contiennent du texte (libellé du lien) qu'un lecteur vocal PEUT lire. 
- [x] Toutes les balises `img` ont un attribut `alt` avec un contenu pertinent

---

## CSS
- [x] L'instruction __@charset "UTF-8";__ est placée sur la première ligne du fichier
- [x] La feuille de style de réinitialisation précède l'ensemble des règles 
- [x] Les tailles de typo sont en rem, em ou vw
- [x] Les variables du projet sont présentées sous le sélecteur :root

### Lisibilité
- [x] La feuille de style est ordonnée en fonction des affinités et de la hiérarchie du contenu 
- [x] La feuille de style est écrite lisiblement  
- [x] La feuille de style est commentée
- [x] Les polices importées de Google Fonts sont fonctionnelles

### Réactivité (_Responsive Web Design & Mobile First_)
- [x] L'approche Mobile d'abord est utilisée
- [x] La réactivité de la navigation principale est harmonieuse (horizontale à verticale)
- [x] La réactivité de la zone de contenu des sections est harmonieuse (largeur du texte contrôlée) 
- [x] La réactivité des images (images adaptées écran étroit vs large)
- [x] Le ou les points de rupture sont judicieusement choisis en fonction de l'interface

### Contrôle de la mise en forme 
- [x] L'ensemble du site comporte une identité visuelle personnalisée: couleurs, polices, etc.
- [x] La hiérarchie visuelle des titres est cohérente
- [x] Les images sont mis en forme de manière contrôlée 
- [x] Les hyperliens de contenu sont mis en forme
- [x] Les alignements sont consistants d'une section à l'autre

---

## Performance
- [x] Taille et poids des images contrôlés

## Droits d'auteur
- [x] Les sources des contenus sont indiquées
