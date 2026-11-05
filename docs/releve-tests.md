# Relevé des tests

> Écrivez le résultat attendu avant d'essayer. Un écart n'est pas une faute : notez-le, corrigez, refaites le test.

**Calculs à la main** : refaites à la main les résultats de référence de `SUJET.md`, puis comparez avec votre programme. 

- Total des coûts : 3000 + 4500 + 2000 + 5000 + 1500 + 8000 + 4000 + 3500 + 2500 + 6000 = 40000 FCFA ;
- Coût minimum : 1500 FCFA ;
- Coût maximum : 8000 FCFA ;
- Parcelle P1 : nombre d'opérations = 4 et  coût total = 3000 + 2000 + 8000 + 2500 = 15500 FCFA;
- Parcelle P2 : nombre d'opérations = 3 et  coût total = 4500 + 1500 + 3500 = 9500 FCFA;
- Parcelle P3 : nombre d'opérations = 3 et  coût total = 5000 + 4000 + 6000 = 15000 FCFA;

COMPARAISON ENTRE NOS RESULTATS ET LES RESULTATS DU PROGRAMME:

résultats de la machine: 
Total des coûts : 40000 FCFA
Coût minimum et maximum : { min: 1500, max: 8000 }
Synthèse par parcelle : 
  P1: { nombre: 4, total: 15500 },
  P2: { nombre: 3, total: 9500 },
  P3: { nombre: 3, total: 15000 }

nos résultats:
- Total des coûts : 3000 + 4500 + 2000 + 5000 + 1500 + 8000 + 4000 + 3500 + 2500 + 6000 = 40000 FCFA ;
- Coût minimum : 1500 FCFA ;
- Coût maximum : 8000 FCFA ;
- Parcelle P1 : nombre d'opérations = 4 et  coût total = 3000 + 2000 + 8000 + 2500 = 15500 FCFA;
- Parcelle P2 : nombre d'opérations = 3 et  coût total = 4500 + 1500 + 3500 = 9500 FCFA;
- Parcelle P3 : nombre d'opérations = 3 et  coût total = 5000 + 4000 + 6000 = 15000 FCFA;

CONCLUSION : Après analyse et comparaison de nos résultats avec ceux du programme, nous sommes arrivés à la conclusion suivante:
Nos résultats sont identiques aux résultats de la machine.

**Essais dans le menu** : un ajout valide (encore là après redémarrage), chaque règle refusée, une recherche introuvable, chaque tri, la synthèse, un choix inconnu.

| Action | Attendu | Obtenu | Testeur |
| Une expérience pour lire un test rouge dans `src/outils.js` | True | False | npm run test:outls |
| `git clone` sur le PC d'un condisciple | | | `node app.js`|
| `git clone` sur le PC d'un condisciple| | | `npm test`|
| ✏️ | | | |
| ✏️ | | | |
| ✏️ | | | |
| ✏️ | | | |

**Sur un autre poste** (`git clone`, `node app.js`, `npm test`, en suivant le README) : ✏️
