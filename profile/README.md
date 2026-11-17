# DejaView

Сайт: https://dev.deja-view.ru/

Мультимодальный поиск фильмов по обрывку воспоминания: найди фильм по описанию сцены, кадру, видеофрагменту или звуку. Как Shazam, но для кино.

Страница-визитка: https://dejaview-nsu.github.io

## О проекте

Кинопоиск и IMDb ищут только по названию и метаданным. DejaView ищет по содержанию воспоминания: опиши сцену словами, загрузи кадр, скинь короткую нарезку или напой мелодию, и получи фильм. Плюс личный кинотрекер: списки, оценки, отзывы. Ядро поиска планируется доступным как публичный REST API.

Учебный проект дисциплин ПУИТП / КРПО, ФИТ НГУ, 2026.

## Репозитории

| Репозиторий | Назначение |
|---|---|
| [dejaview-nsu.github.io](https://github.com/dejaview-nsu/dejaview-nsu.github.io) | Страница-визитка проекта |
| [dejaview-backend](https://github.com/dejaview-nsu/dejaview-backend) | API поиска, бизнес-логика, БД, интеграция TMDB |
| [dejaview-frontend](https://github.com/dejaview-nsu/dejaview-frontend) | Веб-интерфейс (SPA) |
| [dejaview-ml](https://github.com/dejaview-nsu/dejaview-ml) | Эмбеддинги и векторный поиск |
| [dejaview-infra](https://github.com/dejaview-nsu/dejaview-infra) | Docker, CI/CD, деплой |
| [dejaview-docs](https://github.com/dejaview-nsu/dejaview-docs) | Архитектура, контракты API, соглашения команды |

## Стек

| Направление | Технологии |
|---|---|
| Backend | C++, CMake, PostgreSQL |
| Frontend | React, TypeScript |
| ML | Python, HuggingFace, Qdrant |
| Инфраструктура | Docker, GitHub Actions |

Подробно: [architecture.md](https://github.com/dejaview-nsu/dejaview-docs/blob/main/architecture.md).

## Как ведём работу

Требования, задачи, баги и учёт времени в Redmine: https://ai.nsu.ru/projects/dejaview

GitHub только для кода: ветки, Pull Request, ревью. Issues в репозиториях не заводим, чтобы не раздваивать учёт.

- Процесс: [process.md](https://github.com/dejaview-nsu/dejaview-docs/blob/main/process.md)
- Соглашения: [conventions.md](https://github.com/dejaview-nsu/dejaview-docs/blob/main/conventions.md)
