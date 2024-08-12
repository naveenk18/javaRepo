
public class Inheritance {

	public static void main(String[] args) {
		Parent obj1 = new Parent();
		Child obj2 = new Child();
		
		obj1.father();
		obj2.father();
		obj2.son();
	}
}
class Parent{
	public void father(){
		System.out.println("Father");
	}
	public void mother() {
		System.out.println("Mother");
	}
}
class Child extends Parent{
	public void son() {
		System.out.println("Son");
	}
}

