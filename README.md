# WAP-to-find-Sum-and-product-of-a-given-digit.
import java.util.Scanner;
class Sump{
	public static void main(String args[]){
	System.out.println("enter the two numbers");
	int a,b;
	int c;
	for(int i=0;i<=5;i++){
	Scanner sc= new Scanner(System.in);
	a=sc.nextInt();
	b=sc.nextInt();
	c=a+b;
	int d;
	d=a*b;
	System.out.println("the sum and product of two numbers are "  +c+ " " +d);
	}
	}
}
