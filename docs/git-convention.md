## Требования к именам коммитов

- Названия коммитов должны быть согласно [гайдлайну](https://www.conventionalcommits.org/en/v1.0.0/)
- Тип коммита должен быть только в нижнем регистре (`feat`, `fix`, `refactor`, `docs`, `style`, `chore` и т.д.)
- Должен использоваться present tense ("add feature" not "added feature")
- Должен использоваться imperative mood ("move cursor to..." not "moves cursor to...")

### Примеры имен коммитов

- `init:` - используется для начала проекта/таска. Примеры:

```
init: start youtube-task
init: start mentor-dashboard task
```

- `feat:` - это реализованная новая функциональность из технического задания (добавил поддержку зумирования, добавил footer, добавил карточку продукта). Примеры:

```
feat: add basic page layout
feat: implement search box
feat: implement request to youtube API
feat: implement swipe for horizontal list
feat: add additional navigation button
feat: add banner
feat: add social links
feat: add physical security section
feat: add real social icons
```

- `fix:` - исправил ошибку в ранее реализованной функциональности. Примеры:

```
fix: implement correct loading data from youtube
fix: change layout for video items to fix bugs
fix: relayout header for firefox
fix: adjust social links for mobile
fix: array parsing issue when multiple spaces were contained in string
```

- `refactor:` - новой функциональности не добавлял/поведения не менял. Файлы в другие места положил, удалил, добавил. Улучшил алгоритм, без изменения функциональности. Примеры:

```
refactor: change structure of the project
refactor: rename vars for better readability
```

- `docs:` - используется при работе с документацией/readme проекта. Примеры:

```
docs: update readme with additional information
docs: update description of run() method
```

- `style:` - используется при изменениях стиля и оформления кода. Примеры:

```
style: remove trailing white spaces
style: add missing semi-colons
style: format code with prettier
```

- `chore:` - используется, когда не меняются исходные файлы и файлы тестов. Примеры:

```
chore: add .editorconfig file for uniform code formatting  
chore: rename environment variable file to .env.example
```

## FAQ

### Можно ли ревертнуть отправленный (запушенный) в репозиторий коммит без снижения оценки?

Да, можно.
