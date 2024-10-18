# Test-design
### Тест-дизайн 
— это процесс создания тестов на основе требований к программному обеспечению. Существуют различные техники тест-дизайна, каждая из которых предназначена для достижения определенных целей. Вот основные техники тест-дизайна и примеры их применения:
#### 1. Эквивалентное разбиение
```
Описание: Эта техника основана на делении входных данных на эквивалентные классы. Предполагается, что тестирование одного значения из класса будет эквивалентно тестированию других его представителей.
Пример: Если приложение принимает возраст пользователя от 0 до 120 лет, можно выделить три класса:
Неприемлемые значения: -5, 150 (негативный класс)
Приемлемые значения: 25, 80 (позитивный класс)
Граничные значения: 0, 1, 120 (граничные тесты)
```
