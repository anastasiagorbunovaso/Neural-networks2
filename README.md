# Детектирование объектов с использованием нейронных сетей глубокого обучения на примере сети SSD

В ходе выполнения задачи были определены характеристики предобученной нейронной сети глубокого обучения SSD на наборе снимков с беспилотных летательных аппаратов VisDrone-Dataset.

**Качественный анализ работы сети на снимках**

Поскольку обучение было произведено на сторонних данных, ожидаемо, что точность детектирования очень низкая. При выполнении работы классы обхектов сопоставлялись вручную, так как изначально наборы классов входных и выходных аннотаций сильно различались. 

Низкую точность детектирования в совокупности в частым несовпадением классов можно наблюдать на примере трёх изображений из нашего датасета:
![Image alt](https://github.com/anastasiagorbunovaso/Neural-networks_2/blob/master/pic_1.jpg)
![Image alt](https://github.com/anastasiagorbunovaso/Neural-networks_2/blob/master/pic_2.jpg)
![Image alt](https://github.com/anastasiagorbunovaso/Neural-networks_2/blob/master/pic_3.jpg)

**Таблица для пункта 4**

Средняя точность детектирования объектов, количество пропущенных объектов, количество ложных тревог для порогов IoU = 0.3, 0.35, 0.4 (пороговые значения целенаправленно были заданы ниже, чем в условии)
![Image alt](https://github.com/anastasiagorbunovaso/Neural-networks_2/blob/master/%D0%9E%D0%B1%D1%89%D0%B5%D0%B5.JPG)

**Таблица для пункта 5**

Средняя точность детектирования объектов, количество пропущенных объектов, количество ложных тревог для каждого класса для порогов IoU = 0.3, 0.35, 0.4 (пороговые значения целенаправленно были заданы ниже, чем в условии)
![Image alt](https://github.com/anastasiagorbunovaso/Neural-networks_2/blob/master/%D0%9A%D0%BB%D0%B0%D1%81%D1%81%D1%8B.JPG)
