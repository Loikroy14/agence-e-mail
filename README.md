# revendo.ca

Site d'une page de Revendo, en français (`/`) et en anglais (`/en/`). HTML et CSS statiques, aucune étape de compilation.

## Voir le site en local

```
python3 -m http.server 8000
```

Puis ouvrir http://localhost:8000.

## À faire avant la mise en ligne

- Remplacer tout ce qui est surligné en jaune, dans les 4 pages (accueil et politique de confidentialité, FR et EN) : preuve, garantie, ton histoire et ta photo, nom légal, NEQ, adresse postale, courriel, fournisseurs.
- Faire relire la politique de confidentialité par un juriste.
- Ne pas ajouter de Google Analytics, de pixel Meta ou de polices Google sans mettre à jour la politique (le site affirme n'utiliser aucun témoin ni outil de suivi).
- Mettre le lien de réservation dans `RESERVATION` (index.html) et dans `BOOKING` (en/index.html).
- Retirer le bandeau « Brouillon » et la ligne `<meta name="robots" content="noindex">` dans les deux pages.
