#"Проект по поиску и анализу слов в тексте."


## Описанте работ

Программа определяет ключевые слова текста из файла, фильтруя стоп-слова и выполняя приведение к нормальной форме.


## Установка и использование

1. Выполните клонирования репозитория

```
git clone https://github.com/TokioSGl/nlp-project.git
```

2. Выполните установку зависимостей из файла `requirements.txt`, желательно в виртуальном окружении.

```shell
pip install -r requirements.txt
```
либо

```bash
python -m pip install -r requirements.txt
```

3. Загрузите желаемый корпус текстов в директорию `data`

4. Настройте имя файла для анализа:

```python
# main.py

text = load("data/wizard_oz.txt", encoding="cp1251")
```

5. (Для продвинутых пользователей) при желании, вы можете натроить:
    - токенизацию
    - тэги для морфем
    - изменить список стоп-слов