//Mean of numbers

import java.util.*;
public class Myclass {
    public static void main(String args[])
    {
        Scanner s=new Scanner(System.in);
        int n,i=0,sum=0,num,mean;
        System.out.println("Enter number of values: ");
        n=s.nextInt();
        for(i=0;i<n;i++)
        {
            num=s.nextInt();
            sum=sum+num;
        }
        mean=(sum/n);
        System.out.println("Mean is "+mean);
}
}

=====================================
//Biggest of 3 numbers

import java.io.*;
import java.util.*;
public class First {
    public static void main(String[] args) {
        int a,b,c;
        Scanner s = new Scanner(System.in);
        System.out.println("Enter 3 numbers to check:");
        a=s.nextInt();
        b=s.nextInt();
        c=s.nextInt();
        if (a>b && a>c ){
        System.out.println(a+" is the biggest number");
    }
        else if (b>c){
                System.out.println(b+" is the biggest number");
                }
        else{
            System.out.println(c+" is the biggest number");
        }
        }
}



=====================================
//Prime in given 3 digit number

import java.util.*;
public class Main
{
	public static void main(String[] args) {
		System.out.println("Enter number:");
		Scanner s = new Scanner(System.in);
		int n = s.nextInt();
		while(n!=0)
		{
		    int count=0;
		    int rem=n%10;
		    for(int i=1;i<=rem;i++)
		    {
		        if (rem%i==0)
		        {
		            count=count+1;
		        }
		    }
		    if (count==2)
		        {
		            System.out.println(rem+"is Prime number.");
		        }
		    n=n/10;
		}
	}
}

======================================
//Menu driven program :Calculator

import java.io.*;
import java.util.*;
import java.lang.*;
public class First {

      public static void main(String[] args) {
        int a,b;
        Scanner s = new Scanner(System.in);
        while(true)
        {
            System.out.println("Menu:\n1.Addition\n2.Subtraction\n3.Multiplication\n4.Division\n5.Exit\nEnter your option:");

            int n=s.nextInt();
	    switch(n)
            {
                case 1:
                {
	            a=s.nextInt();
	            b=s.nextInt();
                    System.out.println("Addition is "+(a+b));
                    break;
            }
                case 2:
                {
                    a=s.nextInt();
	            b=s.nextInt();
	            System.out.println("Subtraction is "+(a-b));
                    break;
	        }
                case 3:
                {
	            a=s.nextInt();
	            b=s.nextInt();
                    System.out.println("Multiplication is "+(a*b));
                    break;
	        }
                case 4:
	        {
                a=s.nextInt();
                b=s.nextInt();
	        System.out.println("Division is "+(a/b));
                break;
                }
                case 5:
	        {
                    System.out.println("End of Program");
	            System.exit(0);
	        }
                default: {
                    System.out.println("Enter valid number:");
                    break;
                }
	   }
	}
}
}
===============================
//Big and small among 3 digit:

import java.util.*;
public class Main
{
	public static void main(String args[]) {
		System.out.println("Enter number:");
		Scanner s = new Scanner(System.in);
		int n = s.nextInt();
		int min=n%10;
	    int max=n%10;
	    while(n!=0)
	    {
	        int r=n%10;
	        if (max<r)
	        {
	            max=r;
		    }
		    if (min>r)
	        {
	            min=r;
	        }
		    n=n/10;
		}
		System.out.println(max+"is big number.");
	    System.out.println(min+"is small number.");     
	}
}
===============================
//Reverse of a number:

import java.util.*;
public class Main
{
	public static void main(String args[]) {
		System.out.println("Enter number:");
		Scanner s = new Scanner(System.in);
		int n = s.nextInt();
		int rev=0;
	    while(n!=0)
	    {
	        int rem=n%10;
		    rev=((rev*10)+rem);
		    n=n/10;
		}
		System.out.println(rev+"is reverse number.");   
	}
}
===============================
//Arm strong 

import java.io.*;
import java.util.*;
public class First {
    public static void main(String[] args) {
        int n,rem,temp,sum=0;
        Scanner s = new Scanner(System.in);
        System.out.println("Enter 3 numbers to check:");
        n=s.nextInt();
        temp=n;
        while(n!=0)
        {
            rem=n%10;
            sum=sum+(rem*rem*rem);
            n=n/10;
        }
        if (temp==sum)
        {
            System.out.println("Arm strong");
        }
        else
        {
            System.out.println("Not Arm strong");
        }
}
}
===================================
//Arm Strong blw 100 to 1000:
import java.io.*;
public class Main {
    public static void main(String[] args) {
        int n,rem,temp,sum;
        System.out.println("Enter 3 numbers to check:");
        for(int i=100;i<200;i++)
        {
            temp=i;
            sum=0;
            while(i!=0){
            rem=i%10;
            sum=sum+(rem*rem*rem);
            i=i/10;
            }
            if (temp==sum)
            {
                System.out.println(sum+" is Arm strong");
            }
        }
    }
}

===================================
//Perfect number:

import java.io.*;
import java.util.*;
public class Main
{
	public static void main(String args[]) {
		System.out.println("Enter number:");
		Scanner s = new Scanner(System.in);
		int n = s.nextInt();
		int sum=0;
		for(int i=1;i<n;i++)
		{
		    if (n%i==0)
		    {
		        sum=sum+i;
		    }
		}
		if (sum==n)
		{
		    System.out.println(n+" is Perfect number.");   
	    }
	    else{
	        System.out.println(n+" is Not Perfect number."); 
	    }
	}
}


================================
//Strong number:
import java.io.*;
import java.util.*;
public class Main
{
	public static void main(String args[]) {
		System.out.println("Enter number:");
		Scanner s = new Scanner(System.in);
		int n = s.nextInt();
		int sum=0,temp=n;
	while(n != 0)
	{
    int i = 1;
    int fact = 1;
    int rem = n % 10;
    while(i <= rem)
    {
        fact = fact * i;
        i++;
    }
    sum = sum + fact;
    n = n / 10;
	}
	if (sum==temp)
	{
	    System.out.println(temp+" is strong number.");   
	}
	else
	{
        System.out.println(temp+" is Not strong number."); 
	}
	}
}
=====================================

//Array initialisation:

public class Main {
    public static void main(String[] args) {
        int a[]={10,20,30,40,50};
        int i ;
        System.out.println("Array elements are:");
        for(i=0;i<5;i++)
        {
            System.out.println(a[i]+" ");
        }
    }
    
}
======================================
//Even or odd :

public class Even_odd {
    public static void main(String args[])
    {
        int a[]=new int[10];
        int i;
        Scanner s= new Scanner(System.in);
        System.out.println("Enter array elements");
        for(i=0;i<10;i++)
        {
            a[i]=s.nextInt();
        }
        System.out.println("Even elements are:");
        for(i=0;i<10;i++)
        {
            if (a[i]%2==0)
            {
            System.out.println(a[i]);
            }
        }
        System.out.println("Odd elements are:");
        for(i=0;i<10;i++)
        {
            if (a[i]%2!=0)
            {
            System.out.println(a[i]);
            }
        }
        }
}
===========================================
//Selection sort:

import java.util.*;
public class Selection_sort {
    public static void main(String args[]){
        int a[]=new int[10];
        Scanner s =new Scanner(System.in);
        System.out.println("Enter elements size:");
        int n=s.nextInt();
        int i,j;
        System.out.println("Enter elements:");
        for(i=0;i<n;i++)
        {
            a[i]=s.nextInt();
        }
        for(i=0;i<n;i++)
        {
            for(j=i+1;j<n-1;j++)
            {
            if (a[i]>a[j])
                    {
                        int t=a[i];
                        a[i]=a[j];
                        a[j]=t;
                    }
        }
        }
        System.out.println("Sorted elements are:");
        for(i=0;i<n;i++)
        {
            System.out.println(a[i]);
        } 
    }
}

========================================
//Bubble sort:
import java.util.*;
public class Main {
    public static void main(String args[]){
        int a[]=new int[10];
        Scanner s =new Scanner(System.in);
        System.out.println("Enter elements size:");
        int n=s.nextInt();
        int i,j,t;
        System.out.println("Enter elements:");
        for(i=0;i<n;i++)
        {
            a[i]=s.nextInt();
        }
        for(i=0;i<n;i++)
        {
            for(j=0;j<n-1;j++)
{
                if (a[j]>a[j+1])
                    {
                        t=a[j];
                        a[j]=a[j+1];
                        a[j+1]=t;
                      
                    }
            }
        }
        System.out.println("Sorted elements are:");
        for(i=0;i<n;i++)
        {
            System.out.println(a[i]);
        } 
    }
}
