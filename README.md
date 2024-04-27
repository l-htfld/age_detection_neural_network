# Определение возраста покупателей

В рамках проекта для сетевого супермаркета "Хлеб-Соль" была разработана модель компьютерного зрения, которая определяет приблизительный возраст клиентов на основе фотографий, сделанных в прикассовой зоне. Это позволит магазину анализировать покупки и предлагать товары, соответствующие интересам конкретной возрастной группы, а также контролировать добросовестность кассиров при продаже алкоголя.

## Цели проекта:
1. Построить и обучить модель для распознавания возраста покупателей на фотографиях.
2. Оценить точность работы модели и ее применимость на практике.

## Задачи проекта:
1. Подготовить и обработать набор фотографий покупателей.
2. Построить архитектуру модели на базе нейронной сети Keras.
3. Использовать предварительно обученную модель ResNet50 для определения возраста.
4. Оценить качество модели с помощью метрики средней абсолютной ошибки (MAE).
5. Предложить возможные пути улучшения модели и ее применения на практике.

## Выводы:
Модель на основе нейронной сети ResNet50 была построена и успешно обучена для определения приблизительного возраста покупателей на фотографиях. Метрика MAE составила 5.8, что позволяет модели достаточно точно определять возраст. Однако, стоит учитывать возможность переобучения модели и рекомендуется дальнейшее совершенствование, например, введение интервальной системы определения возраста для повышения точности на практике.
