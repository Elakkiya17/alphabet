import java.io.*;
import java.util.*;
class Alaphabet 
{
	public static void main (String[] args) 
	{
	  Scanner sc=new Scanner (System.in);
	  char c;
	  c=sc.next().charAt(0);
	 if((c>='a' && c<='z')||(c>='A' && c<='Z'))
	   System.out.println("alphabet");
	  else
	    System.out.println("not an alphabet");
	
		
	}
}
