## A/B test
В ходе тестирования гипотезы целевой группе пользователей сайта (студентам) была предложена новая механика оплаты услуг, у контрольной группы оставалась базовая механика. Имеются данные о группах пользователей, их активности и оплатах. Необходимо проанализировать итоги эксперимента и сделать вывод, стоит ли запускать новую механику оплаты на сайте на всех пользователей.

#### Стек: 
Pandas, Numpy, Matplotlib, Seaborn, Pingouin.

#### Этапы работы:
- проведен предварительный анализ и предобработка данных;
- рассчитаны метрики CR (конверсия в оплату), ARPPU (средний доход на платящего пользователя) и ARPAU (средний доход на активного пользователя) для целевой и контрольной группы;
- рассчитана статистическая значимость различий в метриках между группами и сделан вывод о целесообразности введения новой механики оплаты.

#### Результаты:
В результате анализа обнаружено статистически значимое увеличение среднего дохода, что позволяет сделать вывод о возможности запуска новой механики оплаты на всех пользователей.