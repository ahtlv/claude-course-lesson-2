# Занятие 2 — раздатка

Сегодня учимся ставить задачу агенту, заглядываем к нему под капот и выкладываем страницу
Persona в интернет. К концу занятия у тебя живая ссылка, которую можно скинуть друзьям.

## Сначала проверка

Самое первое, ещё до практики: открой в VS Code папку `work` и попроси Claude Code

```text
Покажи мой статус авторизации на GitHub.
```

Видишь `✓ Logged in to github.com account твой-ник`, значит всё готово. Не видишь, тогда прямо
сейчас, пока идёт разбор домашки, отправь промпт из занятия 1:
[`github-cli-setup.md`](https://github.com/ahtlv/claude-course-lesson-1/blob/main/prompts/github-cli-setup.md).
Без него сайт в интернет не уедет.

## Промпты по порядку

| Шаг | Промпт | Что делает |
|---|---|---|
| 1 | [`context-profile.md`](prompts/context-profile.md) | Агент собирает из файлов Persona один `profile.md`: кто ты, чем занят, что хочешь построить |
| 2 | [`claude-md-interview.md`](prompts/claude-md-interview.md) | Агент берёт у тебя интервью и сам пишет `CLAUDE.md`, правила проекта |
| 3 | [`personal-system-prompt.md`](prompts/personal-system-prompt.md) | Глобальный `CLAUDE.md`: как Claude обращается к тебе в любом проекте |
| 4 | [`deploy-persona.md`](prompts/deploy-persona.md) | Агент выкладывает страницу Persona на GitHub Pages и показывает живую ссылку |

## Почитать

- [`git-workflow.md`](git-workflow.md): main, ветка, commit, push, origin, prod на метафоре
  ресторана. Команды набирает Claude, тебе нужно понимать маршрут.
- [`deploy-guide.md`](deploy-guide.md): что агент делает при деплое и что делать, если ссылка
  не открывается.

## Домашнее задание

1. **Добить, если не успел на занятии:** `profile.md` и страница Persona в интернете. Это
   обязательно: профиль агент прочитает на занятии 3, когда будет подбирать идею под тебя.
2. 🕹️ **Главное, на большие выходные:** своя 8-битная игра в браузере, живущая по ссылке.
   Всё в [`retro-game-challenge.md`](retro-game-challenge.md).

Персонажи и раздатка занятия 1: https://github.com/ahtlv/claude-course-lesson-1
