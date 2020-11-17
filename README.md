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
        - Le CV doit être valide W3C [validateur HTML W3C] (https://validator.w3.org/)
        - Le CV doit être aussi visible sur IE11
        - Le CV doit avoir une favicon (en pièce jointe) et une description exploitable par les moteur de recherche
        
  - Workshop 3 : Emploi du temps (a venir)
  - Workshop 4 : [Maquette tableau des médailles](tp-medal-ranking/maquette.png)
    - Reproduire la maquette en HTML et voici les critères que vous devez respecter : 
        - Le CV doit être valide W3C [validateur HTML W3C] (https://validator.w3.org/)
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
  - Workshop 5 : [Maquette bon de commande](tp-purchase-order/maquette.pdf)
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
  - Workshop 6 : Maquette formulaire d'inscription
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
