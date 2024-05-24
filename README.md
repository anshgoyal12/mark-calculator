import java.util.*;
public class calculator {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("enter the marks in english");
        int eng_int1 = sc.nextInt();
        System.out.println("enter the marks in hindi");
        int hindi_int1 = sc.nextInt();
        System.out.println("enter the marks in maths");
        int maths_int1 = sc.nextInt();
        System.out.println("enter the marks of science");
        int sci_int1= sc.nextInt();
        System.out.println("enter the marks in  java ");
        int jav_int1 = sc.nextInt();
        int sum = eng_int1 + hindi_int1 + maths_int1 + sci_int1 + jav_int1;
        System.out.println("the total marks of student is " + sum);
        float per = sum/5;
        System.out.println(per);
        if(per>=90)
			System.out.println("Grade A");
		else if(per>=80)
			System.out.println("Grade B");
		else if(per>=70)
			System.out.println("Grade C");
		else if(per>=60)
			System.out.println("Grade D");
		else if(per>=40)
			System.out.println("Grade E");
		else
			System.out.println("Grade F");

    }
      
}
 
