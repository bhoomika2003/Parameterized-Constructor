# Parameterized-Constructor
Simple example of parameterized constructor using Student Object
class Student{
	 String name;
	 int age;
	 int marks;
	 int standard;

	Student(String name , int age){
		this.name = name;
		this.age = age;
	}
	public void studentInfo() {
		System.out.println("The Student name is " + name +" and  age is " +age +" and her total marks is "+marks+" and she is studing in "+standard+"th standard");
	}
	
}
public class Parameterised {
	public static void main(String[] args) {
		Student s1 = new Student("Bhoomi",21);
		s1.marks = 80;
		s1.standard = 10;
		s1.studentInfo();
	}

}
