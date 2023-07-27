**Задача:** 
- Построить модель на несбалансированных данных, которая предскажет уйдёт ли клиента из банка в близжайшее время или нет. 
- Критерий эффективности - значение F1 меры на уровне не менее 0.59.

**Используемые модели:** при решении задачи были реалзованы моедли лийненой регрессии и случайного леса с различными методами борьбы с дисбалансом, а именно:
- взвешивание классов; 
- Random Under Sampler;
- Downsampling;
- Upsampling;
- SMOTE (Over sampling)

**Вывод:**
- среди всех рассмотренных моделей на валидационной выборе лучшее значение F1 меры у случайного леса с взвешиванием классов, именно эта модель проверялась на тестовйо выборке;
- Значение F1 меры на тестовых данных составляет 0.597, что удовлетворяет критерию задачи
- Значение ROC-AUC находится на достаточно высоком уровене (0.8441) и показывает, что модель прогнозировала не случайно и в большинстве случаев отвечала верно.
