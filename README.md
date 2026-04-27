# 🎮 Rock Paper Scissors Game

Интерактивная веб-игра "Камень-Ножницы-Бумага" с поддержкой сохранения счёта и красивым интерфейсом.

## ✨ Особенности

- 🎯 Простой и интуитивный интерфейс с эмодзи
- 💾 Автоматическое сохранение счёта в localStorage
- 🤖 Случайный ход компьютера
- 📊 Отслеживание побед, поражений и ничьих
- 🔄 Кнопка сброса счёта

## 🚀 Как запустить

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/solkuzzzz/rock-paper-scissor.git
   cd rock-paper-scissor
   ```

2. Откройте файл `10-rock-paper-scissor.html` в браузере двойным щелчком или через локальный сервер:
   ```bash
   # Если у вас установлен Python 3
   python -m http.server 8000
   # или для Python 2
   python -m SimpleHTTPServer 8000
   ```

3. Откройте http://localhost:8000 в браузере

## 📁 Структура проекта

```
.
├── 10-rock-paper-scissor.html    # Главный файл HTML
├── index.js                       # Логика игры
├── 10-rps.css                     # Стили (если есть)
├── images/                        # Папка с эмодзи
│   ├── rock-emoji.png
│   ├── paper-emoji.png
│   └── scissors-emoji.png
└── README.md                      # Этот файл
```

## 🎮 Правила игры

- **Камень** побеждает **Ножницы**
- **Ножницы** побеждают **Бумагу**
- **Бумага** побеждает **Камень**
- При одинаковом выборе - **Ничья**

## 💡 Как это работает

1. Нажмите на одну из кнопок (Камень, Бумага или Ножницы)
2. Компьютер случайно выбирает свой ход
3. Игра определяет победителя
4. Счёт автоматически обновляется и сохраняется
5. Кнопка "Reset Score" сбрасывает счёт

## 📸 Скриншоты

Скриншоты проекта можно добавить в папку `screenshots/` в корне репозитория:

```
screenshots/
├── game-interface.png       # Основной интерфейс
├── game-result.png          # Экран результата
└── score-tracking.png       # Счёт
```

Затем вставьте в этот README:

```markdown
### Главный экран
![Game Interface](screenshots/game-interface.png)

### Результат игры
![Game Result](screenshots/game-result.png)

### Отслеживание счёта
![Score Tracking](screenshots/score-tracking.png)
```

## 🛠️ Технологии

- HTML5
- CSS3
- JavaScript (Vanilla)
- LocalStorage API

## 👤 Автор

[solkuzzzz](https://github.com/solkuzzzz)

---

**Приятной игры! 🎮**
