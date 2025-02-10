# MandragoreGUI

**Client graphique pour télécharger des ressources numériques protégées de Mandragore**  
*(Interface utilisateur indépendante permettant de naviguer, zoomer et télécharger des images en haute résolution depuis le site [Mandragore](https://mandragore.bnf.fr/) de la Bibliothèque nationale de France.)*

## Présentation

MandragoreGUI est une application web statique, légère et développée en HTML, CSS et JavaScript. Elle sert d'interface dédiée aux ressources numériques proposées par Mandragore, le portail de la Bibliothèque nationale de France. Ce projet, réalisé de manière indépendante, n'est ni associé ni approuvé par la BnF. MandragoreGUI a pour objectif d'aider les utilisateurs à télécharger des images issues de fichiers protégés, souvent difficiles à sauvegarder directement via l'interface officielle.

## Fonctionnalités

- **Chargement d'Ouvrage :**  
  Saisissez une référence d'ouvrage (par exemple, la valeur par défaut `12148/btv1b52506706r`) pour charger les ressources associées depuis Mandragore.

- **Extraction de la Référence de l'Ouvrage :**  
  Lorsque vous consultez un ouvrage sur le site de Mandragore, par exemple :  
  `https://mandragore.bnf.fr/mirador/ark:/12148/btv1b84192173/f49`  
  Vous devez extraire la référence de l'ouvrage, ici **`12148/btv1b84192173`**.  
  Celle-ci se trouve dans l'URL après `ark:/` et avant le numéro de page (`/f49`). Entrez cette référence dans le champ prévu à cet effet dans l'interface.

- **Navigation Simplifiée :**  
  Utilisez les boutons **Précédent** et **Suivant** pour parcourir les pages, ou saisissez directement un numéro de page pour y accéder instantanément.

- **Affichage en Mode Double et Simple :**  
  L'interface passe automatiquement en mode double page pour une lecture classique, et en mode simple pour la couverture ou la dernière page.

- **Zoom et Déplacement :**  
  Ajustez le niveau de zoom à l'aide des curseurs intuitifs. Cliquez sur une image pour alterner entre le zoom standard et un zoom accru. Lorsqu'une image est zoomée, vous pouvez la déplacer en cliquant-glissant (ou via des gestes tactiles). Un bouton **Réinitialiser** permet de revenir rapidement à la vue par défaut.

- **Téléchargement des Images :**  
  Téléchargez les images en haute résolution grâce aux boutons dédiés. Les fichiers téléchargés possèdent une extension `.highres` bien qu'ils soient au format JPEG (vous pouvez renommer l'extension après téléchargement).

- **Thème Clair/Sombre :**  
  Basculez entre le mode clair et le mode sombre manuellement. L'interface s'adapte également automatiquement aux préférences de votre système.

## Démo en Ligne et Page GitHub

- **Démo en Ligne :**  
  Essayez MandragoreGUI directement via GitHub Pages :  
  [MandragoreGUI Démo](https://bastonus.github.io/MandragoreGUI/)

- **Page GitHub :**  
  Retrouvez le code source et les informations sur le projet sur :  
  [github.com/bastonus/MandragoreGUI](https://github.com/bastonus/MandragoreGUI)

## Utilisation

1. **Charger un Ouvrage :**  
   - Saisissez une référence d'ouvrage valide (par exemple, `12148/btv1b52506706r`) dans le champ dédié.  
   - Cliquez sur le bouton **Charger** pour récupérer l'ouvrage depuis Mandragore.

2. **Extraction de la Référence :**  
   - Lors de la consultation d'un ouvrage sur Mandragore (exemple : `https://mandragore.bnf.fr/mirador/ark:/12148/btv1b84192173/f49`), extrayez la référence de l'ouvrage, ici **`12148/btv1b84192173`**.  
   - Entrez cette référence dans l'interface pour charger les pages correspondantes.

3. **Parcourir les Pages :**  
   - Utilisez les boutons **Précédent** et **Suivant** pour naviguer d'une page à l'autre.  
   - Vous pouvez également saisir directement le numéro de page dans le champ prévu.

4. **Zoomer et Déplacer l'Image :**  
   - Ajustez le zoom à l'aide du curseur situé sous chaque image.  
   - Cliquez sur l'image pour activer ou désactiver le zoom.  
   - En mode zoomé, déplacez l'image en cliquant et glissant (ou en utilisant des gestes tactiles).  
   - Utilisez le bouton **Réinitialiser** pour revenir à la vue par défaut.

5. **Télécharger une Image :**  
   - Cliquez sur le bouton **Télécharger l'image** pour sauvegarder l'image en haute résolution.  
   - Notez que le fichier sera téléchargé avec une extension `.highres`, bien qu'il soit au format JPEG.

## Avertissements

- **Indépendance du Projet :**  
  Ce projet est une initiative indépendante et n'est ni associé ni approuvé par la Bibliothèque nationale de France.

- **Utilisation Responsable :**  
  MandragoreGUI est destiné à faciliter le téléchargement d'images issues de fichiers protégés. Veuillez respecter les droits d'auteur et les conditions d'utilisation des ressources numériques disponibles sur [Mandragore](https://mandragore.bnf.fr/).

## Contribuer

Les contributions et suggestions sont les bienvenues ! Si vous rencontrez des problèmes ou avez des idées d'amélioration, veuillez ouvrir une issue ou soumettre une pull request sur la [page GitHub du projet](https://github.com/bastonus/MandragoreGUI).

## Licence

Ce projet n'inclut pas actuellement de licence. Pour toute question concernant l'utilisation ou la distribution du code, veuillez contacter le propriétaire du dépôt.

## Contact

Pour toute question, retour ou proposition de contribution, veuillez utiliser les issues sur la [page GitHub du projet](https://github.com/bastonus/MandragoreGUI).

## Remerciements

- **Ressources de Mandragore :**  
  Les images en haute résolution fournies par [Mandragore](https://mandragore.bnf.fr/) (Bibliothèque nationale de France) constituent la source de données de cette application.
- Merci à la communauté open source pour les outils et l'inspiration ayant permis la réalisation de ce projet.

---

*Créé par [bastonus](https://github.com/bastonus).*  
*(README mis à jour pour expliquer comment extraire la référence d'un ouvrage depuis Mandragore et pour clarifier l'utilisation du projet pour télécharger des images issues de fichiers protégés.)*