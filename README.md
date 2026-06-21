# PROC-002 — Réinitialisation d'un mot de passe
## Objectif
Réinitialiser le mot de passe d'un utilisateur Active Directory afin de lui permettre de retrouver l'accès à son compte.

## Prérequis

* Disposer des droits d'administration Activce Directory
* Être connecté à un contrôleur de domaine ou à un poste d'administration
* Vérifier l'identité de l'utilisateur selon la précédure interne

## Procdéure

### 1. Ouvrir la console Active Directory

```cmd
dsa.msc
```

La console "Utilisateurs et ordinateurs Activce Directory" s'ouvre.

### 2. Rechercher l'utilisateur

* Naviguer dans l'arborescence du domaine
* Localiser l'utilsateur concerné

Ou utiliser la fonction de recherche :

```text
Action
-> Rechercher
```

Sélectionner le compte utilisateur.

### 3. Réinitialiser le mot de passe

* Clic droit sur l'utilisateur
* Réinitialiser le mot de passe

Saisir un nouveau mot de passe temporaire.

### 4. Configurer les options de connexion

Cocher :

* L'utilisateur doit changer le mot de passe à la prochaine ouverture de session.

Vérifier que :

* Le comtpe est activé
* Le compte n'est pas verrouillé
 
Si nécessaire :

* Déverouiller le compte utilisateur

Cliquer sur "OK" .

### 5. Informer l'utilisateur 

Communiquer le mot de passe temporaire selon la procédure de sécurité en vigueur.

Informer l'utilisateur :

* Qu'un changement de mot de passe sera demandé lors de la prochaine connexion
* De ne pas partager ses identifiants

## Validation

La procédure est considérrée comme réussie lorsque :

* L'utilisateur peut se connecter avec le mot de passe temporaire
* Le changement de mot de passe est demandé à la connexion
* Aucun verrouillage du compte n'est constaté

## Compétences démontrées

* Administration Active Directory
* Gestion des comptes utilisateurs
* Gestion des identitées
* Support utilisateurs
* Sécurité des accès
* Windows Server



  
