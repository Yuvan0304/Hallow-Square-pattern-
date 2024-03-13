# Hallow-Square-pattern-
I have done a Hallow Square pattern using java
Program:

import java.util.*;
public class Main{
	public static void main(String[] args) {
	Scanner sc=new Scanner(System.in);
	int row=sc.nextInt();
	for(int i=0;i<row;i++){
	    for(int j=0;j<row;j++){
	    if(i==0 || i==row-1 || j==0 || j==row-1 )
	    System.out.print("*"+" ");
	else 
	
	    System.out.print(" "+" ");
	}
	System.out.println();
		}
}
}
