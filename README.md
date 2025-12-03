# Домаћи задатак из Техничке документације
## Задатак
Програм који на основу унете дужине полупречника s израчунава површину праве кружне 
купе P. 

P =𝑟𝑠𝜋 
### Алгоритамска шема
<img width="224" height="415" alt="flow" src="https://github.com/user-attachments/assets/3b8e4a83-b11f-4f5d-bc4b-1587a95f06b9" />


## Решење

``` csharp
using System;

class Program
{
    static void Main()
    {
        Console.Write("Unesi poluprečnik r: ");
        double r = double.Parse(Console.ReadLine());

        Console.Write("Unesi dužinu izvodnice s: ");
        double s = double.Parse(Console.ReadLine());

        double P = r * s * Math.PI;

        Console.WriteLine("Površina prave kružne kupe iznosi: " + P);
    }
}
```

### Тест примери


``` csharp

Unesi poluprecnik r: 10
Unesi duzinu izvodnice s: 5
Povrsina prave kruzne kupe iznosi: 157.07963267949

C:\Users\Korisnik\source\repos\ConsoleApp8\ConsoleApp8\bin\Debug\ConsoleApp8.exe (process 19060) exited with code 0 (0x0).
To automatically close the console when debugging stops, enable Tools->Options->Debugging->Automatically close the console when debugging stops.
Press any key to close this window . . .

```

``` csharp
Unesi poluprecnik r: 2
Unesi duzinu izvodnice s: 6
Povrsina prave kruzne kupe iznosi: 37.6991118430775

C:\Users\Korisnik\source\repos\ConsoleApp8\ConsoleApp8\bin\Debug\ConsoleApp8.exe (process 17312) exited with code 0 (0x0).
To automatically close the console when debugging stops, enable Tools->Options->Debugging->Automatically close the console when debugging stops.
Press any key to close this window . . .

```




