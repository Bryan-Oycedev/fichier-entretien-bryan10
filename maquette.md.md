**# Projet : Application "Boutique Amina"**



Ce dépôt contient le dossier complet d'analyse de besoins et de conception réalisé pour Mme Amina au Marché Mokolo (Yaoundé).



\##  Fiche Besoins Complète (Les 11 rubriques)

1\. \*\*Client et contexte :\*\* Mme Amina, boutique au Marché Mokolo, entretien réalisé le lundi 2 novembre 2026 à 14h00 (durée : 35 minutes).

2\. \*\*Problème :\*\* Comment pourrions-nous aider Mme Amina à suivre ses commandes, son stock et ses paiements sans se perdre dans WhatsApp et ses cahiers ?

3\. \*\*Acteurs et persona :\*\* Amina (38 ans, smartphone Android, pas d'ordinateur), sa vendeuse, les clientes, les fournisseurs et le livreur moto.

4\. \*\*Situation actuelle :\*\* Processus manuel et fragmenté à l'aide de 3 cahiers distincts. Blocage critique à l'étape finale d'enregistrement de la commande.

5\. \*\*Informations manipulées :\*\* Produits (nom, photo, prix, taille, stock), Commandes (date, cliente, produit, quantité, montant total, statut), Clientes (nom, téléphone, dettes).

6\. \*\*Besoins fonctionnels :\*\* Priorisés de BF-01 à BF-09 selon la grille MoSCoW.

7\. \*\*Besoins non fonctionnels :\*\* Performance sur environnement mobile Android standard, interface épurée en français avec des gros boutons d'action.

8\. \*\*User stories :\*\* Focus sur les trois actions indispensables de gestion (Ajout de produit, Enregistrement de vente, Suivi des dettes).

9\. \*\*Contraintes :\*\* Budget nul (0 FCFA), utilisation exclusive sur smartphone, absence d'ordinateur, timing de réalisation court d'une semaine.

10\. \*\*Solution et maquettes :\*\* Application "Boutique Amina" découpée en 3 écrans distincts calibrés en FCFA (voir détails ci-dessous).

11\. \*\*Retours du test :\*\* Prise en compte immédiate des demandes d'ajustements ergonomiques (bouton d'appel rapide et alerte visuelle de stock).



\---



\## **Descriptif Technique des Maquettes (Étalonnées en FCFA)**



La solution se compose de 3 écrans épurés conçus pour correspondre aux habitudes de l'utilisatrice :



\### Maquette 1 - Catalogue

\* \*\*Description :\*\* Liste en grille des robes avec photo, taille et prix exacts (\*\*12 500 FCFA\*\*, \*\*9 500 FCFA\*\*, \*\*7 500 FCFA\*\*).

\* \*\*Éléments visuels :\*\* Pastille verte (En stock) ou rouge (Rupture). Un grand bouton flottant `\[+ Ajouter produit]` est accessible en bas.

\* \*Lien besoin : BF-01.\*



\### Maquette 2 - Nouvelle commande

\* \*\*Description :\*\* Formulaire de saisie ultra-rapide. On sélectionne la cliente, la robe concernée (ex: \*\*12 500 FCFA\*\*), la quantité, puis on bascule l'interrupteur entre `\[Payé]` ou `\[Non payé / Dette]`.

\* \*\*Action :\*\* Grand bouton de validation `\[Enregistrer la commande]`.

\* \*Lien besoin : BF-02 et BF-04.\*



\### Maquette 3 - Mes commandes

\* \*\*Description :\*\* Historique chronologique des transactions du jour. Le haut de l'écran affiche clairement le résumé financier : \*\*Total du jour : 25 000 FCFA\*\*.

\* \*\*Actions de relance :\*\* Chaque ligne de commande marquée comme "Dette" dispose de deux boutons d'action directs : `\[WhatsApp]` et `\[Appeler]`.

\* \*Lien besoin : BF-03 et BF-04.\*













