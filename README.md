# LINIA — Piste 3 “La Saison créative”

## 1. Présentation
Prototype HTML/CSS/JS statique pour présenter LINIA comme une adresse créative vivante à Remouchamps, rythmée par les saisons, ateliers, nouveautés boutique, créateurs locaux, cartes cadeaux et événements.

## 2. Objectif
Favoriser les réservations d’ateliers, les ventes boutique, les cartes cadeaux, la fidélisation et le retour régulier sur le site via une programmation éditoriale mise à jour.

## 3. Différence avec les pistes 1 et 2
La piste 1 fait ressentir le lieu. La piste 2 guide par envie créative. La piste 3 organise les contenus par mois, saison, nouveautés, agenda et événements, comme une programmation culturelle douce.

## 4. Fichiers créés
- `index.html` : page complète de la piste 3.
- `css/styles.css` : design system, responsive, placeholders CSS et composants WooCommerce simulés.
- `js/main.js` : menu burger mobile.
- `docs/synthese-piste-3.md` : synthèse stratégique avant codage.
- `assets/brand/` et `assets/placeholders/` : dossiers prêts pour les futurs médias.

## 5. Lancer en local
Ouvrir directement `index.html` dans un navigateur ou lancer :

```bash
python3 -m http.server 8000
```

Puis ouvrir `http://localhost:8000`.

## 6. Tester sur smartphone via le même Wi-Fi
1. Lancer `python3 -m http.server 8000`.
2. Trouver l’IP locale de l’ordinateur (`hostname -I` sur Linux).
3. Depuis le smartphone connecté au même Wi-Fi, ouvrir `http://IP_LOCALE:8000`.

## 7. Publier sur GitHub Pages
Pousser le dépôt sur GitHub, puis activer Pages dans `Settings > Pages`, source `Deploy from a branch`, branche courante, dossier racine.

## 8. Transposition WordPress/WooCommerce
- Les sections `wp-section` et `wp-container` pourront devenir des blocs Gutenberg.
- Les cartes `wc-product-card` préfigurent une boucle WooCommerce produits.
- Les cartes `wc-workshop-card` préfigurent des produits WooCommerce virtuels avec stock limité pour les places.
- Les capsules pourront devenir catégories saisonnières, articles ou pages d’atterrissage.
- L’agenda pourra être alimenté par des produits ateliers, événements ou articles.

## 9. Points à adapter plus tard
- Vraies photos et visuels de LINIA.
- Adresse, horaires et coordonnées définitives.
- Produits réels, prix, stocks et catégories.
- Ateliers réels, dates, animateurs, conditions et places.
- Vraie programmation éditoriale.
- Fiches événements.
- Intégration WooCommerce.
- Paiements Stripe/Mollie.
- Google Maps.
- Formulaires.
- Système d’actualités WordPress.

## Sources exploitées et limites
Les informations visibles dans les annexes fournies dans la conversation ont été exploitées : questionnaire stratégique, positionnement, publics, freins, ateliers, produits, créateurs locaux, coin café et univers graphique. Aucun fichier annexe local supplémentaire n’était présent dans le dépôt au moment de l’implémentation.
