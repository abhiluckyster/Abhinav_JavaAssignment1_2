# Abhinav_JavaAssignment1_2
#prime numbers between 1 and 100

public class PrimeNumber {
	public static void main(String args[]){
	
	for (int i=1; i<=100; i++)
	{
		int k=0;
		for (int j=2; j<=i-1; j++)
		{
			if (i%j==0)
			{	k = k+1;
			   break; }
		}
		if (k==0)
			System.out.print(" " +i);
		}
	}
	}
	
