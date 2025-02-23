# docker-container-template
Template repository for easier definition of new docker containers for apps.

Please remind to locking your dependencies via `poetry.lock`. If your app needs `main.py` feel free to create it.

Please be sure before starting the development:
1. Install needed dependencies in `requirements-dev.txt`
2. Run `pre-commit install`. This will install the hooks in your `.git`.
