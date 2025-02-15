# Репозиторий для группы 9383. Правила сдачи работ. [Табличка](https://docs.google.com/spreadsheets/d/1uGZ_8VjGU6MJDrPcOoF03cyn1omLoW5N75faK6XudGM/edit?usp=sharing)
## Дедлайны PR
При пропуске дедлайна минус один балл за работу.

Во избежание штрафа требуется получить плашку в своём PR "Готово к защите" до даты дедлайна. Если сделан только PR, то решение о получении штрафа зависит от количества изъянов в работе и субъективного мнения проверяющего. При отсутствии PR удовлетворяющего критериям выполненной работы выставляется штраф без дополнительных условий (кроме случаев непредвиденных обстоятельств).
| № работы |  Дата   |
|:--------:|:-------:|
|   Лаб 1  |  22.03  |
|   Лаб 2  |  05.04  |
|   Лаб 3  |  26.04  |
|   Лаб 4  |  10.05  |
|   Лаб 5  |  24.05  |

## Правила работы с репозиторием
- В начале работы делаем форк этого репозитория
   
- Создаём свою директорию Surname/
   
- Для каждой лабораторной создаётся своя отдельная ветка c названием в формате <Surname\lab#> (ветвимся от master!)
   
- Для каждой работы создаётся отдельная директория lab#, где # - номер лабораторной
   
- Внутри этой директории должны находиться материалы для проверки
      
## Разбалловка за семестр
Объём работы, выполняемый студентом в рамках лабораторных работ, зависит от оценки к которой он стремится и степени адекватного энтузиазма.

Оценка ставится при условии выполнения всех работ (получения хотя бы 1.5 баллов за каждую из работ).
|  Оценка    | Баллы |
|:----------:|:-----:|
|   Удовл    |   13  |
|   Хорошо   |   26  |
|   Отлично  |   39  |

## Получение баллов в рамках защиты лаб-работ
Сдавать работу можно в трёх режимах: на удовл, на хор, на отл.

|  Режим  | Требования | Код | Защита | Отчёт | Тесты | Макс |
|:-------:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| Удовл   | Stepik | 1 | 1 | 1| - | **3** |
| Хорошо  | Stepik + задание по варианту | 3 | 2 | 1 | - | **6** |
| Отлично | Stepik + задание по варианту + юнит-тесты | 3 | 2 | 2 | 2 | **9** |

## Ожидаемые файлы в PR
- Исходный код программ в папке Source;

- Тестовые данные в папке Tests;

- makefile или скрипт командной строки для получения исполняемого файла с названием lab# в корневой папке;

- Скрипт командной строки или на Python для возможности запуска всех тестов из папки Tests одной командой;

- Отчёт (строго в формате pdf).

### Комментарий про требования к коду
 Общие замечания, высказываемые во время практических занятий. Единообразие форматирования кода, следование принципам выбранного стиля программирования (процедурного, ооп, функционального...). Эффективная работа с ресурсами. Время жизни переменных.
 
### Комментарий про требования к отчёту
 Для полного балла за отчёт требуется: задание, вариант (если есть), постановка задачи (что вводим, что выводим, формат правильных и неправильных данных, описание работы прогамммы), описание алгоритма + сложность (кратко), детали реализации (сюда пишите наиболее важные функции/классы/методы и используемые структуры данных (если не С++, то отдельно описать, какая структура лежит под капотом), сюда же можете написать об особенностях реализации, компромиссах), демонстация работы (вообще желательно покрыть все кейсы из постановки задачи), вывод (большой).
 
### Комментарий про требования к тестам
Тестовые данные должны быть покрывать различные случаи корректных и некорректных входных данных, т.е. попадать по большей части в разные класс эквавлентности. Юнит-тесты должны быть сделаны для основных функций алгоритма, при этом должно быть произведено адекватное разбиение алгоритма на отдельные подзадачи. Также требуются тесты и система запуска для всей программы в целом. В случае использования С++ такими инструментами будут выступать Catch2 + makefile/CMake.

Можете наколхозить, то всё-таки лучше использовать стандартное решение. При необходиомсти можем согласовать для единообразия.
 

   
