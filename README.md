Эти учебные проекты были выполнены в рамках курса «Специалист по Data Science» в Яндекс.Практикум, финансируемого Научно-образовательным фондом имени Шахмардана Есенова через грант, который я выиграла на конкурсной основе. Дополнительно я завершила курс «Математика для анализа данных» в Яндекс.Практикум. Эти проекты демонстрируют практическое применение методов анализа данных, машинного обучения и статистического моделирования с использованием реальных наборов данных.

| Проект | Описание | Библиотеки |
| ------------- | ------------- | ------------- |
| [Статистический анализ пользователей и дохода GoFast](Statistic_analysis.ipynb) | Этот проект посвящен анализу данных сервиса аренды самокатов GoFast. Цели: выявить ключевые тенденции, оценить эффективность подписки Ultra, изучить поведение пользователей и предоставить рекомендации по улучшению сервиса. <br><br>**Методы:** Предобработка данных, анализ, проверка гипотез и расчет доходов. | Pandas, NumPy, Seaborn, Matplotlib, SciPy |
| [Статистический анализ успеха игр](Assembly%20projects.ipynb) | Этот проект анализирует исторические данные о продажах игр, рейтингах и жанрах для выявления факторов, влияющих на успех игр. Выводы помогут компании «Streamchik» прогнозировать успешные игры и планировать маркетинг на 2017 год. Цель — определить ключевые факторы успеха игр, включая платформу, жанр и рейтинги. <br><br>**Основные задачи:** Анализ и предобработка данных, анализ продаж по платформам и жанрам, предпочтения пользователей в разных регионах, проверка гипотез и рекомендации по маркетингу на 2017 год. <br><br>**Методы:** Анализ данных, регрессия и проверка гипотез. | Pandas, NumPy, Seaborn, Matplotlib, SciPy |
| [Машинное обучение для оптимизации молочной фермы](Linear_models_in_machine_learning.ipynb) | Этот проект разрабатывает модели машинного обучения для оптимизации отбора коров на молочной ферме «Вольный Луг» с целью обеспечения стабильного производства молока и соответствия стандартам вкусовых качеств. Две модели прогнозируют удой молока и оценивают его вкусовые качества. <br><br>**Методы:** Предобработка данных, исследовательский анализ данных, корреляционный анализ, регрессионное и классификационное моделирование. | Matplotlib, Numpy, Pandas, Seaborn, Phik, Scipy, Sklearn |
| [Оптимизация принятия бизнес-решений в управлении персоналом компании](hr_decisions_business_oprimization_ml.ipynb) | Аналитики отдела кадров помогают бизнесу оптимизировать управление персоналом: бизнес предоставляет данные, а аналитики предлагают решения для предотвращения финансовых потерь и текучести кадров. <br><br>**Методы:** Построение модели для прогнозирования удовлетворенности сотрудников и модели для прогнозирования текучести кадров. <br><br>**Основные задачи:** Использование машинного обучения для улучшения принятия решений на основе прогнозов, основанных на данных. | Matplotlib, Numpy, Pandas, Seaborn, Shap, Phik, Scipy, Sklearn |
| [Прогнозирование цен на рынке подержанных автомобилей](gradient_boosting.ipynb) | Сервис продажи подержанных автомобилей разрабатывает приложение для быстрой оценки рыночных цен на основе исторических данных, включая спецификации автомобилей, конфигурации и цены. Цель — построить модель машинного обучения для точного прогнозирования цен на автомобили с быстрым временем предсказания и обучения. <br><br>**Методы:** Разработка и оценка нескольких моделей машинного обучения для прогнозирования цен, включая LightGBM, RandomForestRegressor и линейную регрессию. Модели оценивались по точности прогноза (RMSE), времени обучения и времени предсказания. <br><br>**Основные задачи:** <br> - Предобработка данных: обработка пропущенных значений, выбросов и неинформативных признаков <br> - Инженерия признаков: создание нового признака для возраста автомобиля и удаление нерелевантных признаков <br> - Обучение моделей: обучение и настройка различных моделей с использованием подходящих кодировок признаков <br> - Оценка моделей: анализ RMSE, времени обучения и времени предсказания для каждой модели <br> - Выбор модели: рекомендация модели с наилучшей производительностью в соответствии с требованиями бизнеса | Matplotlib, Numpy, Pandas, Seaborn, LightGBM, CatBoost, Sklearn |
| [Прогнозирование заказов такси](time_series.ipynb) | Компания «Чётенькое такси» собрала исторические данные о заказах такси в аэропортах. Цель проекта – построить модель, которая будет прогнозировать количество заказов такси на следующий час для привлечения большего количества водителей в периоды пиковой нагрузки. <br><br>**Основные задачи:** <br> - Загрузить данные и выполнить ресемплирование по одному часу. <br> -Проанализировать временные ряды. <br> -Обучить модели Linear Regression, Decision Tree Regressor, CatBoost, LightGBM, и Random Forest с различными гиперпараметрами. <br> -Провести финальное тестирование и сделать выводы. | Pandas, NumPy, Seaborn, Matplotlib, Scipy, Sklearn, LightGBM, CatBoost |
