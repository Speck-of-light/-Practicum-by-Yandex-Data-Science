#  Practicum by Yandex Data Science
Репозиторий содержит проекты, выполненные  в рамках образовательной программы "Яндекс.Практикум". 
Профессия: Специалист Data Science.

Языки программирования: Python

IDE: Jupyter Notebook

	
 Название проекта| Цель проекта |Используемые библиотеки и модули
----------------|--------------|---------------------------
Определение токсичных комментариев|Поиск токсичных комментариев и отправка их на модерацию. Классификация комментариев на позитивные и негативные|pandas, numpy,tf-idf, nltk, pipeline, LinearRegression, CatBoost, LightGBM
Прогноз заказов такси на следующий час|Построение системы прогноза количества заказов такси на следующий час|pandas, numpy, scikit-learn, XGBoost, CatBoost, LightGBM
[Определение стоимости автомобиля](https://github.com/Speck-of-light/-Practicum-by-Yandex-Data-Science/tree/947039ea0fafb86958588a57c1ce49efb8ce948f/%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%81%D1%82%D0%BE%D0%B8%D0%BC%D0%BE%D1%81%D1%82%D0%B8%20%D0%B0%D0%B2%D1%82%D0%BE%D0%BC%D0%BE%D0%B1%D0%B8%D0%BB%D0%B5%D0%B9)|Разработка системы рекомендации стоимости автомобиля на основе его описания. Построить модель машинного обучения, используя модели Градиентного Бустинга для быстрого определения стоимости автомобиля|pandas, numpy, scikit-learn, XGBoost, CatBoost, LightGBM, matplotlib, seaborn, scipy
Защита персональных данных клиентов|Защитить данные клиентов страховой компании. Разработать такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. При преобразовании качество моделей машинного обучения не должно ухудшаться.|sklearn pandas matplotlib numpy seaborn
[Исследование технологического процесса очистки золота](https://github.com/Speck-of-light/-Practicum-by-Yandex-Data-Science/tree/ae34c626cd654a2c5b7718b38c0cf677fe339b5a/%D0%92%D0%BE%D1%81%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B7%D0%BE%D0%BB%D0%BE%D1%82%D0%B0%20%D0%B8%D0%B7%20%D1%80%D1%83%D0%B4%D1%8B)| Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды.  Модель поможет оптимизировать производство, чтобы предотвратить запуск предприятия с убыточными характеристиками.|scipy sklearn pandas numpy matplotlib seaborn
[Определение наиболее выгодного региона нефтедобычи](https://github.com/Speck-of-light/-Practicum-by-Yandex-Data-Science/tree/ae34c626cd654a2c5b7718b38c0cf677fe339b5a/%D0%92%D1%8B%D0%B1%D0%BE%D1%80%20%D0%BB%D0%BE%D0%BA%D0%B0%D1%86%D0%B8%D0%B8%20%D0%B4%D0%BB%D1%8F%20%D0%B1%D1%83%D1%80%D0%B5%D0%BD%D0%B8%D1%8F%20%D1%81%D0%BA%D0%B2%D0%B0%D0%B6%D0%B8%D0%BD%D1%8B)|Проанализировать данные геологоразведки трёх регионов. На предсказания ML модели выбрать регион дальнейшего бурения| pandas numpy matplotlib seaborn sklearn
[Прогноз оттока клиентов банка](https://github.com/Speck-of-light/-Practicum-by-Yandex-Data-Science/tree/21d63f32f0241571a4b1faed0b77985e0898e3cd/%D0%9F%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7%20%D0%BE%D1%82%D1%82%D0%BE%D0%BA%D0%B0%20%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%D0%BE%D0%B2%20%D0%B1%D0%B0%D0%BD%D0%BA%D0%B0)|	Спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Построить модель с предельно большим значением F1-меры. Исследовать баланс классов, обучите модель без учёта дисбаланса. Улучшите качество модели, учитывая дисбаланс классов. Обучить разные модели и найдите лучшую.|sklearn pandas matplotlib
Классификаиция клиентов телеком компании| Построение и подбор максимально точной ML модели для подбора телефонного тарифа|	sklearn pandas
Анализ рынка компьютерных игр|Выявление определяющих успешность компьютерной игры закономерностей.|scipy pandas numpy matplotlib seaborn
[Анализ прибыльности телефонных тарифов](https://github.com/Speck-of-light/-Practicum-by-Yandex-Data-Science/tree/925d3436a2933b6fa40145ce93f0f7e4adfec9bb/%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%BF%D1%80%D0%B8%D0%B1%D1%8B%D0%BB%D1%8C%D0%BD%D0%BE%D1%81%D1%82%D0%B8%20%D1%82%D0%B5%D0%BB%D0%B5%D1%84%D0%BE%D0%BD%D0%BD%D1%8B%D1%85%20%D1%82%D0%B0%D1%80%D0%B8%D1%84%D0%BE%D0%B2)|На основе данных клиентов оператора сотовой связи проанализировать поведение клиентов и поиск оптимального тарифа |	scipy pandas numpy matplotlib seaborn
[Анализ рынка недвижимости](https://github.com/Speck-of-light/-Practicum-by-Yandex-Data-Science/tree/cf8d6b76b6969c3ebdd98bf6316ee8294a41d28c/%D0%98%D1%81%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BE%D0%B1%D1%8A%D1%8F%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B9%20%D0%BE%20%D0%BF%D1%80%D0%BE%D0%B4%D0%B0%D0%B6%D0%B5%20%D0%BA%D0%B2%D0%B0%D1%80%D1%82%D0%B8%D1%80)|Спрогнозировать рыночную стоимость объектов недвижимости.|pandas numpy matplotlib seaborn
Исследование надёжности заёмщиков — анализ банковских данных| На основании статистики платежеспособности клиентов банка, выявить, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Результаты исследования будут учтены при построении модели кредитного скоринга|pandas
[Исследование данных музыкального сервиса — сравнение пользователей двух городов](https://github.com/Speck-of-light/-Practicum-by-Yandex-Data-Science/tree/38bc9b04590d92c9d0883111fddb3f5dbaddf153/%D0%9C%D1%83%D0%B7%D1%8B%D0%BA%D0%B0%20%D0%B1%D0%BE%D0%BB%D1%8C%D1%88%D0%B8%D1%85%20%D0%B3%D0%BE%D1%80%D0%BE%D0%B4%D0%BE%D0%B2) |На реальных данных Яндекс.Музыки c помощью библиотеки Pandas и её возможностей проверить данные и сравнить поведение и предпочтения пользователей двух столиц — Москвы и Санкт-Петербурга.|pandas|   
