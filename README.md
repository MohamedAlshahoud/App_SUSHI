# App_SUSHI-FUJI
Mise en service **d'une application de commande (POS)** avec **Loyverse** pour **un restaurant**.

---

## 🎯 1. OBJECTIF DU PROJET
**L'objectif** principal était d'établir **un système de commande**, **de gestion de tickets** et **d'impression pour la cuisine** qui soit **100% fonctionnel et gratuit (sans frais d'abonnement mensuel)**, en utilisant l'application **Loyverse** **POS** et **l'imprimante thermique** existante du restaurant.

## 🛠️ 2. FONCTIONNALITÉS CLÉS ET CONFIGURATION
**Le système** a été configuré pour optimiser **la vitesse** de prise de **commande** et **la communication avec la cuisine**.

### 2.1. Logiciel de Commande Mobile (Loyverse POS)
* **Plateforme :** Application **mobile** gratuite (**Android/iOS**).
* **Rôle Principal :** Permet la **prise de commande rapide** à la table ou au comptoir, **la création de tickets** ouverts et **l'enregistrement des transactions**.
* **Accès Sécurisé :** Les serveurs accèdent à **l'application mobile** via un code **PIN** simple pour **déverrouiller l'écran** et **envoyer les commandes**.

### 2.2. Configuration du Back Office
| Fonctionnalité | Description |
| :--- | :--- |
| **Gestion des Articles** | **Création** et **structuration** complète du **menu** avec **des prix**. |
| **Catégories** | **Création de catégories** claires (**Sushi**, **Entrée**, **Boissons**, **Plateau**, **etc**.) pour une navigation rapide. |
| **Tickets Ouverts** | **Activé**. Permet d'ouvrir une commande pour une table et de la modifier sans paiement immédiat. Essentiel pour le service à table. |
| **Langue du Reçu** | Français. |
| **Personnalisation** | Configuration de l'En-tête (Nom, Adresse, Téléphone) et du Bas de page ("Merci pour votre visite...") sur le reçu. |

### 2.3. Optimisation Mobile
* **Affichage sur l'écran du Serveur :** Configuration d'une **Page Personnalisée (Grille)** sur l'application mobile pour afficher directement les **Catégories** comme de gros boutons (Entrée, Boissons, Sushi, etc.). Ceci élimine l'étape de sélection du menu déroulant.
* **Sécurité Mobile :** Configuration d'un **code PIN** simple pour déverrouiller l'écran de **caisse** après l'ouverture de l'application.

---
