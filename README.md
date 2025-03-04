# Вёрстка сайта с нуля • JSX, SCSS, JS, Vite, Minista, БЭМ 

Этот репозиторий содержит материалы и код, написанный в процессе прохождения курса **"Вёрстка сайта с нуля • JSX, SCSS, JS, Vite, Minista, БЭМ"**.

## 📌 О курсе

Цель курса — пошагово реализовать фронтенд многостраничного приложения стримингового сервиса, который состоит из 6 полноценных страниц со множеством секций и сложных UI-компонентов.

В рамках курса будут созданы следующие интерфейсные элементы:

- Табы
- Мобильное меню (бургер-кнопка)
- Кастомный видеоплеер
- Различные слайдеры
- Маски для полей ввода
- Кастомный селект

Использованы следующе технологии:

- **ванильный JavaScript** с несколькими сторонними NPM-библиотеками
- **БЭМ-методологию** для организации кода
- **Sass (SCSS)** для стилизации
- **Vite** в обёртке **Minista** для сборки проекта и использования шаблонизатора JSX.

## 📌 О проекте

- **Методология работы с Git**: Git Flow + Conventional Commits
- **Система управления задачами**: GitHub Projects
- **CI/CD**: GitHub Actions
- **Среда разработки**: WebStorm&#x20;

## 📂 Структура проекта

- `README.md` — документация проекта

## 🚀 Начало работы

1. Клонируйте репозиторий:
   ```bash
   git clone git@github.com:username/stream-vibe.git
   cd stream-vibe
   ```
2. Установите зависимости:
   ```bash
   npm install
   ```
3. Запустите локальный сервер:
   ```bash
   npm run dev
   ```

## 📌 Git Flow

- `master` — стабильная версия
- `develop` — основная ветка разработки
- `feature/*` — новые фичи
- `release/*` — подготовка к релизу
- `hotfix/*` — исправление критических багов

## 📌 Conventional Commits

Используемый стандарт коммитов:

- `feat`: новая фича
- `fix`: исправление бага
- `docs`: изменения в документации
- `style`: исправления форматирования
- `refactor`: улучшение кода без изменения логики
- `chore`: настройки и вспомогательные изменения
- `test`: добавление/изменение тестов
