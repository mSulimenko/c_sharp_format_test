# Задание 1

## Статья
Название: 3D path planning and real-time collision resolution of multirotor drone operations in complex urban low-altitude airspace 

Для цитирования: Zhang, N., Zhang, M. & Low, K. H. (2021). 3D path planning and real-time collision resolution of multirotor drone operations in complex urban low-altitude airspace. Transportation Research Part C: Emerging Technologies, 129, 103123-. https://dx.doi.org/10.1016/j.trc.2021.103123

URL: https://hdl.handle.net/10356/151289

## Поставленная цель и задачи
Цель авторов статьи: разработать метод для достижения автономного планирования пути дронов без столкновений с учетом статических и динамических препятствий в городском пространстве. 

Список задач исследования:
1)  Разработка метода 3D voxel JPS для нахождения глобального пути без столкновения для дронов в статической среде.
2)  Внедрение техник дедиагонализации, реконструкции и сглаживания для оптимизации опорного пути, полученного из предыдущего этапа.
3) Разработка схему разрешения столкновений на основе MDP для предотвращения столкновений в режиме реального времени, для избегания дроном столкновений с динамическими препятствиями.
4) Приведение обоснований корректности работы, а также эффективности разработанной модели.

Следует отметить то, что в пункте 1. Введение — определена цель текущих разработок и актуальность данной темы.

Разделы, раскрывающие вышеописанные задачи:
- "2. Background review " — раздел, в котором представлены общие краткие описания первых трёх этапов процесса вместе;
- "3.1. Reference path planning based on 3D voxel jump point search" — раздел, который описывает работу алгоритма для вычесления пути без столкновений в статической среде, сравнение различных подходов для этой цели;
- "3.2. Path optimization"  — описание блока, отвечающего за оптимизацию основного пути, для того, чтобы уменьшить риски столкновений, избежать большого количества поворотов и уменьшить общую длину пути;
- "3.3. Real-time collision resolution based on Markov decision process" — описание методов для быстрого перерасчета пути для избегания столкновений с динамическими препятствиями, например, другими дронами;
- "4. Simulation and results " — раздел, в котором с различных углов обзора представлено обоснование эффективности и корректности применения разработанных методов на основе статистических данных. 

## Тематика статьи
Тематики статьи - разработка алгоритмов для планирования маршрутов и решения проблем столкновений дронов в условиях городской среды.

Авторы статьи представляют новый подход к планированию маршрутов для дронов в сложном городском воздушном пространстве, обеспечивая как глобальное избежание столкновений со статическими объектами, так и разрешение столкновений с динамическими объектами в режиме реального времени.

> This work presents a fusion scheme to achieve autonomous drone collision-free path planning considering static obstacles and dynamic threats detected.

## Методы обоснования
Были использованы следующие методы обоснования достигнутых результатов:

- Эксперименты в симуляторе: Авторы проводили эксперименты в симуляторе для демонстрации эффективности предложенного метода планирования маршрутов для дронов.
> In this section, simulations are conducted to study the performance of the proposed method in dealing with static obstacles and dynamic threats. For the simulation results presented next, the building features of certain areas of the Jurong East, Singapore (shown in Fig. 13), from the UTM platform (Mohamed Salleh and Low, 2017), have been extracted as the static urban environments. Besides, the test results obtained run in the computer.

- Сравнительный анализ с существующими методами: Авторы сравнили свой метод с существующими подходами к планированию маршрутов для дронов.
> First, to test the superiority of 3D voxel JPS in global drone path planning, two simulation scenarios (Scenario 1 and Scenario 2) are established, and the comparative simulations are carried out as shown in Fig. 14 and Fig. 15, respectively.
>  To test the effects of the proposed optimization technique, we set two scenarios in case of special cases. Fig. 16 shows the results of the 3D view and the top view of Scenario 1 after different optimized steps.

- Проведение стресс-теста для проверки работостпособности системы и выявления ошибок
> The stress test is widely applied to check the collision avoidance system and identify the critical event
>  In conclusion, the stress test results reveal that the proposed dynamic collision resolution approach is sensible in collision detection.
