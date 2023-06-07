---
theme: default
background: /images/ia-data.jpg
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Pas d'IA sans data.
  Vers des jeux de données libres et ouverts pour l'éducation.

  Les slides sont disponibles sur [GitHub](https://openfun.github.io/2023-ai-education-datasets/).
drawings:
  persist: false
transition: fade
title: IA & Education 2023 // Pas d'IA sans data.
---

# Pas d'IA sans data.

Vers des jeux de données libres et ouverts pour l'éducation.

<logos-mastodon-icon /> [@jmaupetit](https://mamot.fr/@jmaupetit) // <logos-twitter /> [@open_fun](https://twitter.com/open_fun)


<div class="abs-br m-6 flex gap-2">
  <a href="https://openfun.github.io/2023-ai-education-datasets/" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<div class="credit">
    Photo de <a href="https://unsplash.com/@syinq?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Susan Q Yin</a> sur <a href="https://unsplash.com/fr/photos/2JIvboGLeho?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
</div>


<!--
The last comment block of each slide will be treated as slide notes. It will be
visible and editable in Presenter Mode along with the slide. [Read more in the
docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: statement
background: https://source.unsplash.com/collection/94734566/1920x1080
---

<style>
blockquote {
  margin: 4rem;
  padding-top: 2rem !important;
  padding-bottom: 2rem !important;
}
blockquote p {
  font-size: 1.5rem;
  line-height: 2.5rem;
}
</style>

> Cette présentation ne parle pas d'« Intelligence Artificielle ».


---
layout: section
---

## De l'importance des jeux de données pour apprendre

---
layout: image-right
image: /images/dataset.png
---

### Problématique

<br/>
<br/>

* Dépendance : un jeu de données comportementales
* Comment obtenir un tel jeu de données ?
    - données maison
    - données ouvertes
* Très peu de jeux de données sont disponibles ([OULAD](https://www.nature.com/articles/sdata2017171), [MOOCCubeX](https://github.com/THU-KEG/MOOCCubeX), [StanfordMoocPosts](https://datastage.stanford.edu/StanfordMoocPosts/), et ?)

<div class="credit">
    Illustration réalisée par MidJourney
</div>

---
layout: image-right
image: /images/citizen-science.png
---

### Des données ouvertes pour qui ?

<br/>
<br/>
<br/>

* Chercheurs
* Entreprises
* Citoyens

<div class="credit">
    Illustration réalisée par MidJourney
</div>

---
layout: image-right
image: /images/lock-in.jpg
---

### Freins à l'ouverture

<br />
<br />

* Pas d'incitation à libérer ces données
* Les traces d'apprentissage sont des données identifiantes


<div class="credit">
    Photo de <a href="https://unsplash.com/ja/@polarmermaid?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Anne Nygård</a> sur <a href="https://unsplash.com/fr/photos/rTC5SF27jIc?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
</div>

---
layout: image-right
image: /images/open.jpg
---

### FUN est un Groupement d'Intérêt Public

Notre crédo :

> Argent public, code public ... données publiques.

* Argent public ✅
* Code public \* ✅
* Données publiques 🔳

\* https://github.com/openfun


<div class="credit">
    Photo de <a href="https://unsplash.com/@marcooriolesi?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Marco Oriolesi</a> sur <a href="https://unsplash.com/fr/photos/wqLGlhjr6Og?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
</div>

---
layout: section
---

## Vers une ouverture de nos données d'apprentissage

---
layout: image-right
image: /images/to-open.jpg
---

### Défis

<br/>
<br/>
<br/>

1. Quel standard adopter pour ces données ?
2. Comment les anonymiser ?

<div class="credit">
    Photo de <a href="https://unsplash.com/@ruisilvestrecreative?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Rui  Silvestre</a> sur <a href="https://unsplash.com/fr/photos/ul-ZsFLIjvw?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
</div>

---
layout: image-right
image: /images/json.jpg
---

### Standard adopté : profils xAPI

<br/>
<br/>
<br/>

* Un vocabulaire contrôlé pour des statements xAPI
* Fusion de datasets de sources différentes
* [github.com/Gaia-X-DaSES](https://github.com/gaia-x-dases)

<div class="credit">
    Photo de <a href="https://unsplash.com/ko/@flowforfrank?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Ferenc Almasi</a> sur <a href="https://unsplash.com/fr/photos/HfFoo4d061A?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
</div>

---
layout: image-right
image: /images/anon.jpg
---

### Anonymisation

<br/>
<br/>

En 2022, FUN est lauréat du Bac à Sable Education de la CNIL.

Premières étapes :

* Minimisation des traces d'apprentissage
* Hachage identifiant utilisateur
* Obfuscation de la clé de cours / ressource pédagogique

<div class="credit">
    Photo de <a href="https://unsplash.com/@jjrocha?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Jesús Rocha</a> sur <a href="https://unsplash.com/fr/photos/ZNOtwtFUvhk?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
</div>

---
layout: image-right
image: /images/outliers.png
hideInToc: true
---

### Anonymisation

<br/>
<br/>

Deuxième étape (avant publication) :

* Analyse statistique des traces
* Evaluer la génération de données synthétiques
* Participation à des challenges de ré-identification

<div class="credit">
    Illustration réalisée par MidJourney
</div>

---
layout: center
---

## Des questions, des remarques ?

Parlons-en.
