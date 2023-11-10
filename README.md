# lyceum-lesson1

## Активация виртуального окружения
```bash
python -m venv venv
venv/Scripts/activate
```

## Установка зависимостей 
```bash
pip install -r requirements/prod.txt
```

## Установка зависимостей для разработки
```commandline
pip3 install -r requirements/dev.txt
```

## Установка зависимостей для тестирования
```commandline
pip3 install -r requirements/test.txt
```

## Настройка переменных окружения
Скопируйте файл "config.env" в ".env", если нужно, отредактируйте значение переменных
```commandline
cp confing.env .env
```

## Запуск
```commandline
python manage.py runserver
```