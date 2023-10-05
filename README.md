# cicd-poly-2023

Répertoire git pour l'introduction CI/CD!

## Commandes .NET

```shell
$ dotnet new webapp --output MyCoolWebApp
$ dotnet new xunit --output MyCoolTests
$ dotnet new sln
$ dotnet sln add MyCoolWebApp MyCoolTests
```

## Étapes Azure
1. Créer Linux WebApp
2. Download publish profile
3. Créer GH Action secret AZURE_WEBAPP_PUBLISH_PROFILE