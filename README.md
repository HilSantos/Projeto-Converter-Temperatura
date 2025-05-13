# Projeto Converter Temperatura

Exercício 3: Converter Temperatura de Celsius para Fahrenheit
Objetivo: Trabalhar com tipos de variáveis e realizar cálculos matemáticos para conversão de unidades.

Enunciado:
Crie um programa em C# que leia uma temperatura em Celsius, converta para Fahrenheit e exiba o resultado. A fórmula de conversão é: Fahrenheit = (Celsius * 9/5) + 32.

using System;

class Program
{
    static void Main()
    {
        Console.Write("Digite a temperatura em Celsius: ");
        double celsius = Convert.ToDouble(Console.ReadLine());

  double fahrenheit = (celsius * 9 / 5) + 32;

  Console.WriteLine($"A temperatura em Fahrenheit é: {fahrenheit:F2}°F");
    }
}
________________________________________________________________________________________________
