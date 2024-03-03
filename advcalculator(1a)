package p1;

import java.util.Scanner;

public class Lab_1a{
	public static void main(String[] args) {
		Scanner s=new Scanner(System.in);
		boolean continue_calculation=true;
		String History=" ";
		while(continue_calculation) {
			System.out.println("Enter the operand 1:");
			double a=s.nextDouble();
			System.out.println("Enter the operator:");
			char c=s.next().charAt(0);
			System.out.println("Enter the operand 1:");
			double b=s.nextDouble();
			if(a>0&&b>0) {
				double result=0;
				switch(c) {
				case'+':
					result=a+b;
					System.out.println(" "+a+c+b+"="+result+"\n");
					History+=" "+a+c+b+"="+result+"\n";
					break;
				case'-':
					result=a-b;
					System.out.println(" "+a+c+b+"="+result+"\n");
					History+=" "+a+c+b+"="+result+"\n";
					break;
				case'*':
					result=a*b;
					System.out.println(" "+a+c+b+"="+result+"\n");
					History+=" "+a+c+b+"="+result+"\n";
					break;
				case'/':
					if(a>b) {
						result=a/b;
						System.out.println(" "+a+c+b+"="+result+"\n");
						History+=" "+a+c+b+"="+result+"\n";
					}
					else
						System.out.println("Invalid input");
					break;
				}
				System.out.println("Do you want to repeate calculation");
				String input=s.next();
				if(input.equalsIgnoreCase("yes"))
					continue_calculation=true;
				else
					continue_calculation=false;
				
			}
			else
				System.out.println("Please enter positive numbers");
		}
		System.out.println("Do you want to display the history");
		String input1=s.next();
		if(input1.equalsIgnoreCase("yes"))
			System.out.println(History);
		
	}
}
