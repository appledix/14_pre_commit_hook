# Quadratic Equations Solver

В данном репозитории хранится скрипт с функцией вычисления корней квадратного уравнения, набором тестов для данной функции и **pre-commit hook** для git репозитория, **запускающий тесты перед коммитом**. Если изменения в коде повлекли за собой сбои при прохождении тестов, то будет выведен отчет об ошибке и коммит сделать не удастся.

## Использование

##### В качестве модуля
Импортируем функцию к себе в программу и наслаждаемся:
```python
from quadratic_equation import get_roots

print(get_roots(a, b, c))
```

#####  Тесты
Запуск вручную в терминале: `python3.5 tests.py`

##### Установка pre-commit hook
В клонированный репозиторий необходимо скопировать файл **pre-commit** по адресу ".git/hooks" в репозитории.

Для работы хук обязательно(!) должен иметь права на запуск. Если по какой-то причине хук таких прав не имеет, можно добиться этого командой в терминале: `chmod +x pre-commit`.

##### Установка скрипта
В терминале: `git clone https://github.com/appledix/17_sites_monitoring.git`

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)