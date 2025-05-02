# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To Create a main () for class named as ‘Fruit’ it has name , color, weight as its member.  Access Grape and Mango by creating its object.

## ALGORITHM :
1.	Start the program.
2.	Define a class named 'Student'
3.	Declare a String variable 'name' and initialize it with the value "John"
4.	Declare a String variable 'address' and initialize it with the value "Chennai"
5.	Define a class named 'Test'
6.	Define the 'main' method within the 'Test' class
7.	Create an object 'obj' of the 'Student' class
8.	Print the value of 'name' and 'address' variables of the 'obj' object
9.	End



## PROGRAM:
 ```
Program to implement a class & objects using Java
Developed by: Swetha D
RegisterNumber:  212223040222
public class Fruit {
    String name;
    String color;
    double weight;
    public static void main(String[] args)
    {
        Fruit obj1=new Fruit();
        Fruit obj2=new Fruit();
        obj1.name="Grape";
        obj1.color="Purple";
        obj1.weight=0.75;
        obj2.name="Mango";
        obj2.color="Yellow";
        obj2.weight=1.50;
        System.out.println("Fruit Name is "+obj1.name+",Color is "+obj1.color+" and weight is "+obj1.weight+"kg");
        System.out.println("Fruit Name is "+obj2.name+",Color is "+obj2.color+" and weight is "+obj2.weight+"kg");
      }
}
```
## OUTPUT:
![{110A9577-1C69-436A-B0F3-7582666A6B58}](https://github.com/user-attachments/assets/becc7a1c-b7d1-4527-a8c7-afa60ccc014c)

## RESULT:
Thus, the class named as ‘Fruit’ it has name , color, weight as its member access Grape and Mango by creating its object
was created successfully.
