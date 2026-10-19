# Byron pour Claude Code

Byron est l'assistant de ciblage B2B de [Build Your Sales](https://buildyoursales.io). Ce plugin le branche sur Claude Code : recherche d'entreprises et de contacts, secteurs, personas, filtres.

Il ne contient aucune clé d'API. La connexion passe par votre compte Build Your Sales (OAuth).

## Installation

Dans Claude Code, lancez ces deux commandes :

```
/plugin marketplace add Build-Your-Sales/byron-plugin
/plugin install byron@build-your-sales
```

Puis relancez la session, ou tapez `/reload-plugins`.

## Connexion

1. Tapez `/mcp`.
2. Choisissez le serveur `byron`.
3. Cliquez sur **Authenticate**. Le navigateur s'ouvre.
4. Choisissez votre espace Build Your Sales.
5. Cliquez sur **Autoriser**.

Le serveur est alors connecté. Les méthodes de Byron apparaissent quand vous tapez `/` et cherchez `byron`.

## Dépenses

Les recherches payantes demandent toujours votre accord : Byron annonce le coût du devis, attend votre oui, et Claude Code affiche en plus sa propre demande de validation. Un changement de devis exige un nouvel accord.

## Révocation

Pour retirer l'accès de Claude Code à votre compte : ouvrez **Applications connectées** dans votre profil, sur https://app.buildyoursales.io/settings/profile, et révoquez l'application. Vous pouvez aussi utiliser **Clear authentication** dans `/mcp`.

## Désinstallation

```
/plugin uninstall byron@build-your-sales
```

## Liens

- Site : https://buildyoursales.io
- Licence : MIT, voir [LICENSE](LICENSE)
