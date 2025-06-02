# ElevenLabs ConvAI Widget

Простая страница с виджетом ElevenLabs ConvAI для развёртывания на Vercel.

## Быстрый деплой

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/djfsldjfkfofjfjm/elevenlabs-widget)

## Локальный запуск

```bash
# Клонировать репозиторий
git clone https://github.com/djfsldjfkfofjfjm/elevenlabs-widget.git

# Открыть index.html в браузере
open index.html
```

## Настройка

Для изменения agent ID отредактируйте в `index.html`:

```html
<elevenlabs-convai agent-id="YOUR_AGENT_ID"></elevenlabs-convai>
```

## Требования

- Микрофон для голосового взаимодействия
- HTTPS соединение (автоматически на Vercel)
- Публичный agent в ElevenLabs