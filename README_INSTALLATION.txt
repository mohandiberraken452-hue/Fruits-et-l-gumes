AGRO DZ MARKETPLACE — DEMONSTRATION GITHUB PAGES
================================================

CE QUE CONTIENT LE ZIP
- index.html : page principale
- styles.css : design responsive
- app.js : catalogue, panier, espace producteur, commandes de demonstration
- assets/ : 12 photos de produits creees pour cette demonstration
- favicon.svg, .nojekyll

FONCTIONNALITES
- Francais / arabe (RTL)
- Fruits et legumes frais ; fruits et legumes seches / transformes
- Catalogue, recherche, filtres, details et panier
- Liste de producteurs
- Espace producteur : fiche et ajout de produit avec photo locale
- Commande : acheteur industriel, commercant ou particulier
- Option transport et adresse de livraison
- Confirmation et suivi des commandes avec changement de statut simule
- Donnees de demonstration conservees localement dans le navigateur

IMPORTANT : PAS DE COMMERCE REEL
Aucun serveur, aucune base de donnees, aucune authentification reelle.
Les commandes ne sont transmises a personne. Aucun paiement ni livraison.
Les donnees en localStorage restent sur le meme navigateur et peuvent etre
perdues si l'utilisateur efface les donnees de navigation. Les produits ajoutes
ne sont PAS visibles sur les autres telephones ou ordinateurs.
Ne pas saisir de vraies donnees personnelles dans cette demonstration.
Les prix, stocks et profils de producteurs precharges sont fictifs.
Les photos de produits sont des images illustratives generees pour ce prototype.

PUBLIER SUR GITHUB PAGES
1. Creez un depot GitHub public, par exemple AGRO-DZ-DEMO.
2. Decompressez le ZIP sur votre ordinateur.
3. Sur GitHub, ouvrez le depot, cliquez Add file > Upload files.
4. Envoyez LE CONTENU du dossier decompresse (index.html a la racine),
   y compris le dossier assets et le fichier .nojekyll.
5. Cliquez Commit changes.
6. Settings > Pages > Source: Deploy from a branch > main > /(root) > Save.
7. Apres publication, ouvrez :
   https://VOTRE-COMPTE.github.io/AGRO-DZ-DEMO/
   Le nom dans l'URL doit correspondre exactement au nom du depot.

POUR TESTER EN LOCAL
Ouvrez index.html dans un navigateur moderne. Les fonctionnalites principales
fonctionnent sans connexion Internet ; les polices peuvent utiliser une police
locale si Google Fonts est inaccessible.

CONSERVATION DES DONNEES
Le depot GitHub conserve les fichiers publics, independamment du PC allume.
Les produits et commandes crees par les visiteurs ne sont PAS sauvegardes sur
GitHub. Pour une vraie plateforme multi-utilisateurs, il faudra une API et une
base de donnees sur un hebergement adapte.
