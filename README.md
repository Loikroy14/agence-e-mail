# revendo.ca

Site d'une page de Revendo, en français (`/`) et en anglais (`/en/`). HTML et CSS statiques, aucune étape de compilation.

## Voir le site en local

```
python3 -m http.server 8000
```

Puis ouvrir http://localhost:8000.

## À faire avant la mise en ligne

- Remplacer tout ce qui est surligné en jaune : la preuve, la garantie, l'adresse postale, le courriel, la politique de confidentialité.
- Mettre le lien de réservation dans `RESERVATION` (index.html) et dans `BOOKING` (en/index.html).
- Retirer le bandeau « Brouillon » et la ligne `<meta name="robots" content="noindex">` dans les deux pages.
