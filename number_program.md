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

- Write a java program to print the tables. results should be odd number and print sum of results.


``` java

package com;

public class Tables {

	public static void main(String[] args) {

		int a = 3;
		int sum = 0;
		for (int i = 1; i <= a; i++) {
			sum = 0;
			System.out.println("Tables :" + i + "\n");
			for (int j = 1; j <= 10; j++) {

				if ((i * j) % 2 != 0) {
					System.out.println(i + "*" + j + "=" + (i * j));
					sum = sum + (i * j);

				}

			}

			int temp = sum;
			System.out.println("Sum of " + i + " Tables : " + temp);
			System.out.println("\n");
		}

	}
}
//Output:

// Tables :1

// 1*1=1
// 1*3=3
// 1*5=5
// 1*7=7
// 1*9=9
// Sum of 1 Tables : 25


// Tables :2

// Sum of 2 Tables : 0


// Tables :3

// 3*1=3
// 3*3=9
// 3*5=15
// 3*7=21
// 3*9=27
// Sum of 3 Tables : 75

```