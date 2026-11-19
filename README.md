# devops-ci-app

Учебное Flask-приложение для практической работы № 10.

CI последовательно запускает Pylint, pytest, сборку Docker-образа и проверку запущенного контейнера.
При push в main проверенный образ публикуется в GHCR. Pull Request выполняет проверки.

- Проверка состояния — `/health`.
- Образ — `ghcr.io/imp-moce/devops-ci-app`.
- Конвейер — [ci.yml](.github/workflows/ci.yml).
