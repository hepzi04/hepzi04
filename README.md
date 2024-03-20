import java.util.Scanner;
class Project 
{
	public static void main(String[] args) 
	{
		
        double sum,sub,mul,div;
		System.out.println("WELCOME TO MY CALCULATING APP");
		System.out.println("*****************************");
		for(int num=1;num<=5;num++){
        System.out.println("1.ADDITION");
		System.out.println("2.SUBRACTION");
		System.out.println("3.MULTIPLICATION");
		System.out.println("4.DIVISION");
		System.out.println("5.EXIT");
		

		Scanner sc= new Scanner(System.in);
		System.out.println("Enter the Required Operation = ");
		num=sc.nextInt();

		switch(num)
		{
			case 1:
				 System.out.println("1.ADDITION");
			      System.out.println("1.ENTER THE NUMBER = ");
				  double a=sc.nextDouble();

				  System.out.println("2. ENTER THE NUMBER = ");
				  double b=sc.nextDouble();

                  sum = a + b;
					 
				  System.out.println("SUM OF " + a + " AND " + b + " IS " + sum);
				  break;



			case 2:
				 System.out.println("2.SUBRACTION");
			      System.out.println("1.ENTER THE NUMBER = ");
				  a=sc.nextDouble();

				  System.out.println("2. ENTER THE NUMBER = ");
				  b=sc.nextDouble();

                  sub = a - b;
					 
				  System.out.println("SUB OF " + a + " AND " + b + " IS " + sub);
				  break;

		    case 3:
				 System.out.println("3.MULTIPLICATION");
			      System.out.println("1.ENTER THE NUMBER = ");
				  a=sc.nextDouble();

				  System.out.println("2. ENTER THE NUMBER = ");
				  b=sc.nextDouble();

                  mul = a * b;
					 
				  System.out.println("MUL OF " + a + " AND " + b + " IS " + mul);
				  break;

			case 4:
				 System.out.println("4.DIVISION");
			      System.out.println("1.ENTER THE NUMBER = ");
				  a=sc.nextDouble();

				  System.out.println("2. ENTER THE NUMBER = ");
				  b=sc.nextDouble();

                  div = a / b;
					 
				  System.out.println("DIV OF " + a + " BY "  + b + " IS " + div);
				  break;


				  case 5:
				  System.out.println("Thanks For Using me!");
					  System.exit(0);



		}
		}
	
}
