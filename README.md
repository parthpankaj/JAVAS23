# JAVAS23
public class Pattern2
{
       public static void main(String args[])   
	   {
		    final int no=99;//a=97 ,b=98,c=99 (ASCII CODE)
			int space,in,dn;
			//in->increment,dn->decrement
			for(int i=97;i<=no;i++)
		    {
			 System.out.println();
			 for(space=no-1;space>=i;space--)
		     {
				 System.out.print(" ");
		     }
			 for(in=97;in<=i;in++)
			 {
			       char ch=(char)in;
				   System.out.print(ch);
			 }
			 for(dn=i-1;dn>=97;dn--)
			 {
			      char ch=(char)dn;
				  System.out.print(ch);
			 }
		   }
		   for(int i=no-1;i>=97;i--)
		   {
		        System.out.println();
				for(space=98;space>=i;space--)
		        {
				   System.out.print(" ");
		        }
				for(in=97;in<=i;in++)
			    {
			       char ch=(char)in;
				   System.out.print(ch);
			    }
				for(dn=i-1;dn>=97;dn--)
			    {
				   char ch=(char)dn;
				   System.out.print(ch);
			   }
			  
		   }
	   }
}




***output***

  a
 aba
abcba
 aba
  a
