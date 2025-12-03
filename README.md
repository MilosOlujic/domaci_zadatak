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

