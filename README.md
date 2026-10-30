# Kiswendsida & Frères — site

Site vitrine de **Kiswendsida & Frères** : achat, vente, collecte, tri, recyclage,
récupération, transformation, valorisation, commerce et importation de ferrailles.
265, Boulevard Zerktouni, 9ᵉ étage, appartement n°92, Anfa — Casablanca.

En ligne : <https://kobedy.github.io/kiswendsida-freres/>

Une seule page, sans dépendance ni étape de construction : `index.html` et `assets/`.
La branche servie par GitHub Pages est `gh-pages`.

## Numéro WhatsApp

Le formulaire compose un message WhatsApp pré-rempli. Le numéro se règle en un seul
endroit, en haut du `<script>` de `index.html` :

```js
var WA_NUMBER = '212612345678';   // format international, sans « + » ni espaces
```

Tant que la chaîne est vide, les boutons ouvrent WhatsApp avec le message prêt mais
sans destinataire. Les champs `[__]` (téléphone, e-mail, horaires, ICE, RC) attendent
eux aussi leur validation.

## Photographies

Les images de `assets/photos/` viennent de Pexels (licence libre, usage commercial,
sans attribution obligatoire). Elles tiennent la place du reportage à faire sur le parc
et les chantiers.

---

Identité de marque et site : **Kobedy Web**.
La charte de marque et les sources de production sont tenues dans un dépôt privé.
