# World Classicals Matomo

## Contribution

### Getting started

```sh
cp ./.env.example ./.env
docker-compose up -d app
```

### Automated Git Deployment Setup

```sh
git remote add live ssh://<username>@<ip>/home/<username>/repositories/matomo.git
```

### Deployment

```sh
git push live main
```

### Commands

```sh
make backup # Dump MariaDB databases
make restore # Restore MariaDB databases
```
