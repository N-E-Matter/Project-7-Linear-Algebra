# Project-7-Linear-Algebra
Data Science project work during the Yandex Practicum
Project #7

Нужно защитить данные клиентов страховой компании «Хоть потоп». Необходимо разработать такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию.
Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось.

Инструкция по выполнению проекта
1. Загрузите и изучите данные.
2. Ответьте на вопросы и обоснуйте решение: 
  - Признаки умножают на обратимую матрицу. Изменится ли качество линейной регрессии? (Её можно обучить заново.)
   a. Изменится. Приведите примеры матриц.
   b. Не изменится. Укажите, как связаны параметры линейной регрессии в исходной задаче и в преобразованной.
3. Предложите алгоритм преобразования данных для решения задачи. Обоснуйте, почему качество линейной регрессии не поменяется.
4. Запрограммируйте этот алгоритм, применив матричные операции. Проверьте, что качество линейной регрессии из sklearn не отличается до и после преобразования. Примените метрику R2.

Описание данных:
Набор данных находится в файле /datasets/insurance.csv. 
Признаки: пол, возраст и зарплата застрахованного, количество членов его семьи.
Целевой признак: количество страховых выплат клиенту за последние 5 лет.
