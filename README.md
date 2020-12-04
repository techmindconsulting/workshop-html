## Workshop
### HTML

#### Pré-requis :
Tous vos TP doivent être dans le repertoire workshop comme ceci : **C:/workspace/workshop-html/** : 

1. Créer un repertoire workspace dans C:
2. Créer un repertoire workshop-html dans workspace
3. Créer un dossier par workshop (Ex: C:/workspace/workshop-html/tp-cv/)

  - Workshop 1 : [Maquette cv](tp-cv/maquette.pdf)
    - Reproduire la maquette en HTML et voici les critères que vous devez respecter :
        - Je dois pouvoir naviguer sur les section du CV via un menu
        - Je dois pouvoir télécharger le CV au format pdf (mettre le cv pdf en lien de téléchargement)
        - Je dois pouvoir être contacter par un simple clic sur le téléphone et l'email
        - Le CV doit être valide W3C [validateur HTML W3C] (https://validator.w3.org/)
        - Le CV doit être aussi visible sur IE11
        - Le CV doit avoir une favicon (en pièce jointe) et une description exploitable par les moteur de recherche
              
  - Workshop 2 : [Maquette recette de cuisine](tp-recipe/maquette.pdf)
    - Reproduire la maquette en HTML et voici les critères que vous devez respecter :
        - Je dois pouvoir naviguer sur les section du CV via un menu
        - Je dois pouvoir télécharger le CV au format pdf (mettre le cv pdf en lien de téléchargement)
        - Je dois pouvoir être contacter par un simple clic sur le téléphone et l'email
        - Le document doit être valide W3C [validateur HTML W3C] (https://validator.w3.org/)
        - Le document doit être aussi visible sur IE11
        - Le CV doit avoir une favicon (en pièce jointe) et une description exploitable par les moteur de recherche
        
  - Workshop 3 : [Planning](tp-planning/maquette.png)
    - Reproduire la maquette en HTML et voici les critères que vous devez respecter, les images, un fichier html vierge et le style sont fournit [Cliquez-ici](tp-planning):
        - L'image du planning doit être cliquable sur deux zones: 
        
            1 - Je dois avoir la bonne structure html de tel sorte que ma page s'affiche comme sur la maquette
            
            2 - La zone verte de David Tremblay, lorsque je clique elle doit me rediriger vers un lien wikipedia aleatoire sur un nouvel onglet
            
            3 - La zone jaune de Julie Lebon, lorsque je clique elle doit me rediriger vers un autre lien wikipedia aleatoire sur un nouvel onglet
            
         - Les images de profil doivent faire 100 pixels de largeur
         - Le document doit être validate W3C
         
    - Rappel : Comment obtenir les coordonées ? https://www.image-map.net/
  - Workshop 4 : [Lecteur vidéo](tp-player/maquette.jpg)
    - Reproduire la maquette en HTML, tous les éléments dont vous avez besoin sont à télécharger [ici](tp-player)
    - Copier coller le style dans la balise <head></head> 
    ```
            <style>
            * {
                margin: 0;
                padding: 0;
            }

            html {
                font-family: "Roboto", sans-serif;
            }

            video {
                outline: none;
            }
            
            section {
                margin: 32px;
                width: 640px;
            }

            h1 {
                margin: 16px 0;
            }

            p {
                padding-bottom: 16px;
            }

            h1 + p {
                color: grey;
                font-size: medium;
                border-bottom: 1px solid lightgrey;
            }

            h2 {
                margin-top: 8px;
                font-size: 14px;
            }

            h3 {
                margin: 12px 0;
                font-size: 12px;
            }
            
            div.description {                
                line-height: 1.4rem;
            }
        </style>
    ```
    - Voici les critères que vous devez respecter :
        - Je dois pouvoir afficher une video qui ne démarre pas automatique.
        - Je dois pouvoir voir la vignette de la vidéo
        - Je dois pouvoir gérer le format mp4 et ogg
        - Je dois pouvoir voir un message d'avertissment si le format de la vidéo n'est pas supporté
        - Le document doit être valide W3C [validateur HTML W3C] (https://validator.w3.org/)
  
  - Workshop 5 : [Maquette tableau des médailles](tp-medal-ranking/maquette.png)
    - Reproduire la maquette en HTML et voici les critères que vous devez respecter : 
        - Le document doit être valide W3C [validateur HTML W3C] (https://validator.w3.org/)
        ```
        <style>
            table {
              border: 1px solid black;
              border-collapse: collapse;
            }
            th, td {
              padding: 15px;
              text-align: left;
            }
          th {
              background-color: #4CAF50;
              color: white;
          }
        </style>
        ```
  - Workshop 6 : [Maquette bon de commande](tp-purchase-order/maquette.pdf)
    - Reproduire le bon de commande en HTML et voici les critères que vous devez respecter :
        - Le code du style doit être copié collé dans l'en-tête de votre document HTML
        ```
        <style>
            html {
              font-family: sans-serif;
            }

            body {
                height: 100%;
            }

            caption {
              caption-side: bottom;
              text-align: right;
            }

            tbody tr:nth-child(odd) {
                background-color: gainsboro;
            }
            tbody tr:nth-child(even) {
                background-color: ghostwhite;
            }

            table {
                table-layout: fixed;
                width: 100%;
                border: 1px solid black;
                border-collapse: collapse;
            }
            tr {
                background-color: #f8f6ff
            }
            th, td {
                padding-right: 5%;
                text-align: center;
                border: 1px solid black;
                letter-spacing: 1px;
            }
            th {
                font-size: 18px;
                color: #fff;
                background-color: #393939;
                padding-top: 18px;
                padding-bottom: 18px;
                text-transform: capitalize;
                letter-spacing: 2px;

            }
            td {
                font-size: 18px;
                color: #000000;
                line-height: 1.4;
                padding-top: 16px;
                padding-bottom: 16px;
            }

            tfoot th {
                text-align: right;
            }
        </style>
        ``` 
  - Workshop 7 : Maquette formulaire d'inscription
    - Créer un formulaire d'inscription avec les champs suivants :
        - Email (obligatoire)
        - Mot de passe (obligatoire)
        - Répétez le mot de passe (obligatoire)
        - Nom (obligatoire)
        - Prénom (obligatoire)
        - Date de naissance  (obligatoire)
        - Téléphone (obligatoire)
        - Couleur préféré
        - Photo
        - Site internet
    - Le formulaire doit être valide W3C [validateur HTML W3C] (https://validator.w3.org/)
