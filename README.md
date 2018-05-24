# Решатель квадратных уравнений

Данный проект демонстрирует работу модуля unittest, на примере тестирования функции нахождения корней квадратичныхуравнений. 
Подробнее о квадратных уранениях можно почитать [здеcь](http://school-assistant.ru/?predmet=algebra&theme=kvadratnie_uravnenija)

# Как использовать
Для использования запустить скрипт test.py, который проведет тестирование функции `get_root` модуля `quadratic_equation`
Варианты вывода:
1. Если все корректно:
```
Ran 4 tests in 0.001s

OK
```
2. Если есть ошибки:
```
F.FF
======================================================================
FAIL: test_first_root_less_than_second (__main__.QuadraticEquationTestCase)
----------------------------------------------------------------------
Traceback (most recent call last):
  File "D:/projects/devmanorg/7_mistery_fix/tests.py", line 13, in test_first_root_less_than_second
    self.assertEqual(root1, -3)
AssertionError: None != -3

======================================================================
FAIL: test_second_root_is_none_if_one_solution (__main__.QuadraticEquationTestCase)
----------------------------------------------------------------------
Traceback (most recent call last):
  File "D:/projects/devmanorg/7_mistery_fix/tests.py", line 18, in test_second_root_is_none_if_one_solution
    self.assertIsNotNone(root1)
AssertionError: unexpectedly None

======================================================================
FAIL: test_solves_real_roots (__main__.QuadraticEquationTestCase)
----------------------------------------------------------------------
Traceback (most recent call last):
  File "D:/projects/devmanorg/7_mistery_fix/tests.py", line 9, in test_solves_real_roots
    self.assertEqual(root1, 1)
AssertionError: None != 1

----------------------------------------------------------------------
Ran 4 tests in 0.001s

FAILED (failures=3)
```
# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python test.py # может понадобиться вызов python3 вместо python, ....
----------------------------------------------------------------------
Ran 4 tests in 0.001s

OK
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
