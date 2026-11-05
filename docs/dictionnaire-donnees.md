# Dictionnaire des données

> Un champ par ligne, d'après `SUJET.md` et le fichier de `donnees/`. La première ligne sert de modèle.

| Champ | Signification | Type | Règle de validation | Unité | Exemple |
| --- | --- | --- | --- | --- | --- |
| `id` | Identifiant unique | texte | non vide, absent des données | Aucune | O02 |
|`date` | Date de l'opération | Texte | au format `AAAA-MM-JJ` |Aucune | 2026-11-03 |
| `parcelle` | Numéro de la parcelle | Texte | au format `Pnuméro`| Aucune | P3 |
| `culture`| Espèce végétale | Texte | `nom de la culture` | Aucune | tomate |
| `operation` | Travaux techniques | Texte | `nom de l'operaton` | Aucune | arrosage  |
| `coutFCFA` | Dépense enregistrée | Nombre  | un nombre positif ou nul  | FCFA | 3000 |

**Listes de valeurs autorisées** : 

 `id` : O01, O02, O03, O04, O05, O06, O07, O08, O09, O10;
 `date`: 2026-11-03, 2026-11-01, 2026-10-02;
 `parcelle`: P1, P2, P3;
 `culture`: gombo, tomate, aubergine;
 `operation`: semis, repiquage, arrosage, désherbage;
 `coutFCFA`: 1500, 2000, 2500, 3000, 3500, 4000, 4500, 6000, 8000.

**Sources** : 
- Fichier SUJET.md;
- Fichier de donnees/
