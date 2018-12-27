import java.io.*;
import java.util.*;
class Swap
{
public static void main(String args[])
{
Scanner input=new Scanner(System.in);
System.out.println("values before swap");
int a=input.nextInt();
int b=input.nextInt();

System.out.println("a="+a+"b="+b);
int temp=a;
a=b;
b=temp;
System.out.println("values after swap");
System.out.println("a="+a+"b="+b);
}
}
