# Registre des opérations maraîchères

> Projet individuel du SAS DFS, brief 1 (sujet : [SUJET.md](SUJET.md)). Remplacez chaque ✏️ par votre texte, puis supprimez cette ligne.

## Contexte

1-Le registre des opérations maraîchères est utilisé par les producteurs, les chefs d’exploitation, les techniciens, les agronomistes, les coopératives et les chercheurs;

2-Il sert principalement à documenter chaque opération agricole pour faciliter l’analyse technique et économique des cultures;

3-On y saisit l’identifiant de l’opération, la date, le lieu, le type d’intervention, la culture, la parcelle, les détails techniques, les coûts et les observations;

4-Le registre affiche le total des coûts, les coûts minimum et maximum, ainsi que les totaux par parcelle ou par culture;

5-Il permet aussi de trier les opérations par date ou par coût et de filtrer par type d’intervention;

6-Certaines versions offrent la recherche par identifiant, parcelle ou culture et l’affichage de références agronomiques;

7-En revanche, le registre n’affiche pas les revenus, les bénéfices, les marges ni les données nécessaires pour calculer la rentabilité;

8-Il ne fournit pas non plus les quantités récoltées, les surfaces exploitées, les volumes d’eau ou des conseils agronomiques, et certaines versions limitent la modification ou la suppression des opérations.

## Prérequis et lancement

- Node.js 20 ou plus récent, Git ; aucune bibliothèque à installer.

```bash
git clone https://github.com/VOTRE-COMPTE/brief-1-registre-maraicher.git
cd brief-1-registre-maraicher
node app.js
npm test
```

Sous PowerShell, si `npm` est bloqué : `npm.cmd test`.

## Fonctionnalités

✏️ *Cochez seulement ce qui marche : `- [x]`.*

- [x] Données lues et enregistrées dans `donnees/operations.json`
- [x] Ajouter une opération, saisies invalides refusées sans arrêter le programme
- [ ] Lister les opérations, message si le registre est vide
- [x] Rechercher par identifiant ou par parcelle ; filtrer par culture
- [x] Trier par coût ou par date
- [x] Synthèse : total, nombre et total par parcelle, coût minimum et maximum
- [x] Bonus : supprimer et modifier une opération (choix 6 et 7)
- [x] Bonus : tri par coût décroissant, parcelle la plus coûteuse

## Données

- Le fichier: operations.json;
- Le nombre d'opérations: 4;
- Les champs: id, date, parcelle, culture, operation, coutFCFA;
- Les unités: Aucune, FCFA;

Note: Les données contenues dans le fichier operation.js sont des données fictives.

## Limites

1-Le registre des opérations maraîchères ne fournit pas de conseils de culture;
2-Le registre des opérations maraîchères ne fournit pas des mesures de performance agronomique;
3-Le registre des opérations maraîchères n’affiche pas des données financières complètes (affiche les dépenses mais pas les revenus).

## Documents

[Dictionnaire des données](docs/dictionnaire-donnees.md) · [Tâches](docs/taches.md) · [Relevé des tests](docs/releve-tests.md) · [Journal de recherche](docs/journal-recherche.md) · [Fiche agronomique](docs/fiche-agronomique.md) · [Fiche individuelle](docs/fiche-individuelle.md)

## Auteur

- Prénoms : YEBOUAH JEAN CLAUDE MONDESIR;
- Nom : YAO;
- Compte Github: mondesiryao529-hue;

- Entraide:

Liadé Marc Henoc Ebenezer : pour des explicatons sur l'écriture de tout le menu dans app.js et sur le codage dans les fichiers stockage.js et bonus.js;

Harouna Bamba :  pour des séances de coaching entre condisciples et des explicatons sur le codage dans les fichiers registre.js et recherche.js;

Kakeu Zran Bruce :  pour des explicatons sur le codage dans les fichiers synthese.js et saisie.js;

Tiemoko Marie Carmelle : pour des explicatons sur le codage dans le fichier outils.js;

l'Intelligence Artificielle (chat GPT) : pour vérifier l'authenticité des lignes de code à toutes les étapes du projet. 