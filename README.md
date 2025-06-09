# azure-ad-demo-public

Démo simple d’un flux d’authentification OAuth 2.0 / OpenID Connect avec Microsoft Azure AD (MSAL.js).

## 🌐 Démo

Interface Web HTML/JS permettant de :
- Se connecter avec un compte Microsoft
- Récupérer l’ID Token, Access Token, et d’autres informations du compte
- Renouveler automatiquement l’Access Token via MSAL

## 🖼️ Capture d’écran

Aperçu de l’interface utilisateur :

![Étape 1](docs/screenshots/1.png)

➡️ La documentation complète contient toutes les captures étape par étape.

## 📘 Documentation complète

👉 [Voir le guide avec instructions + images](docs/setup.md)

## 🛠️ Technologies utilisées

- HTML / CSS / JavaScript
- [MSAL.js (Microsoft Authentication Library)](https://github.com/AzureAD/microsoft-authentication-library-for-js)

## 🚀 Lancer le projet en local

2. Ouvrir `index.html` dans un navigateur

3. Modifier la configuration dans le fichier pour insérer votre propre `clientId` et `tenantId` :

```js
const msalConfig = {
  auth: {
    clientId: "VOTRE_CLIENT_ID",
    authority: "https://login.microsoftonline.com/VOTRE_TENANT_ID",
    redirectUri: window.location.href
  }
};

