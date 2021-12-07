# 1-number
package com.company;

import jdk.swing.interop.SwingInterOpUtils;

import java.util.Scanner;

public class Main
{
    public static void main (String args[])
    {
        Scanner k=new Scanner(System.in);
        int n = k.nextInt();
        float sum=0;
        for (int i = 1; i <= n; i++)
        {
           sum+= 1.0/i;
        }
        System.out.println(" sum =" + sum);
    }
}
