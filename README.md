# Coweigate
Стефка - 02.10
Създадох няколко метода за генериране на матрицата: основният е GenerateMatrix(int level), който извиква другите два: 
CreateEmptyMatrix(int boardSize) и PrintMatrix(char[,] matrix, int boardSize). 
Единият създава матрицата запълнена само с празни интервали ' ', основният я запълва на произволен принцип 
с букво по азбучен ред, последния метод принтира.
Създала съм един switch case, който да проверява кое е нивото и да променя размера на матрицата (boardSize) и броя букви (letters).
Добавих метода RemoveScrollBars(), който маха scrollbars от конзолата, но ако кажете може да фиксираме размера.


