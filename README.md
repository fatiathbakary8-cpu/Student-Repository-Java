class Student {
int studentId;
String name;
    int age;
    String department;
    double GPA;
Student(int id, String n, int a,String d,double g) {
    studentId = id;
    name = n;
    age = a;
    department = d;
    GPA = g;
}
    void displayInfo()  {
        System.out.println("StudentID: " +studentId);
        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
        System.out.println("Department: " + department);
        System.out.println("GPA: " + GPA);
    }
}
class Main {
     public static void main(String[]args) {
         Student s1 = new
  Student(101, "Fatiath", 22,"Software Engineering", 3.50);
         s1.displayInfo();
     }
}   
    







    
    # Student-Repository-Java
