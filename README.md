# revendo.ca

Site d'une page de Revendo, en français (`/`) et en anglais (`/en/`). HTML et CSS statiques, aucune étape de compilation.

## Structure (méthode de Louis)

Une page, une promesse, un seul bouton (réserver un appel) :

1. Titre qui dit le résultat
2. Ce qu'on installe : les 3 courriels de rachat (preuve concrète, marque fictive)
3. Avant / après
4. Pourquoi nous
5. Comment ça marche
6. Ce que tu reçois et prix
7. Qui est derrière
8. FAQ
9. Le même bouton

Couleurs tirées du logo : crème `#F4F1EA`, vert forêt `#14261F`, terracotta `#E2603F` (bouton seulement). Titres en Fraunces, texte en Inter.

## Voir le site en local

```
python3 -m http.server 8000
```

Puis ouvrir http://localhost:8000.

## À faire avant la mise en ligne

- Remplacer tout ce qui est surligné en jaune, dans les 4 pages (accueil et politique de confidentialité, FR et EN) : garantie, ton histoire et ta photo, nom légal, NEQ, adresse postale, courriel, fournisseurs.
- Faire relire la politique de confidentialité par un juriste.
- Ne pas ajouter de Google Analytics, de pixel Meta ou de polices Google sans mettre à jour la politique (le site affirme n'utiliser aucun témoin ni outil de suivi).
- Mettre le lien de réservation dans `RESERVATION` (index.html) et dans `BOOKING` (en/index.html).
- Retirer le bandeau « Brouillon » et la ligne `<meta name="robots" content="noindex">` dans les deux pages.
- Dès qu'on a un vrai témoignage, l'ajouter dans la section « Ce qu'on installe » (commentaire dans le code).
