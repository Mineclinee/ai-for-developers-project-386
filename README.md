# Календарь звонков

[![hexlet-check](https://github.com/Mineclinee/ai-for-developers-project-386/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/Mineclinee/ai-for-developers-project-386/actions)

Минимальная версия учебного проекта. В ней есть главная страница и запуск в Docker с портом из `PORT`.

Учебный проект Хекслета: https://ru.hexlet.io/programs/ai-for-developers
Как это должно работать: https://files.hexlet.app/a/2ipc5m

## Запуск

```bash
git clone https://github.com/Mineclinee/ai-for-developers-project-386.git
cd ai-for-developers-project-386
docker build -t hexlet-call-calendar .
docker run --rm -e PORT=8080 -p 8080:8080 hexlet-call-calendar
```

Главная страница доступна по адресу [http://localhost:8080](http://localhost:8080). Для запуска без Docker используйте `node server.mjs`.

---

<details>
<summary>Автоматические тесты Хекслета</summary>

Тесты запускаются на каждый коммит. За запуск отвечает файл `.github/workflows/hexlet-check.yml` — не удаляйте и не переименовывайте ни его, ни репозиторий.

</details>

## О Хекслете

[Хекслет](https://ru.hexlet.io/) — школа программирования: авторские программы обучения с практикой, поддержкой наставников и реальными проектами, которые остаются в резюме. Этот репозиторий — один из таких проектов.
