# DejaView

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
| [dejaview-docs](https://github.com/dejaview-nsu/dejaview-docs) | Контракты API, архитектура, соглашения команды |

## Стек

Python, FastAPI, PostgreSQL / pgvector, React / Vue, HuggingFace, Docker, REST API
