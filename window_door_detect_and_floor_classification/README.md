Компания XRPlace создает интерактивные 3D квартиры и дома для сайтов застройщиков. Это похоже на web игру, где мы показываем планировку и локацию вокруг будущей недвижимости. Это особенно актуально для покупателей из других городов, а также для объектов недвижимости, которые ещё не построены. Это real time 3D в браузере, где можно гулять от первого лица, как в любой компьютерной игре (без ограничений перемещения по точкам, как у 360панорам). На предыдущем этапе была создана модель распознавания углов помещений для создания интерактивных 3D визуализаций. На данном этапе предполагается определять координаты окон и дверей и (по возможности) - тип помещения.

Мы обучили и протестировали две модели, которые по плану помещения возвращают координаты дверных и оконных проемов и определяют назначение помещения (кухня, спальня, санузел). 

В ходе работы над проектом решены следующие задачи:
 - Исследование открытых датасетов, релевантных для задачи
 - Выбор pretrained модели и типа решаемой задачи
 - Обучение модели на открытых датасетах
 - Постпроцессинг результатов работы модели (преобразование маски или bbox в координаты объектов.
