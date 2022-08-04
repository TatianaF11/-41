//void Zadacha41()
{
    //Задача 41: Пользователь вводит с клавиатуры M чисел. Посчитайте, сколько чисел больше 0 ввёл пользователь.
    //0, 7, 8, -2, -2 -> 2
    //1, -7, 567, 89, 223-> 3
    int M = 5;

    int count = 0;
    for (int i = 0; i < M; i++) //i < 5; 0 1 2 3 4
    {
        Console.WriteLine();
        Console.Write($"Введите {i+1}-e число: ");
        int number = Convert.ToInt32(Console.ReadLine());
        if (number > 0) count++;
    }
    Console.WriteLine("Количество чисел больше нуля:"+ count);
}
//Zadacha41();
