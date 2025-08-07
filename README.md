## pythonWebServer (Самописный сервер. Далекий аналог Flask)

### Функции/Фияи
- Выдача html/json файлов (может быть еще yaml и xml)
- Конфигурация всех роутов
    - Настройка параметров прямиком из конфига
- Hot reload
- Финимум кода при разработаке

### Конфигурация 
```python
config = [
  {
    "method": GET|POST|PUT|OPTIONS,
    "folder": "PATH_TO_FOLDER",
    "params": [], # Optioanl
  }
]
```

Примеры использования...
