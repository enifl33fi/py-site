# py-site

Статический сайт для публикации результатов исследований.
Собран на MkDocs Material, публикуется на GitHub Pages и на Helios ИТМО.

## Что внутри

- [T1. Сравнительный анализ генераторов статических сайтов](t1.md)
- [P4. Развёртывание на Helios с контролем качества доставки](p4.md)

## Стек

- **Генератор:** MkDocs + Material
- **CI/CD:** GitHub Actions
- **Хостинги:** GitHub Pages, Helios ИТМО
- **Доставка на Helios:** SSH/rsync с отдельным deploy-ключом
- **Healthcheck:** HTTP 200 + контрольная строка `P4_DEPLOY_OK`

## Репозиторий

- GitHub: <https://github.com/enifl33fi/py-site>
- GitHub Pages: <https://enifl33fi.github.io/py-site/>
- Helios: <https://se.ifmo.ru/~s367380/py-site/>

## Лицензии

- Код: [MIT](https://github.com/enifl33fi/py-site/blob/master/LICENSE)
- Текст, графики, данные: [CC BY 4.0](https://github.com/enifl33fi/py-site/blob/master/LICENSE-CONTENT)