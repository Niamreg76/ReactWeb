# ReactWeb Roman Germain

# Guide de Lancement du Conteneur Docker

## Prérequis

- Docker installé sur votre machine ([Télécharger Docker](https://www.docker.com/products/docker-desktop))

## Étapes

1. **Construire l'Image Docker :**
   - Ouvrez un terminal dans le répertoire de votre projet.
   - Utilisez la commande suivante pour construire l'image Docker :
     ```bash
     docker build -t monapp:laters .
     ```
   - Assurez-vous que le point à la fin de la commande est bien présent.

2. **Lancer le Conteneur :**
   - Accédez à l'interface Docker, allez dans "Images", puis appuyez sur la flèche pour "Run" l'image que vous venez de construire.
   - Une fois le conteneur créé, cliquez sur le nom du conteneur pour voir les logs.

3. **Vérifier les Logs :**
   - Dans les logs du conteneur, vous verrez des informations telles que l'URL locale et l'URL sur votre réseau où l'application est disponible. Par exemple :
     ```plaintext
     2023-12-06 11:54:39 Local: http://localhost:3000/ReactWeb
     2023-12-06 11:54:39 On Your Network: http://172.17.0.2:3000/ReactWeb
     ```

4. **Accéder à l'Application :**
   - Ouvrez un navigateur web et accédez à l'une des URL fournies dans les logs.
   - Cliquez sur le lien pour afficher l'interface de votre application.


Il est également possible d'accéder à la version githubPages : https://niamreg76.github.io/ReactWeb/
