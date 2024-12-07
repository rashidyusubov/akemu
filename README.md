# Akemu

![README md](https://github.com/user-attachments/assets/f0ff79c0-5dca-4422-abf8-c9723bf8ea46)
## Общее описание
Akemu — это простое приложение на Python с графическим интерфейсом на основе `customtkinter`, которое отслеживает содержимое буфера обмена и автоматически воспроизводит текст из буфера обмена в текстовые поля других приложений. Также приложение позволяет запускать действия по горячей клавише и поддерживает таймер для автоматической вставки текста.

В общем, эта программа эмулирует процесс ввода текста, скопированного в буфер обмена, с задержкой между нажатиями клавиш. Это может быть полезно, например, для автоматизации ввода текста в приложениях, которые не поддерживают вставку из буфера обмена.

Важно: Использование этого кода может нарушать политику безопасности некоторых систем или приложений. Пожалуйста, используйте его ответственно и только в тех случаях, когда у вас есть явное разрешение на эмуляцию ввода с клавиатуры.

## Функции и настройки

- **Буфер обмена**: Отображает содержимое буфера обмена и отслеживает его изменения.
- **Обратный отсчёт**: После нажатия кнопки "Начать" запускается трёхсекундный обратный отсчёт перед воспроизведением текста.
- **Печать текста**: Воспроизводит текст из буфера обмена с небольшими задержками между символами. Воспроизведение текста можно прервать нажатием клавиши `p`.
- **Горячая клавиша**: Приложение поддерживает горячую клавишу `Ctrl + B` для запуска печати текста.
  
## Команды для сборки и запуска

### Клонирование репозитория:

```bash
git clone https://github.com/rashidyusubov/akemu.git
cd akemu
```

### Создание виртуального окружения

```python
python -m venv .venv
```

### Активация виртуального окружения (Windows)

```bash
.venv\Scripts\activate
```

### Активация виртуального окружения (MacOS/Linux)

```bash
source venv/bin/activate
```

### Установка необходимых библиотек:

```bash
pip install -r requirements.txt
```

### Запуск проекта:
```bash
python src/akemu.py
```

## Пример работы

![akemu](https://github.com/user-attachments/assets/3fc2fbe5-493a-44f3-b249-51bf61f8cba4)
