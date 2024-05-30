
# Документация проекта

## Общее описание
Этот проект включает функции для вычисления площади и периметра различных геометрических фигур, таких как прямоугольник, треугольник, квадрат и круг.

## Описание функций с примерами вызова

### Прямоугольник (`rectangle.py`)
- `area(a, b)`: Возвращает площадь прямоугольника.
  ```python
  area(5, 3)  # Пример вызова
  ```
- `perimeter(a, b)`: Возвращает периметр прямоугольника.
  ```python
  perimeter(5, 3)  # Пример вызова
  ```

### Треугольник (`triangle.py`)
- `area(a, h)`: Возвращает площадь треугольника.
  ```python
  area(4, 6)  # Пример вызова
  ```
- `perimeter(a, b, c)`: Возвращает периметр треугольника.
  ```python
  perimeter(3, 4, 5)  # Пример вызова
  ```

### Квадрат (`square.py`)
- `area(a)`: Возвращает площадь квадрата.
  ```python
  area(4)  # Пример вызова
  ```
- `perimeter(a)`: Возвращает периметр квадрата.
  ```python
  perimeter(4)  # Пример вызова
  ```

### Круг (`circle.py`)
- `area(r)`: Возвращает площадь круга.
  ```python
  area(5)  # Пример вызова
  ```
- `perimeter(r)`: Возвращает периметр круга.
  ```python
  perimeter(5)  # Пример вызова
  ```

## История изменений
- Хэш коммита: Описание изменений
  - `8b3343b`: Начальная версия функций.
  - `d078c8d`: Добавлены тестовые примеры и документация.
  - `4e3d6a6`: Добавлен rectangle.py с вычислениями площади и периметра.
  - `8004268`: Добавлен triangle.py с вычислениями площади и периметра.
  - `8b3343b`: Исправлены расчеты периметра в rectangle.py.