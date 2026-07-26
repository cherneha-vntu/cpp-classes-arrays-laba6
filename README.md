# Lab Work 6: Classes and Dynamic Arrays in C++

This project is a laboratory/practical work for the "Computer Technologies and Programming" course. It contains three programs that demonstrate the use of simple classes and objects for manipulating 1D and 2D dynamic arrays in C++.

## Programs Included

### 1. Move Extrema (`task1.cpp`)

This program uses a class `Array1D` to find the minimum and maximum elements of a 1D dynamic array and moves them to the ends (minimum to the first position, maximum to the last) without sorting the array.

### 2. Sum Negative Triangles (`task2.cpp`)

This program uses a class `Array2D` to find the sum of negative elements in both the upper and lower triangular parts of a 2D dynamic array, returning them in a new 1D array.

### 3. Analyze Even Elements (`task3.cpp`)

This program analyzes a 1D dynamic array, counting its even elements, calculating their sum, and computing their arithmetic mean using an `Array1D` class and an external helper function.

## How to Compile and Run

To compile and run each program, use the following commands:

```bash
g++ task1.cpp -o task1
./task1

g++ task2.cpp -o task2
./task2

g++ task3.cpp -o task3
./task3
```

## Example Usage

### task1

```text
Розмір масиву: 7
Введіть 7 елементів:
data[0] = 3
data[1] = -5
data[2] = 8
data[3] = 1
data[4] = -2
data[5] = 7
data[6] = 4
До перетворення: 3 -5 8 1 -2 7 4 
Після перетворення: -5 3 4 1 -2 7 8 
```

### task2

```text
Введіть кількість рядків і стовпців: 3 3
data[0][0] = 2
data[0][1] = -3
data[0][2] = 5
data[1][0] = -1
data[1][1] = 4
data[1][2] = -6
data[2][0] = 3
data[2][1] = -2
data[2][2] = 1
Двовимірний масив:
2       -3      5       
-1      4       -6      
3       -2      1       
Новий масив [Верхня, Нижня]: [-9, -3]
```

### task3

```text
Розмір масиву: 8
Введіть 8 елементів:
data[0] = 1
data[1] = 4
data[2] = -3
data[3] = 6
data[4] = -8
data[5] = 2
data[6] = 5
data[7] = 10
Кількість парних елементів: 5
Сума парних елементів: 14
Середнє арифметичне: 2.8
```

## Contributing

Contributions are welcome and appreciated! Here's how you can contribute:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Please make sure to update tests as appropriate and adhere to the existing coding style.

## License

This project is licensed under the CSSM Unlimited License v2.0 (CSSM-ULv2). See the [LICENSE](LICENSE) file for details.
