# Checkpoint — mlcourse.ai setup

## Пройдено

- Изучено intro-описание курса.
- Разобрана логика self-paced прохождения.
- Определена структура папок.
- Определены правила фиксации прогресса.
- Подготовлен формат конспекта и отчёта.

## Понято хорошо

- Курс нельзя проходить пассивно.
- Основной цикл: article → notebook → assignment → review → report.
- mlcourse.ai фокусируется на classic ML.
- Главные риски прохождения: отсутствие практики, слабая фиксация ошибок, пропуск validation/leakage.

## Требует повторения

- Prerequisites: Python, math, Docker/devops basics.
- Нужно отдельно проверить готовность окружения.

## Практика

- Нужно создать папку курса.
- Нужно инициализировать Git.
- Нужно заполнить progress.md и learning_log.md.

## Ошибки / слабые места

- Пока нет фактической практики по материалам курса.
- Пока не проверено окружение Python/Jupyter.

## Следующий шаг

- Создать структуру проекта.
- Сделать prerequisites audit.
- Затем перейти к Topic 1: Pandas.

## Stage 0 — Course repository setup

Status: approved.

Local path:
`C:\temp\python_learning\mlcourse_ai`

Repository:
`https://github.com/manaer6-alt/ml_course_ai.git`

Working branch:
`develop`

What was done:
- created local course repository;
- initialized Git;
- created base folder structure;
- added `.gitignore`;
- added `README.txt`;
- added `requirements.txt`;
- added `progress.txt`;
- added `learning_log.md`;
- added `data/README.md`;
- added `notes/00_intro.md`;
- added `reports/00_intro_report.md`;
- made first commit;
- created and pushed `develop` branch.

Git issue fixed:
- initial push to `main` failed because local branch was `master` and there was no initial commit;
- SSH push failed due to missing public key setup;
- HTTPS push was used successfully.

Important rule:
- heavy datasets must not be committed;
- `data/` stores only structure/readme or lightweight metadata.

Coordinator decision:
- Stage 0 approved;
- proceed to Intro / Lecture 0.