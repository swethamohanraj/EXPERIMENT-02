# EXPERIMENT-02 JAVA PROGRAM TO COMPARE TWO NUMBERS
## AIM:
To compare two numbers using java programming language.

## PROCEDURE:
1.Import required packages.
2.Declare main method with the signature "public static void main(String[] args)".
3.Get two numbers as input.
4.Compare two numbers using else-if ladder.
5.Dispaly the output accordingly.

## PROGRAM:
```
public class Main
{
    public static void main(String[] args)
    {
        Scanner scan=new Scanner(System.in);
        System.out.print("Enter the first number: ");
        int a=scan.nextInt();
        System.out.print("Enter the second number: ");
        int b=scan.nextInt();
        if(a>b)
            System.out.println("A is greater");
        else if(a<b)
            System.out.println("B is greater");
        else
            System.out.println("A is equal to B");

    }
}
```
## OUTPUT:
![image](https://github.com/swethamohanraj/EXPERIMENT-02/assets/94228215/cba2d8a4-46cf-4614-95c8-7a436ad588d7)


## RESULT:
Hence, two numbers were compared using java programming language.

