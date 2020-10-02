# patterns-
import java.util.Scanner;
public class pattern {

	public static void main(String[] args) {
		
		Scanner s=new Scanner(System.in);
		int n=s.nextInt();
		
		 int i=1;
       
       
       while(i<=n) { 
    	   
    	   int sp=1;
      	   
    	   while(sp<=n-i) {                                   
       		   System.out.print(" ");
       		   sp++;
       	   
    	   }
    	   
          int   l=1;
          int   var=i;
    	   
    	   while(l<=i) { 
    		   
    		   System.out.print(var);
    		   var++;
    	   j++;
    	 	   
    	   }
    	  
         int k=1;
           while(k<=i-1) {
        	   System.out.print((2*i)-1-k);
        	   k++;
           }
           
    	   
    	   System.out.println();
           i++;
       }
       
	}

}
