## Workshop

#### Pré-requis :
Suivre ce cours pour un débutant en informatique :  <a href="https://openclassrooms.com/fr/courses/1946386-comprendre-le-web" target="_blank">Comprendre le web</a>

Tous vos TP(s) doivent être dans le repertoire workshop comme ceci : **C:/workspace/workshop-html/** : 

1. Créer un repertoire workspace dans C: ou /home/nom_de_session
2. Créer un repertoire workshop-html dans workspace
3. Créer un dossier par workshop (Ex: C:/workspace/workshop-html/tp-cv/)

  - [Workshop 1](#workshop-1) : [Maquette cv](tp-cv/maquette.png)
    - Reproduire la maquette en HTML et voici les critères que vous devez respecter :
        - Je dois pouvoir naviguer sur les sections du CV via un menu
        - Je dois pouvoir télécharger le CV au format pdf (mettre le cv pdf en lien de téléchargement)
        - Je dois pouvoir être contacter par un simple clic sur le téléphone et l'email
        - Le CV doit être valide W3C [validateur HTML W3C] (https://validator.w3.org/)
        - Le CV doit être aussi visible sur IE11
        - Le CV doit avoir une favicon (en pièce jointe) et une description exploitable par les moteur de recherche
              
  - [Workshop 2](#workshop-2) : [Maquette recette de cuisine](tp-recipe/maquette.pdf)
    1. Concevoir une page d'accueil avec un titre et les liens suivants :
        - Accueil
        - Voir la recette (doit avoir un lien sur la maquette HTML voir partie 2)
        - Télécharger le document
    2. Reproduire la maquette en HTML et voici les critères que vous devez respecter :
        - Je dois pouvoir naviguer sur les sections de la recette via un menu et prévoir un lien de retour sur la page d'acceuil
        - Le document doit être valide W3C [validateur HTML W3C] (https://validator.w3.org/)
        - La recette doit avoir une favicon (en pièce jointe) et une description exploitable par les moteur de recherche
    
  - [Workshop 3](#workshop-4) : [Lecteur vidéo](tp-player/maquette.jpg)
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
  
 - [Workshop 3 Bis](#workshop-4-bis) : [Lecteur vidéo](tp-player/maquette.jpg)
 
    - Dans le TP précédent, remplacer la video par une iframe youtube https://youtu.be/aqz-KE-bpKQ
    
  - [Workshop 4](#workshop-5) :  [Maquette tableau des médailles](tp-medal-ranking/maquette.png)
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
  - [Workshop 5](#workshop-6) :  [Maquette bon de commande](tp-purchase-order/maquette.pdf)
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
  - [Workshop 6](#workshop-7) : Enoncé formulaire d'inscription
    - Créer un formulaire d'inscription avec les champs suivants, regroupez les champs obligatoires avec la légende "Informations personnelles" et les champs non obligatoire avec la légende "Autre information"
        - Photo 
        - Mr ou Mme (obligatoire, 1 seul choix est possible)
        - Email (obligatoire)
        - Mot de passe (obligatoire)
        - Répétez le mot de passe (obligatoire)
        - Nom (obligatoire)
        - Prénom (obligatoire)
        - Date de naissance  (obligatoire)
        - Téléphone (obligatoire) doit être un numéro français (aidez vous du site https://www.html5pattern.com)
        - Sports favori (liste déroulante avec plusieurs choix possible contenant les valeurs ci dessous avec la création de deux groupes d'options) :
           - Sport individuel
                - Football
                - Basket
                - Handball
                - Rugby 
           - Sport individuel
                - Badminton
                - Judo
                - Tennis
                - Karaté 
                - Ping Pong
                - Athlétisme 
    - Lorsque j'arrive sur le formulaire, le focus doit automatiquement se mettre sur le champs email
    - Ce formulaire doit comporter un bouton d'envoi et de reinitialisation
    - Le formulaire doit être valide W3C [validateur HTML W3C] (https://validator.w3.org/)
    
- [Quiz]: [Cliquez ici](quiz.md)
