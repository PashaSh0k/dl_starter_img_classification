# dl_starter_img_classification
## Выполнил: Аксенов Павел
Требовалось реализовать модель для классификации фрагментов полнокадровых гистологических изображений (патчей) на 9 классов. Для решения задачи я воспользовался предобученной моделью ResNet50, заменив её последний слой. В качестве оптимизатора использовал алгоритм Adam. По итогу получил следующий результат на тестовых данных: accuracy 0.9884, balanced accuracy 0.9884. Для наглядности реализовал вывод значения функции потерь на каждой эпохе (#LBL5) и построил график зависимости лосса от номера эпохи (#LBL6). 
