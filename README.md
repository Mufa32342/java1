import java.util.Scanner;
public class Arraysoperation1
{
	public static void main(String [] args)
	{
		Scanner sc = new Scanner(System.in);
		int [] numbers = new int [5];
		int sum = 0;
		int n = sc.nextInt();
		int Multi = 1;
		for (int i=0;i<5;i++)
		{
			numbers[i] = sc.nextInt();
			for(int k =1;k<=n;k++)
			{
				Multi= Multi*numbers[i];
				
				
			}
			System.out.println(Multi);
			sum = sum + Multi;
			
		}
		
		System.out.println("Sum of Square is : "+sum);
		
	}
}
