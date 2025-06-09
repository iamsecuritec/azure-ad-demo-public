# Guide de configuration Azure AD pour MSAL.js

## 1. Créer l'application dans Azure AD

1. Connectez-vous au [Portail Azure](https://portal.azure.com)
2. Accédez à **Azure Active Directory > Inscriptions d'applications > Nouvelle inscription**
3. Renseignez le nom de l’application et le **Redirect URI** (`http://localhost` pour local)

📸  
![Création app Azure](./screenshots/step1-create-app.png)

---

## 2. Récupérer les informations

- Copiez le **Client ID** (ID de l'application)
- Copiez le **Tenant ID** (ID de l’annuaire)

---

## 3. Modifier le fichier HTML

Dans `index.html`, remplacez dans `msalConfig` :

```js
clientId: "VOTRE_CLIENT_ID",
authority: "https://login.microsoftonline.com/VOTRE_TENANT_ID",
