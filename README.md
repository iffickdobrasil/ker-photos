# ker-photos — médias image Kermenhir pour Metricool

Repo **public** : les fichiers servent d'URL média à Metricool. **Rien de sensible.**

## Règles
- Photos : **JPG**, 1080×1350 (4:5) pour le fil, ou 1080×1080 (carré).
- **Max ~50 Mo par fichier** (GitHub refuse au-delà de 100 Mo). Compresser. Pas de HEIC.
- Nom de fichier **URL-safe** : minuscules, sans espaces ni accents, préfixe date + slug.
  Exemple : `2026-11-18_chambre-combles.jpg`
- Pas de visages de clients sans accord, pas de détails de sécurité, pas de zones en chantier.

## URL du média (via jsDelivr)
```
https://cdn.jsdelivr.net/gh/iffickdobrasil/ker-photos@main/<fichier>
```
Exemple : `https://cdn.jsdelivr.net/gh/iffickdobrasil/ker-photos@main/2026-11-18_chambre-combles.jpg`

Le calendrier éditorial se tient dans `posts.csv` (une ligne par média). Laisser
`legende_fr` / `hashtags` vides pour que Claude les rédige.
