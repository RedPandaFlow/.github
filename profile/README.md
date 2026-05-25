# RedPandaFlow

A collaborative kanban application.

Inspired by Trello, RedPandaFlow lets teams organise work in workspaces,
boards, columns, and cards, with real-time updates across collaborators.

## Repositories

- [redpandaflow-backend](https://github.com/RedPandaFlow/redpandaflow-backend) — ASP.NET Core 8 Web API, Clean Architecture, EF Core + PostgreSQL, SignalR
- [redpandaflow-frontend](https://github.com/RedPandaFlow/redpandaflow-frontend) — React 19, Vite, Tailwind CSS 4, shadcn/ui
- [redpandaflow-infra](https://github.com/RedPandaFlow/redpandaflow-infra) — docker-compose stack to run the whole project locally
- [documentation](https://github.com/RedPandaFlow/documentation) — architecture and design notes

## Features

- Workspaces, boards, columns, cards with drag and drop
- Real-time sync across collaborators (presence, board mutations, notifications)
- Comments, labels, checklists, assignees on cards
- Per-card activity timeline
- Notifications with unread badge for card events
- Search across workspaces, boards, and cards
- User profiles with avatar upload, account deletion
- Workspaces and boards roles (Admin, Member, Viewer)

## Stack

- ASP.NET Core 8
- Entity Framework Core
- PostgreSQL
- React 19
- Vite
- Tailwind CSS
- SignalR
- Docker
