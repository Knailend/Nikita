using System;
 
namespace HelloApp
{
    class Person
    {
         
    }
    class Program
    {
        static void Main(string[] args)
        {
             
        }
    }
}
using System;
 
namespace HelloApp
{
    class Person
    {
        public string name; // ���
        public int age;     // �������
 
        public void GetInfo()
        {
            Console.WriteLine($"���: {name}  �������: {age}");
        }
    }
    class Program
    {
        static void Main(string[] args)
        {
            Person tom;
 
            Console.ReadKey();
        }
    }
}
class Program
{
    static void Main(string[] args)
    {
        Person tom = new Person();
        tom.GetInfo();      // ���: �������: 0
 
        tom.name = "Tom";
        tom.age = 34;
        tom.GetInfo();  // ���: Tom �������: 34
          
        Console.Read();
    }
}




































