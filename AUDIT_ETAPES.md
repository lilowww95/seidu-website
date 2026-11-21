# SEI DU — Audit et transfert GitHub

## Origine
- `index.html` : copie du fichier fourni `index (1).html` (titre de page et description SEO mis à jour uniquement).
- `assets/` : images issues de l'archive locale SEI DU V18.
- **Ce paquet n'est pas garanti identique à l'état non publié de l'agent Netlify.**

## Vérifications statiques
- Images et ressources locales référencées : 16.
- Ressources locales manquantes : 0 (aucune).
- Réservation : lien Calendly non configuré (message de démonstration).
- Formulaires : fonctions de démonstration, données non transmises au propriétaire du site.
- Musique : tentative de lecture automatique; les navigateurs peuvent la bloquer.
- Traductions, responsive et animations : présents dans le code, nécessitent tests réels.

## Avant publication
1. Comparer cette version au site Netlify et récupérer les changements non publiés.
2. Configurer et tester un service de formulaires (Netlify Forms ou autre) et consentement.
3. Configurer les réservations et paiements approuvés.
4. Tester sur téléphone, ordinateur, en français et anglais, et les performances.
5. Connecter GitHub à Netlify seulement après validation visuelle.

## Test local
Ouvrir `index.html` dans un navigateur; pour un test plus fidèle : `python3 -m http.server 8000` depuis ce dossier.
