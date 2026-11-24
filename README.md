# devops-ci-app-turanov

Учебное Flask-приложение для практической работы № 10.

CI: Pylint → pytest → Docker build → smoke-test → GHCR.

Публикация образа выполняется только из `main`.
В Pull Request выполняются проверки без публикации.

- health endpoint: `/health`;
- образ: `ghcr.io/im2high/devops-ci-app-turanov`;
- основной workflow: `.github/workflows/ci.yml`.
