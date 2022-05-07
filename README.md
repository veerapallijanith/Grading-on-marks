# Grading-on-marks

## Aim:
To write a C# program to grade the marks

## Algorithm:
### Step1:

Start<br/>

### Step2:

Create a class and declare one variable with integer datatype<br/>

### Step3:

Get marks from the User.<br/>

### Step4:

Use if and elif condition to check the grade<br/>

### Step5:

print the grade for the given mark<br/>

### Step6:

stop<br/>

## Program:
```c#
using System;
namespace hello
{
    class program
    {
            static void Main(string[] args)
            {
            int marks;
            Console.WriteLine("ENTER THE MARK:");
            marks = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("\nYOUR GRADE IS:");
            if (marks>90)
                Console.WriteLine("O GRADE");
            else if (marks > 80)
                Console.WriteLine("A+ GRADE");
            else if (marks > 70)
                Console.WriteLine("A GRADE");
            else if (marks > 60)
                Console.WriteLine("B+ GRADE");
            else if (marks > 50)
                Console.WriteLine("B GRADE");
            else if (marks >= 40)
                Console.WriteLine("C GRADE");
            else
                Console.WriteLine("FAIL");

        }
    }
}
```

## Output:

![image](https://github.com/veerapallijanith/Grading-on-marks/blob/main/c3.png)

## Result:
Thus the C# program to grade the marks is executed successfully.
