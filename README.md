# Исследование признаков, которые больше всего влияют на прохождение лечения ментального здоровья
## Данные
Данные взяты в https://www.kaggle.com/datasets/monukhan/mental-health-dataset . В данном наборе данных содержится информация о сотрудниках различных компаний, включая их демографические данные, рабочие условия и факторы, влияющие на психическое здоровье. Цель исследования — выяснить, какие факторы влияют на решение пройти лечение в связи с проблемами психического здоровья.

Данные были предобработаны, а именно очищены от выбросов, заполнены пропущенные значения, удалены некорректные значения. 
## Визуализация
Проиллюстрированы зависимости признаков от целевой переменной. Большую часть опрошенных составляют мужчины и люди в возрасте 25-40 лет. Также большая часть опрошенных - люди в США. 
Результаты представлены в graphics.ipynb
## Модель градиентного бустинга
Для подтверждения результатов визуализации была построена модель градиентного бустинга, чтобы определить, какие признаки больше всего влияют на переменные. Результаты представлены в файле features_importances.ipynb
## Результаты исследования:
Наибольшее влияние на прохождение лечения влияют такие признаки как:
- Наличие семейной истории. Люди, у которых есть семейная история психических заболеваний, значительно чаще проходят лечение.
- Наличие профессиональной помощи. Люди, у которых есть доступ к возможностям профессиональной помощи на работе, чаще выбирают лечение, так как это снижает барьеры и делает процесс обращения за помощью менее сложным.
- Вмешательство работы в личную жизнь. Если работа часто мешает личной жизни, это может стать причиной повышенного стресса и усталости, что приводит к более высокой вероятности обращения за лечением.
- Доступность льгот. Наличие медицинских и других льгот на работе, таких как страхование или программы поддержки психического здоровья, существенно повышает вероятность того, что человек обратится за лечением.
- Размер компании. В небольших компаниях сотрудники реже обращаются за лечением, тогда как в средних и крупных компаниях доступ к льготам и поддержке повышает вероятность прохождения лечения.

