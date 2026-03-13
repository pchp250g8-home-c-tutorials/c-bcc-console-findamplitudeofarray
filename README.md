FindAmplitudeOfArray. C Tutorials. Embarcadero Rad Studio IDE. Simple Input/Output. Arrays. Algorithms. Console application. 
A console application in the C programming language. 
The program does the following:
   1. Prompts the user for the number of elements in the array.
   2. Allocates memory and creates an array of integers with the number of elements entered previously.
   3. The first loop with the parameter is executed.
      3.1. The initial value of the parameter is set to 0, and the final value is set to the number of array elements - 1 (numbering in the array starts from 0).
      3.2. A series of loops are executed, where the array elements are filled with random integers from 1 to 100 and
           they are displayed on the screen in a line    separated by spaces.
      3.3. The value of the loop parameter is compared with the final value. If it is less, the loop is executed. Otherwise, it terminates.
      3.4. The loop parameter variable is incremented by the loop increment. In this example, it is 1.
   4. Variables are introduced for the index of the maximum and minimum array elements and their values.
      The element indices are equal to 0, and the values ​​are equal to the value of the first (zeroth) element of the array.
   5. The second loop with the parameter is executed:
      5.1. The initial value of the parameter is set to 1, and the final value is set to the number of array elements - 1.
           The search for elements will begin with   element No. 2 (1, array numbering starts from 0).
      5.2. A series of loops are executed. The search for the maximum and minimum array elements and their indices is performed.
           5.2.1 If the next element is larger than the previously found one, then its number (index) and value (maximum) are remembered.
           5.2.2 If the next element is smaller than the previously found one, then its number (index) and value (minimum) are remembered.
      5.3. The value of the loop parameter is compared with the final value. If it is less, the loop is executed. Otherwise, it terminates.
      5.4. The loop parameter variable is incremented by the loop increment. In this example, it is 1.
   6. After the loop completes, the index and value variables of the element will contain the maximum and minimum of the array.
   7. The maximum and minimum elements of the array and the range of the series are displayed on the screen.
      Calculated as the difference between the maximum and minimum elements of the array (the values ​​are taken).
Developed in the Embarcadero Rad Studio integrated environment.



ИС Embarcadero Rad Studio. Занятия по C. Простой Ввод/Вывод. Алгоритмы. Массивы. Платформа Windows. Консольное приложение.
Консольное приложение написанное на языке программирования C. 
Программа делает следующее:
  1. Запрашивает у пользователя количество элементов массива.
  2. Выделяет память и создаёт массив целых чисел с количеством элементов введённым ранее.
  3. Выполняется первый цикл с параметром.
     3.1. Начальное значение параметра устанавливается равным 0, а конечное - числу элементов массива - 1 (нумерация в массиве идёт с 0).
     3.2. Выполняется серия цикла, где заполняются элементы массива целыми случайными числами от 1 до 100 и они выводятся на экран в строку через пробел.
     3.3. Значение параметра цикла сравнивается с конечным. Если оно меньше цикл выполняется. В противном случае - завершается.
     3.4. Переменная параметра цикла увеличивается на шаг цикла. В данном примере он равен 1.
  4. Вводятся переменные для индекса максимального и минимального элемента массива и их значений.
     Индексы элементов равны 0, а значения - значению первого (нулевого)     элемента массива.
  5. Выполняется второй цикл с параметром.
     5.1. Начальное значение параметра устанавливается равным 1, а конечное - числу элементов массива - 1. Поиск элеметов будет начинаться с элемента № 2 (1,                нумерация массива идёт с 0).
     5.2. Выполняется серия цикла. Идёт поиск максимального и минимального элементов массива и их индексов.
          5.2.1 Если очередной элемент больше ранее найденного, то запоминается его номер (индекс) и значение (максимум).
          5.2.2 Если очередной элемент меньше ранее найденного, то запоминается его номер (индекс) и значение (минимум).
     5.3. Значение параметра цикла сравнивается с конечным. Если оно меньше цикл выполняется. В противном случае - завершается.
     5.4. Переменная параметра цикла увеличивается на шаг цикла. В данном примере он равен 1.
  6. После завершения работы цикла в переменных индексов и значений элемента будет содержаться максимум и минимум массива. 
  7. На экран выводятся максимальный и минимальный элемент массива и размах ряда.
     Вычисляется как разность между максимальным и мнимальным элементом массива (берутся значения).
Разработано в интегрированной среде Embarcadero Rad Studio.
