# Java-program
import java.util.Scanner;
class array{
public static void main (String[]args){
    int n,i;
Scanner sc=new Scanner (System.in);  
System.out.println("Enter the size of array:");
n=sc.nextInt();
int[]marks=new int[n];
   for (i=0;i<n;i++){  
    System.out.println  
    ("enter the elements:");  
       marks[i]=sc.nextInt();  
   }  
   System.out.println("the elements of the array are ");  
   for(i=0;i<n;i++){  
       System.out.println(marks[i]);  
   }  
}

}
