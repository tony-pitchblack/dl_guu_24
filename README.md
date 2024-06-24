# Введение в Deep Learning
## Задачи к экзамену
1. Матрично - векторное дифференцирование
2. Градиентный спуск (реализовать мнемокод для поставленной задачи)
3. Метод максимального правдоподобия (найти параметры распределения по наблюдаемым величинам)
   * [Теория](https://youtu.be/_mvcZv_gmZE?si=_QDnd2py4lf0magi)
   * [Пример 1](https://youtu.be/_mvcZv_gmZE?si=_QDnd2py4lf0magi)
   * [Пример 2](https://youtu.be/mH8022OsfuI?si=A4TbveLSOuOrE7qk)
6. Найти loss для заданного распределения классов
7. Построить вычислительный граф для метода обратного распространения ошибки
8. Дан код, найти ошибки в коде
9. Дан код, объяснить его и провести вычисления, которые записаны в методе forward
## Вопросы к экзамену
### Basics
1. Однослойные и многослойные полносвязные сети для задач классификации и регрессии. Функции активации. Прямое и обратное распространение ошибки ([Теория](https://youtu.be/bW4dKxtUFpg?si=floVWCWK8KC4_gcv&t=64))
3. Loss функции в задачах глубокого обучения. Метод максимального правдоподобия. Связь метода максимального правдоподобия и нормы L2
4.	Слои сверточных нейронных сетей, функционал, назначение, принципы работы
5.	Архитектуры сверточных нейронных сетей. Передача обучения
6.	Оптимизация: стохастический градиент,  Adam, RmsProp. Автоматическое дифференцирование. Матричные производные. 
7.	Повышение качества обучения (минимизация loss функции): аугментация, выбор гиперпараметров, настройка гиперпарамтеров, Байесовская оптимизация. Плюсы и минусы каждого подхода
### Computer Vision
8. Метрические методы обучения. Сиамские сети. Функции ошибок для метрических методов
9. (*)	Автоэнкодеры: VAE, CVAE
10.(*)	Генеративные модели: GAN, нормализующие потоки
11. (*) 	Дифузионные модели
12.	Детекция объектов: RCNN Fast RCNN, Faster RCNN
13.	Детекция объектов: YOLOv1, v2, v3
14.	Сегментация объектов: SegNet, Unet. DeepLab
### NLP
14. Тексты. Принципы предобработки текстов. Схема обучения word2vec. Что такое токен. Модель WordPiece. 
15.	Рекуррентные сети [[DLS 2](https://youtu.be/3OljkWQ2Uc0?si=jRMaq90_bJXoctgc)] Регрессия, авторегрессия, seq2seq. Устройство LSTM, biLSTM нейрона [[DLS 2](https://youtu.be/2a_7SmTNrJA?si=hQ9no6ir2KLDFpoD)]
16. Рекуррентные сети и механизм внимания в  seq2seq последовательностях [[DLS 2](https://youtu.be/Fki-Xe3CGg8?si=Cne0Vwryo-cn74FH)]
17. Машинный перевод, схема обучения в машинном переводе. [[DLS 2](https://youtu.be/QjpEWRq-Cak?si=u8mfjSCEQ0oWicQB)]. Модель языка.  Метрики качества на примере  BLEU
18. Трансформеры. Архитектура, функционал, элементы. Принцип работы [[DLS 2](https://youtu.be/TBEwpgyoo20?si=wp31J6INJZaHOOPz)]
19. Внимание и самовнимание в трансформерах. Query, Keys, Values, Mask Attantion [[DLS 2](https://youtu.be/tsee8mosj5U?si=5-UbUtrUkLDCYLil)]
20. LSTM vs Тансформер. Достоинства и недостатки каждой архитектуры. Основные различия. [см. п.15 и п.18]
21. Архитектуры Декодер, Энкодер — Декодер, Энкодер. Сходство и различия. Примеры применения.
