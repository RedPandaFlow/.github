# RedPandaFlow

Une application de kanban collaboratif.

Inspirée de Trello, RedPandaFlow permet aux équipes d'organiser leur travail en
espaces de travail, tableaux, colonnes et cartes, avec une synchronisation en
temps réel entre collaborateurs.

## Dépôts

- [redpandaflow-backend](https://github.com/RedPandaFlow/redpandaflow-backend) — API web ASP.NET Core (.NET 10), Clean Architecture, EF Core + PostgreSQL, SignalR
- [redpandaflow-frontend](https://github.com/RedPandaFlow/redpandaflow-frontend) — React 19, Vite, Tailwind CSS 4, shadcn/ui
- [redpandaflow-infra](https://github.com/RedPandaFlow/redpandaflow-infra) — stack docker-compose pour lancer tout le projet en local
- [documentation](https://github.com/RedPandaFlow/documentation) — notes d'architecture et de conception

## Fonctionnalités

- Espaces de travail, tableaux, colonnes et cartes avec glisser-déposer
- Synchronisation temps réel entre collaborateurs (présence, mutations de tableau, notifications)
- Commentaires, étiquettes, checklists et assignations sur les cartes
- Historique d'activité par carte
- Notifications avec badge de non-lus pour les événements de carte
- Recherche transverse (espaces, tableaux, cartes)
- Profils utilisateurs avec avatar, suppression de compte
- Rôles sur les espaces et tableaux (Admin, Membre, Lecteur)

## Stack

- ASP.NET Core (.NET 10)
- Entity Framework Core
- PostgreSQL
- React 19
- Vite
- Tailwind CSS
- SignalR
- Docker
