1. Installation et configuration du projet React avec Vite

    Installation de Vite + React

    Structure du projet

    Configuration des variables d’environnement (VITE_API_URL)

    Mise en place d’axios pour communiquer avec ton API backend

    Explication des outils et dépendances nécessaires

2. Base URL API et communication avec le backend

    Comprendre la base URL et son importance

    Création d’un service API avec axios pour appels REST

    Gestion des erreurs d’API et réponses

    Exemple d’appel simple (test de connexion au backend)

    Explication des routes backend disponibles

3. React Hooks essentiels : useState, useEffect, useContext, useNavigate

    useState : gérer l’état local

    useEffect : effets de bord (appels API, lifecycle)

    useContext : partager l’état global (authentification utilisateur)

    useNavigate : navigation programmatique entre pages

    Exemples concrets liés à l’authentification

4. Formulaires React pour l’authentification

    Inscription (Register)

    Connexion (Login)

    Mot de passe oublié (Request Password Reset)

    Réinitialisation du mot de passe (Reset Password)

    Validation des champs avec React Hook Form

    Gestion des erreurs et feedback utilisateur

5. Gestion de la vérification email et renvoi du mail de validation

    Explication du flow de vérification email dans le backend

    Interface utilisateur pour gérer la vérification (page dédiée)

    Fonction pour renvoyer le mail de validation

    Gestion des cas d’erreurs (token expiré, utilisateur non trouvé)

6. Gestion de l’authentification côté client

    Stockage sécurisé du token JWT (cookie httpOnly côté backend)

    Utilisation du contexte React pour stocker l’état utilisateur connecté

    Protection des routes privées (exemple: profil, admin)

    Déconnexion (logout)

    Gestion des erreurs d’authentification (token expiré, non connecté)

7. Mise en place des rôles et autorisations

    Utilisation du middleware backend authorize pour sécuriser les routes

    Gestion des rôles dans le frontend (admin, user, modérateur)

    Affichage conditionnel selon le rôle utilisateur

    Exemple de panneau admin / section modérateur

Bonus : Sécurité, bonnes pratiques et améliorations

    Protection contre attaques CSRF / XSS

    Limitation des requêtes (rate limiter côté backend)

    Validation côté frontend / backend

    UX/UI basique pour guider l’utilisateur

