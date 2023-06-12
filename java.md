# Java programming.

- Write a java program to find given number is xylem or not

``` java
package com;

import java.util.Scanner;

public class Xylem {

	static Scanner sc = new Scanner(System.in);

	public static void main(String[] args) {
		System.out.println("Enter the number");
		int num = sc.nextInt();
		int last = num % 10;
		num /= 10;
		int mean_sum = 0;
		while (num > 9) {
			mean_sum += num % 10;
			num /= 10;
		}
		int first_last = num + last;

		String res = (first_last == mean_sum) ? "Xylem" : "not Xylem";

		System.out.println(res);
	}

}

// Output:
// Enter the number
// 143
// Xylem

// Enter the number
// 345
// not Xylem


```