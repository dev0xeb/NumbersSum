# NumbersSum
import java.util.Scanner;
public class NumbersSum
{
	public static void main(String[] args)
	{

	int firstnum;
	int sum = 0;

	for (firstnum = 1; firstnum <= 10; firstnum++)
		sum += firstnum;
	System.out.printf("the sum of number from 1 - 10 %d", sum);
	}
}
