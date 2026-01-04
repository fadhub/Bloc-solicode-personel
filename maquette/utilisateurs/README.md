# Maquette Gestion des Utilisateurs

## Prompt
Concevoir une interface d'administration pour la gestion des utilisateurs d'un blog, en utilisant Tailwind CSS. 
L'interface doit inclure :
- Une barre latérale (Sidebar) pour la navigation (Dashboard, Articles, Catégories, Tags, Utilisateurs).
- Une barre de navigation supérieure (Navbar) avec recherche et profil utilisateur.
- Une section principale affichant la liste des utilisateurs sous forme de tableau responsive.
- Des fonctionnalités de filtrage par Rôle et Statut via des menus déroulants personnalisés.
- Une fonctionnalité de recherche par nom.
- Des actions CRUD via des fenêtres modales (Modals) :
  - Ajouter un utilisateur (Nom, Email, Mot de passe, Rôle).
  - Modifier un utilisateur.
  - Assigner un rôle.
  - Activer/Désactiver un utilisateur.
  - Supprimer un utilisateur.
- Le design doit être moderne, épuré ("clean"), et supporter le mode sombre (Dark Mode).

## Liste des Composants
Les composants suivants sont intégrés dans cette maquette :

1.  **Sidebar (Barre latérale)**
    - Logo SolicodeBlog.
    - Navigation groupée (Main, Contenu, Système).
    - Liens actifs/inactifs.

2.  **Navbar (Barre de navigation)**
    - Logo mobile.
    - Barre de recherche.
    - Dropdown de profil utilisateur.

3.  **UserTable (Tableau des utilisateurs)**
    - En-têtes de colonnes.
    - Lignes de données (Avatar/Nom, Email, Rôle, Statut, Actions).
    - Boutons d'action (Modifier, Role, Statut, Supprimer).

4.  **Filters (Filtres)**
    - Dropdown "Tous les rôles".
    - Dropdown "Tous les statuts".
    - Barre de recherche "Rechercher par nom".

5.  **Modals (Fenêtres modales)**
    - **UserFormModal** : Utilisé pour Ajouter et Modifier un utilisateur (formulaire dynamique).
    - **RoleAssignmentModal** : Pour changer le rôle d'un utilisateur specifique.
    - **ConfirmationModal** : Utilisé pour confirmer les actions de Suppression et changement de Statut.

6.  **Pagination**
    - Contrôles de pagination dynamique.
