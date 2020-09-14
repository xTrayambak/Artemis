# Artemis
Artemis Simple Mathematical Calculation API. Can perform basic mathematical operations. (Compiled .dll is in bin/debug)

API Documentation:

the first integer is defined as 'a', the second integer is defined as 'b'.








"Add":

 the Add function performs the addition operation.
Eg:
```csharp
using System;
using artemis;

namespace ArtemisDemo
{
    class Program
    {
        private static calculationAPI api = new calculationAPI();
        static void Main(string[] args)
        {
            Console.WriteLine(api.Add(a: 20, b: 10));
        }
    }
}
```
----





"Subtract":

 the Subtract function performs the subtraction operation.
Eg:
```csharp
using System;
using artemis;

namespace ArtemisDemo
{
    class Program
    {
        private static calculationAPI api = new calculationAPI();
        static void Main(string[] args)
        {
            Console.WriteLine(api.Subtract(a: 20, b: 10));
        }
    }
}
```
----



"Multiply":
 the Multiply function performs the multiplication operation.
Eg:
```csharp
using System;
using artemis;

namespace ArtemisDemo
{
    class Program
    {
        private static calculationAPI api = new calculationAPI();
        static void Main(string[] args)
        {
            Console.WriteLine(api.Multiply(a: 20, b: 10));
        }
    }
}
```
----




"Divide":
 the Divide function performs the division operation.
Eg:
```csharp
using System;
using artemis;

namespace ArtemisDemo
{
    class Program
    {
        private static calculationAPI api = new calculationAPI();
        static void Main(string[] args)
        {
            Console.WriteLine(api.Divide(a: 20, b: 10));
        }
    }
}
```
----




This project has a MIT license, which gives anyone who obtains a copy of this code, the right to freely modify and redistribute.



