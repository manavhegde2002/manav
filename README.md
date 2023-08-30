# manav //java if else code implementation for arithmetic operations
package puzzle;

import java.util.Scanner;

public class menurunner {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner scanner = new Scanner(System.in);
		System.out.println("enter no1:");
		int no1 = scanner.nextInt();


		System.out.println("enter no2:");
		int no2 = scanner.nextInt();

		System.out.println("the choice available are");
		System.out.println("1 - Add");
		System.out.println("2 - Sub");
		System.out.println("3 - Mul");
		System.out.println("4 - Divide");
		System.out.println("enter choice");
		int choice = scanner.nextInt();
		System.out.println("choices are");
		System.out.println("no1" + no1);
		System.out.println("no2" + no2);
		System.out.println("choice" + choice);

		if (choice == 1) {
			System.out.println("result" + (no1 + no2));
		} else if (choice == 2) {
			System.out.println("result" + (no1 - no2));
		} else if (choice == 3) {
			System.out.println("result" + (no1 * no2));
		} else if (choice == 4) {
			System.out.println("result" + (no1 / no2));
		}
	}

}


*//write a java code for switch statement for days in a week
package exercise;

public class switchexerciserunner {
public static void main(string[] args ) {
	System.out.println(determinenameofday(0));
}
public static string determinenameofday(int daynumber) {
	string result = "";
	switch(daynumber) {
	case 0:
		result="sunday";
		break;
	case 1:
		result="monday";
	break;
	case 2:
		result="tuesday";
	break;
	case 3:
	
	result="wednesday";
	break;
	case 4:
		
	result="thursday";
	break;
	case 5:
		result="friday";
	break;
	case 6:
		result="saturday";
	break;
	}
	return "invalidday"
	};
}
}

//*
