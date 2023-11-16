# lyceum-lesson1
![main workflow](https://github.com/makstetoro3/lyceum-lesson1/actions/workflows/python-package.yml/badge.svg)
``

## Активация виртуального окружения
```bash
python3 -m venv venv
source venv/Scripts/activate
```

## Установка зависимостей 
```bash
pip3 install -r requirements/prod.txt
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
python3 manage.py runserver
```