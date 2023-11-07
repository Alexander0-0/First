//Task1
/*Console.WriteLine("Введите ширину");
float a = Convert.ToSingle(Console.ReadLine());
Console.WriteLine("Введите длину");
float b = Convert.ToSingle(Console.ReadLine());
Console.WriteLine("P = " + ("{0,6:f2}"), ((a + b) * 2));
Console.WriteLine("S = " + ("{0,6:f2}"), (a * b));
*/

//Task2
/*Console.WriteLine("Введите первое число (a)");
float a = Convert.ToSingle(Console.ReadLine());
Console.WriteLine("Введите второе число (b)");
float b = Convert.ToSingle(Console.ReadLine());
Console.WriteLine("a + b = " + ("{0,6:f2}"), (a + b));
Console.WriteLine("a * b = " + ("{0,6:f2}"), (a * b));
Console.WriteLine("(a + b) / 2 = " + ("{0,6:f2}"), ((a + b) / 2));
*/

 //Task3
  /* Console.WriteLine("Введите целое число (a)");
 float a = Convert.ToSingle(Console.ReadLine());
 Console.WriteLine(" a ^ 2 = " + (a*a));
 Console.WriteLine(" a ^ 3 = " + (a*a*a));
 Console.WriteLine(" a ^ 4 = " + (a*a*a*a));
*/

//Task4
/*Console.WriteLine("Введите длину боссейна (в метрах)");
float a = Convert.ToInt32(Console.ReadLine());
Console.WriteLine("Введите ширину боссейна (в метрах)");
float b = Convert.ToInt32(Console.ReadLine());
Console.WriteLine("Введите глубину боссейна (в метрах)");
float c = Convert.ToSingle(Console.ReadLine());
Console.WriteLine("Максимальный объём воды, который может поместиться в бассейн = " + (a * b * c) + " " + "метров кубических");
Console.WriteLine("Площадь водной поверхности = " + (a * b) + " " + "метров квадратных");
double d = a * b;
double e = 0.2 * 0.25;
Console.WriteLine("Для укладки дна бассейна потребуется = " + (d/e) + " " + "шт." );
*/

//Task5
/*Console.WriteLine("Введите первую оценку");
double a = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("Введите вторую оценку");
double b = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("Введите третью оценку");
double c = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("Введите четвёртую оценку");
double d = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("Введите пятую оценку");
double e = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("Средний балл = " + ("{0,6:f1}"), ((a+b+c+d+e) / 5));
*/

 //Task6
/*Console.WriteLine("Введите целое трёхзначное число");
if (int.TryParse(Console.ReadLine(), out var number))
{
    if (number > 99 && number < 1000)
    {
        var f = number % 10;
        var s = number / 10 % 10;
        var m = number / 100;
        Console.WriteLine("Количество единиц = " + f);
        Console.WriteLine("Количество десятков = " + s);
        Console.WriteLine("Количество сотен = " + m);
    }
    else if (number < -99 && number > -1000)
    {
        var t = number % 10;
        var g = number / 10 % 10;
        var k = number / 100;
        Console.WriteLine("Количество единиц = " + t);
        Console.WriteLine("Количество десятков = " + g);
        Console.WriteLine("Количество сотен = " + k);
    }
    else
    {
        Console.WriteLine("Вы ввели не трёхзначное число");
     }
}
*/




