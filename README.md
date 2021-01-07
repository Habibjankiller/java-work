# java-work
This repository contains open source Java small Projects
import java.util.Scanner;
//THIS IS A SIMPLE PROGRAM TO REVERSE A STRING

public class Reverse {
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.println("This program is created by Habib Ullah");
		System.out.println("This programm will convert your string");
		Scanner stringScanner = new Scanner(System.in);
		System.out.print("Enter your String: ");
		String charactors = stringScanner.nextLine();
		String reverseString = "";
		for (int i = charactors.length() - 1; i >= 0; i--) {
			reverseString = reverseString + charactors.charAt(i);
		}
		
		System.out.print("Your reverse string is: ");
		System.out.print(reverseString);
	}
}
