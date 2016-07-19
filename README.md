# AlphabetOrNot
import java.util.Scanner;

public class CharacterOrNot {
	public static void main(String []arg)
	{
		Scanner get=new Scanner(System.in);
		char c=get.next().charAt(0);
		int input=(int)c;
		if(input<91 && input>=65)
		{
			System.out.println("the given character is Alphabet");
		}
		else if(input>96 && input<123)
		{
			System.out.println("the given character is Alphabet");
		}
		else
		{
			System.out.println("it is not Alphabet");
		}
	}

}
