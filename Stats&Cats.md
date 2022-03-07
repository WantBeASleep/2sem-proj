## Глава 1 {#start}

***
1. **Мода** - выборка наиболее часто встречающихся объектов
2. **Частота моды** - количество объектов в выборке по моде
3. **Медиана** - выборка среднего элемента в отсортированной группе элементов
4. **Среднее значение** - сложить выборку и поделить на количество элементов в этой выборке 
5. **Выброс** - элемент сильно отличающийся от элементов в группе выборки, "Выброс" портит статистику 
6. **Усеченное среднее** - выброс 5-10% min/max элементов и расчет по оставшимся

*Мода/Медиана/Среднее значение - меры центральной тенденции*

***

1. **Размах** - разница между min max элементом
2. **Межквартальный размах** - размах при выброске по 25% из max, min.
3. **Отклонение** - Разность выбранного элемента с средним значением
4. **Дисперсия** - сумма квадратов отклонений, деленное на их количество
    - $\delta$ - отклонение, тогда: $D=\frac{\sum_{i=1}^{i=n}\delta_i^2}{n}$
5. **Среднеквадратическое отклонение** - корень дисперсии
    - $\sigma=\sqrt{\frac{\sum_{i=1}^{i=n}\delta_i^2}{n}}$
7. **Нормальное распределение** - график с 68% центральной частью

***

1. **Генеральная совокупность** - *все* элементы
2. **Выборка** - группа элементов из **генеральной совокупности**
3. **Репрезентативность** - степень похожести выборкы на генеральную совокупность
> Формулы дисперсии отличаются для генеральной совокупности и для выборки: 
> 
> **генеральная совокупность**
>> $D=\frac{\sum_{i=1}^{i=n}\delta_i^2}{n}$
>
> **выборка**
>> $D=\frac{\sum_{i=1}^{i=n}\delta_i^2}{n-1}$

- **среднеквадратичное отклонение** - корень из дисперсии **ген. совокупности**
- **стандартное отклонение** - корень по выборке

***

## Глава 2

***
- **частота** - количество элементов в группе, определенной по внешнему признаку.= 
- **таблица частот** - таблица показывающая *частоту* элементов в выборке
    - *абсолютные частоты - в количестве*
    - *относительные частоты - в процентах*
- *столбиковая диаграмма* - визуализация соотношения частот и признака выбора (*например диаграмма размера котиков и частоты котиков по этому размеру*)

  - ![diagramma_koty!](/img/diagramma_koty.png)

- *полигон распределения* - еще 1 аналог визуализации данных
  - ![polygon_rasp!](/img/polygon_rasp.png)

- *круговая диаграмма* - аналог визуализации данных
  - ![circle_dia!](/img/circle_dia.png)

***
| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |