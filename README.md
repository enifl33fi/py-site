# py-site
[![prod](https://github.com/enifl33fi/py-site/actions/workflows/prod.yml/badge.svg?branch=master)](https://github.com/enifl33fi/py-site/actions/workflows/prod.yml)

Статический сайт для публикации результатов исследований.

- Сайт (GitHub Pages): https://enifl33fi.github.io/py-site/
- Сайт (Helios): https://se.ifmo.ru/~s367380/py-site/

## Локальный запуск

    python -m venv .venv
    source .venv/Scripts/activate
    pip install -r requirements.txt
    mkdocs serve

## Сборка

    mkdocs build -f mkdocs.github.yml --strict
    mkdocs build -f mkdocs.helios.yml --strict

## Лицензии

- Код: MIT (см. `LICENSE`)
- Контент: CC BY 4.0 (см. `LICENSE-CONTENT`)