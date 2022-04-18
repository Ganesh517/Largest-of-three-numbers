# Largest-of-three-numbers
## Aim:
To write a C# program to find the largest of three numbers



## Algorithm:
### Step1:

Start

### Step2:

Create a class and declare three variable with integer datatype

### Step3:

Use if condition to check whether num1 is largest than num2 and num3

### Step4:

Use elif condition to check whether num2 is largest than num1 and num3

### Step5:

Use else condition to display that third variable is largest among all the variables

### Step6:

stop

## Program:

```c#
using System;
namespace Gg
{
    class LargeNo
    {
        static void Main(string[] args)
        {
            
            int n1,n2,n3;
            Console.WriteLine("Enter The Values :");
            n1=Convert.ToInt32(Console.ReadLine());
            n2=Convert.ToInt32(Console.ReadLine());
            n3=Convert.ToInt32(Console.ReadLine());

            
            if(n1>n2 && n1>n3)
            {
                Console.WriteLine("n1 Is Greater");
            }
            else if(n2>n1 && n2>n3)
            {
                Console.WriteLine("n2 Is Greater");
            }
            else
                Console.WriteLine("n3 Is Greater");
        }
    }
}
```
## Output:
![Image](https://github.com/Ganesh517/Largest-of-three-numbers/blob/main/C%23.png)


## Result:

Thus the C# program to find the largest of three numbers is executed successfully

