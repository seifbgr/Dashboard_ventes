Analyse des Ventes avec Power BI
Description du projet
Ce projet vise à créer un tableau de bord interactif avec Power BI pour analyser les performances de vente d'une entreprise sur une période de quatre mois. Grâce à l'analyse des données, nous répondrons aux principales questions commerciales pour guider les décisions stratégiques.

Business Model
Les clients peuvent passer des commandes en ligne pour divers produits vendus par l'entreprise.
L'entreprise livre les produits dans les plus brefs délais, en fonction de l'adresse du client.
Modes de paiement proposés :
Paiement à la livraison
Paiement en ligne au moment de la commande
Politique de retour : sous 10 jours après la réception de la commande.
Jeu de données
L'analyse s'appuie sur des données contenues dans quatre fichiers CSV représentant les ventes sur quatre mois :

Janvier 2019
Février 2019
Mars 2019
Avril 2019
Colonnes des fichiers CSV
Order ID : Identifiant unique de chaque commande.
Product : Nom du produit commandé.
Quantity Ordered : Quantité commandée.
Price Each : Prix unitaire du produit.
Order Date : Date de la commande.
Purchase Address : Adresse de livraison du client.
Questions commerciales
Le tableau de bord Power BI répondra aux questions suivantes :

Quels sont les Top/Bottom 5 produits par ventes ?
Comment les ventes se répartissent-elles par région ?
Quels sont les détails des produits pour une commande donnée ?
Quelle est l'évolution du nombre de commandes par date ?
Quelle est la répartition des ventes par mois ?
Combien de commandes par mois ont été passées ?
Quelle est la relation entre les ventes et la quantité commandée ?
Méthodologie
Document des exigences métier (BRD) : Définir les objectifs et les besoins commerciaux.
Collecte des données : Importer les fichiers CSV contenant les données de vente.
Nettoyage/Transformation des données : Traiter les données pour assurer leur qualité (ex. gestion des doublons, conversion des formats).
Modélisation des données : Établir les relations entre les tables et structurer les données pour l'analyse.
Fonctions DAX : Créer des mesures et colonnes calculées pour une analyse approfondie.
Rapport UI : Créer une interface utilisateur intuitive et interactive.
RLS (Sécurité au niveau des lignes) : Implémenter des restrictions d'accès basées sur les rôles.
Créer un espace de travail et fournir l'accès : Configurer un espace collaboratif sur Power BI Service.
Publier le rapport : Télécharger le rapport Power BI Desktop vers le service Power BI.
Vue tableau de bord/mobile : Adapter le rapport pour un affichage mobile et tableau de bord.
Passerelle (Gateway) : Configurer une connexion pour les sources de données locales.
Planifier l'actualisation : Automatiser la mise à jour des données.
S'abonner, gérer les alertes : Activer des abonnements et des notifications basées sur des seuils.
Partager le rapport : Diffuser le tableau de bord auprès des parties prenantes.
Livrables
Tableau de bord Power BI interactif répondant aux questions commerciales.
Documentation technique décrivant la modélisation des données, les calculs DAX et la méthodologie suivie.
Vue mobile optimisée pour un accès rapide aux données clés.
