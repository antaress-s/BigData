# Ансамблевое обучение

В данной работе был использован датасет Metabolic Syndrome, который содержит информацию о людях с метаболическим синдромом, для задачи кластеризации. В работе были исследованы показатели, такие как возраст, измерение окружности талии и bmi, наличие синдрома.

Запуск кода производился в Colab Google

Было проведено сравнение двух видов ансамблевого обучения: Bagging и Boosting. Для этого исходный датасет был разделен на обучающую и тестовую выборки, после чего обучался случайный лес. Проанализировав показатели времени и качества работы, был сформирован вывод о том, что на данном датасете баггинг отработал лучше, чем бустинг. Если сравнивать время, то Случайный лес быстрее CatBoost. Случайному лесу требовалось секунд 10, в то время как процесс обучения CatBoost занял 1 минуту и 17 секунд. По качеству баггинг отработал лучше до выбора лучшей модели в тренировочных данных, но хуже на тестовых данных. При этом на обоих видах данных баггинг отработал лучше, чем бустинг.

Таким образом, были изучены разные виды ансамблевого обучения.
