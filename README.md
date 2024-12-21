# Open WebUI

### Miniconda3-latest-Windows-x86_64.exe
Установщик Miniconda3 для Windows x86_64 - это инструмент для создания изолированной среды Python. 

Скачать можно по ссылке:
https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe

## Установка и настройка

1. Установите Miniconda3:
   - Запустите `Miniconda3-latest-Windows-x86_64.exe`
   - Следуйте инструкциям установщика
   - После установки перезапустите командную строку

2. Следуйте инструкциям ниже для дальнейшей настройки проекта

## Команды проекта

### Создание и активация виртуального окружения
```bash
# Создание виртуального окружения Python 3.11
conda create -n myenv python=3.11

# Активация созданного окружения
conda activate myenv
```

### Установка и обновление пакетов
```bash
# Обновление pip до последней версии
python -m pip install --upgrade pip

# Установка open-webui
pip install open-webui
```

### Запуск приложения
```bash
# Запуск сервера open-webui
open-webui serve
```

### Полезные команды для управления
```bash
# Просмотр информации об установленном пакете open-webui
pip show open-webui

# Деактивация текущего окружения
conda deactivate

# Просмотр списка всех окружений
conda env list

# Удаление окружения myenv со всеми установленными пакетами
conda remove -n myenv --all
```

### Повторный запуск
```bash
# Активация окружения
conda activate myenv

# Запуск сервера
open-webui serve
```

## Примечание

Убедитесь, что вы внимательно следуете всем инструкциям для корректной настройки проекта.

## Примечание
Выполняйте команды последовательно в указанном порядке. Перед повторным запуском убедитесь, что окружение активировано.
