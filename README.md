# Class-and-object-instance-

CODING:
class Person {
String name;
int age;
Person(String name, int age) {
this.name = name;
this.age = age;
}
void displayInfo() {
System.out.println("Name: " + name);
System.out.println("Age: " + age);
}
}
public class ClassAndObjectExample {
public static void main(String[] args) {
Person person1 = new Person("Jothika", 17);
person1.displayInfo();
Person person2 = new Person("manjula", 17);
person2.displayInfo();
}
OUTPUT:
Name: Jothika Age: 17
Name: Manjula 
Age: 17
