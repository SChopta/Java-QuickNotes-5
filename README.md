class Robot {
	public void speak(String text) {// You can declare a parameter aka String text similar to a variable ...
		System.out.println(text); }
		
	public void jump(int height) {
		System.out.println("Jumping: " + height);
	}
	public void move(String direction, double distance) {
		System.out.println("Moving " + distance + " metres in direction " + direction);
	}
	
}
public class Project5 {

	public static void main(String[] args) {
		Robot sam = new Robot();
		sam.speak("Hi I'm Sam.");//...which can be passed on to a method.
//Method Parameters aka Passing a Parameter
		sam.jump(7); // you can pass parameters with numbers also
		sam.move("West", 12.2);
		String greeting = "Hello there.";// you can pass a greeting and assign in the same line
		sam.speak(greeting);
	}

}
