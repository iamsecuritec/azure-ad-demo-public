# azure-ad-demo-public

Démo simple d’un flux d’authentification OAuth 2.0 / OpenID Connect avec Microsoft Azure AD (MSAL.js).

## 🌐 Démo

Interface Web HTML/JS permettant de :
- Se connecter avec un compte Microsoft
- Récupérer l’ID Token, Access Token, et d’autres informations du compte
- Renouveler automatiquement l’Access Token via MSAL

## 🖼️ Aperçu de l’interface utilisateur

Voici deux écrans clés de l'application web :

### 1️⃣ Page de connexion

![Page de connexion](docs/screenshots/login.png)

---

### 2️⃣ Interface principale après connexion

![Interface principale](docs/screenshots/dashboard.png)

➡️ L'utilisateur connecté peut consulter ses informations d'identité, ID Token, Access Token, et renouveler son jeton.

🔐 Cette interface est générée dynamiquement à l'aide de [MSAL.js](https://github.com/AzureAD/microsoft-authentication-library-for-js).


➡️ La documentation complète contient toutes les captures étape par étape.

## 📘 Documentation complète

👉 [Voir le guide avec instructions + images](docs/setup.md)

## 🛠️ Technologies utilisées

- HTML / CSS / JavaScript
- [MSAL.js (Microsoft Authentication Library)](https://github.com/AzureAD/microsoft-authentication-library-for-js)

## 🚀 Lancer le projet en local

1. Cloner le dépôt :

```bash
git clone https://github.com/antoniofos88/azure-ad-demo-public.git
cd azure-ad-demo-public
