# Пирамиды и бинарные деревья поиска

## Построение идеального биндерева поиска

У yас есть отсортированный массив двузначных чисел без повторов размером в 2<sup>k</sup>-1 для какого-нибудь k, т.е. нам гарантируется, что размер может быть 3 (2<sup>2</sup>-1), 15 (2<sup>4</sup>-1), 1023 (2<sup>10</sup>-1), но не 11 или 30. Это позволит нам не заморачиваться с проблемами при делении пополам :)

В коде написана функция, которая возьмёт этот массив и выведет на экран бинарное дерево поиска из элементов этого дерева, которое будет полным двоичным деревом. Условие на размер массива гарантирует, что такое дерево всегда можно построить, более того, только на последнем уровне у узлов не будет детей.

У нас есть массив `[10, 13, 16, 19, 22, 25, 28, 31, 34, 37, 40, 43, 46, 49, 52]`.

Программа выводит бинарное дерево в таком виде:
```
              31              
      19              43      
  13      25      37      49  
10  16  22  28  34  40  46  52
```
