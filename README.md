# Program-to-find-out-if-it-is-a-alphabet-or-digit-or-Special-char
public class Characterinput {
	public static void main(String args[])
	{
		char a1='%';
		if ((a1>=65 & a1<=90)||(a1>=97 & a1<=122))
				System.out.println("Alphabet");
		else if (a1>='0' & a1<='9')
			System.out.println("Digit");
		
		else
			System.out.println("Special Character");


}
}
