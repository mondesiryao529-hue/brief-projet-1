# Fiche individuelle

> Une page, avant la livraison. Prénom, nom, compte GitHub : 

- Prénoms : YEBOUAH JEAN CLAUDE MONDESIR;
- Nom : YAO;
- Compte Github: mondesiryao529-hue;
 
1. **Une fonction que j'ai écrite**, et comment elle marche :  

la focntion: .join(', ')

.join(', ') est une fonction essentielle en programmation qui sert à transformer un tableau d'éléments en une seule chaîne de caractères, en insérant une virgule et un espace entre chaque élément.

Exemple d'utilisation dans un script

const courses = ['Pommes', 'Bananes', 'Lait', 'Pain'];

// Transformation du tableau en texte
const listeTexte = courses.join(', ');

console.log(listeTexte); 
// Résultat : "Pommes, Bananes, Lait, Pain"

2. **Une difficulté, et sa solution** : 

Difficulté: 
Quelle est la différence entre json.parse et json.stringify?

Solution:
En JavaScript, json.parse et json.stringify font exactement l'inverse l'un de l'autre. json.parse transforme du texte en code tandis que json.stringify transforme du code en texte 

Exemple: cas json.parse

/ 1. Une chaîne de caractères reçue (du texte brut)
const texteRecu = '{"nom":"Bob","age":35,"ville":"Paris"}';

// 2. Transformation en vrai objet JavaScript manipulable
const objetUtilisateur = JSON.parse(texteRecu);

console.log(objetUtilisateur.nom); 
// Résultat : "Bob"

Exemple: cas json.stringify

// 1. Un objet JavaScript classique
const utilisateur = {
    nom: "Alice",
    age: 28,
    estActif: true
};

// 2. Transformation en chaîne de caractères JSON
const versionTexte = JSON.stringify(utilisateur);

console.log(versionTexte);
// Résultat : '{"nom":"Alice","age":28,"estActif":true}'

3. **L'entraide** (qui m'a aidé, qui j'ai aidé, sur quoi) : 

- Qui m'a aidé ?

Liadé Marc Henoc Ebenezer : pour des explicatons sur l'écriture de tout le menu dans app.js et sur le codage dans les fichiers stockage.js et bonus.js;

Harouna Bamba :  pour des séances de coaching entre condisciples et des explicatons sur le codage dans les fichiers registre.js et recherche.js;

Kakeu Zran Bruce :  pour des explicatons sur le codage dans les fichiers synthese.js et saisie.js;

Tiemoko Marie Carmelle : pour des explicatons sur le codage dans le fichier outils.js;

l'Intelligence Artificielle (chat GPT) : pour vérifier l'authenticité des lignes de code à toutes les étapes du projet.

- Qui j'ai aidé ?

Harouna Bamba : pour le lancement de l'app.js et le codage dans le fichier bonus.js;

Kakeu Zran Bruce :  pour le lancement de l'app.js et le codage dans le fichier bonus.js.