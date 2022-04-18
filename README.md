# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
### Step1:
Start

### Step2:
Create a class and declare two variable with string datatype

### Step3:
Loop over the entire string and reverse it

### Step4:
Use if condition to check whether the string and the reversed string is equal or not

### Step5:
print palindrome if it's equal else print not a palindrome.

### Step6:
stop

## Program:
~~~c#
using System;  
namespace palindrome  
{  
    class Program  
    {  
        static void Main()  
        {  
            string value, dupvalue, rev="";  
            value = Console.ReadLine();  
            dupvalue = value;
            for (int s = value.Length-1; s >=0; s--) 
            {  
                rev += value[s];  
            }  
            if (rev == dupvalue) 
            {  
                Console.WriteLine(dupvalue + " is a Palindrome");  
            }  
            else  
            {  
                Console.WriteLine(dupvalue + " is not Palindrome");  
            }  
        }  
    }  
}
~~~

## Output:
![Online C# Compiler - online editor - Google Chrome 18-04-2022 21_40_42](https://user-images.githubusercontent.com/75235386/163837578-19e13465-de88-4936-994f-c27acac3d3c9.png)

## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
