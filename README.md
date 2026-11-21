# revendo.ca

Site d'une page de Revendo, en français (`/`) et en anglais (`/en/`). HTML et CSS statiques, aucune étape de compilation.

## Structure (méthode de Louis)

Une page, une promesse, un seul bouton (réserver un appel) :

1. Titre qui dit le résultat, avec la cible nommée au-dessus
1b. Pour qui : catégories, ses mots à lui, « c'est pour toi si » et « pas pour toi si »
2. Ce qu'on met en place : la série de rachat (preuve concrète, marque fictive)
3. Avant / après
4. Pourquoi nous (au bon moment, bilingue, mesure honnête, géré chaque mois)
5. Comment ça marche (analyse gratuite, appel, installation, appel de résultats à 30 jours)
6. L'offre en échelle : analyse gratuite (vidéo de 5 min), Installation Rachat 790 $ (une fois), puis Suivi Rachat (490 $/mois) et Gestion Rachat (1 190 $/mois) si le client veut
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
