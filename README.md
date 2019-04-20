# prime-factorization
import java.util.Scanner;
public class Primefactorization {
public static void main(String [] args)

{
	Scanner s=new Scanner(System.in);
	System.out.println("enter number");
	int n=s.nextInt();
	
	for(int i=2;n>1 ;i++)
	{
		while(n%i==0)
		{
			System.out.println(i);
			n=n/i;
		}
	}
	s.close();
	}
}

