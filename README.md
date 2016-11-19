# ACD_JAVAB2_Session_2_Assignment_2.2
package com.session2.pack;

public class ACD_JAVAB2_Session_2_Assignment_2 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int x=5;
        for(int i=0;i<x;i++){
        	for(int j=0;j<x;j++){
        		if(j== i || j==(x-1-i)){
        			
        			System.out.print("*");
        			
        		}
        		else
        		{
        			System.out.print("-");
        		}
        	}
        	System.out.println();
        }
	   
	}	
}
