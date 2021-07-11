# Machine Learning Fundamentals Course by HSE. (Coursera)
![image](https://user-images.githubusercontent.com/57394771/125189597-7f371500-e241-11eb-8d50-b5a4eb86c205.png)


## Task 1
### Анализ таблицы math_students и определение на её основе с помощью библиотеки Pandas таких показателей как:
  1. Какая причина выбора школы была самой частой? В качестве ответа приведите соответствующее значение признака.
  2. Найдите количество студентов, у родителей которых нет никакого образования.
  3. Найдите разность между средними итоговыми оценками студентов, состоящих и не состоящих в романтических отношениях.
  4. Сколько занятий пропустило большинство студентов с самым частым значением наличия внеклассных активностей?
## Task 2
### Использование стандартного dataset'a moons из библиотеки sklearn для построения модели бинарной классификации с использованием метода k-ближайших соседей (kNN). 
  1. Были использованы методы разбиения выборки на обучающую и тестовую с помощью кросс-валидации.
  2. Исследовано поведение метрик в зависимости от количества используемых для классификации соседей.
### Использование dataset'а MNIST, состоящего из образцов рукописного написания цифр для построения модели классификации с использованием метода k-ближайших соседей. 
  1. Было произведено разбиение выборки на обучающую и тестовую.
  2. Обучена модель kNN с k=30.
  3. Рассчитана метрика точности (accuracy)
## Task 3
### Решение задачи с Kaggle о предсказании длины поездки в такси New York City Taxi Trip Duration (https://www.kaggle.com/c/nyc-taxi-trip-duration/overview) с использованием методов линейной регрессии. 
  1. Произведен анализ данных - обнаружены аномалии, произведена нормализация, категориальные признаки обработаны с использованием one-hot кодирования.
  2. Произведено разбитие выборки на обучающую и тестовую.
  3. Обучена модель Ridge регрессии.
  4. Выполнен подбор гиперпараметров модели для улучшения качества. Используемая метрика - среднеквадратичная ошибка (MSE).
  5. Обучена модель Lasso регрессии для сравнения качества работы и отбора признаков.
## Task 4
### Использование стандартного dataset'а boston из библиотеки sklearn для построения модели линейной регрессии предсказания стоимости дома с использованием стохастического градиентного спуска.
  1. Было произведено разбиение выборки на обучающую и тестовую
  2. Обучена модель линейной регрессии с использованием стохастического градиентного спуска. 
  3. Рассчитана метрика MAPE для обученной модели.
  4. Произведено сравнение с аналитическим методом нахождения весов. 
  5. Обучена модель Ridge регрессии с использованием SGD и произведено сравнение метрик.
## Task 5
### Решение задачи с Kaggle о предсказании заболеваний сердца Heart Desease UCI (https://www.kaggle.com/ronitf/heart-disease-uci)  с использованием модели линейного классификатора.
  1. Было произведено разделение выборки на обучающую и тестовую
  2. Обучена модель линейной классификаци с использованием логистической регрессии и метода стохастического градиентного спуска (с использованием L1-регуляризатора и без него).
  3. Рассчитаны метрики доли правильных ответов, AUC-ROC
  4. Произведен анализ важности признаков.
## Task 6
### Использование стандартного dataset'а wine из библиотеки sklearn для построения модели логистической регрессии.
  1. Произведена нормализация признаков.
  2. Обучена модель логистической регрессии.
  3. Произведен аналих важности признаков.
### Задача бинарной классификации текстов с использованием данных SMSSpamCollection. Данные содержат текстовую информацию и бинарное целевое значение (‘spam’, ‘ham’).
  1. Получено векторное представление текстов с использованием TF-IDF меры.
  2. Исследовано количество получаемыемых признаков с учетом n-грамм.
  3. Обучена модель логистической регрессии.
  4. Оценена доля правильный ответов.
