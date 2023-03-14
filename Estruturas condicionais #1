/*PUCMINAS-Contagem-Disciplina:ATP
Programador: Erick Ribeiro
Descricao: Descobrir Titulo e ângulo
Entrada: a ,b e c   
Saida: Descobre titulo e ângulo
*/
using System;

class Program {
  public static void Main (string[] args) {
  double a, b, c;

    Console.WriteLine("Digite o valor de a");
    a = double.Parse(Console.ReadLine());

    Console.WriteLine("Digite o valor de b");
    b = double.Parse(Console.ReadLine());

    Console.WriteLine("Digite o valor de c");
    c = double.Parse(Console.ReadLine());

    if (a<b) {
        double aux = a;
        a = b;
        b = aux;
      }

    if (a<c) {
        double aux = a;
        a = c;  
        c = aux;
      }
      
  

    if (a >= b + c) {
        Console.WriteLine("Esses valores não forman um triângulo"); 
      
    }
    if (a<=b+c) {
       
      
    if (Math.Pow (a,2) == (Math.Pow (b,2) + (Math.Pow (c,2)))){
        Console.WriteLine("Esses valores forman um triângulo retângulo");
      }

    if (Math.Pow (a,2) > (Math.Pow (b,2) + (Math.Pow (c,2)))){
        Console.WriteLine("Esses valores forman um triângulo obtusângulo");
      }

    if (Math.Pow (a,2) < (Math.Pow(b,2) + (Math.Pow (c,2)))){
        Console.WriteLine("Esses valores forman um triângulo acutângulo");
      } 
    if ( a==b && b==c) {
       Console.WriteLine("Esses valores forman um triângulo equilatero"); 
      }
    if ((a==b && a!=c)
      ||(a==c && a!=b)
      ||(b==c && b!=a)
      ){
        Console.WriteLine("É isóceles");
      }
      if (a!=b && a!=c && b!=c) {
        Console.WriteLine("É escaleno");
      }
      
      
      }
      }   
    }
