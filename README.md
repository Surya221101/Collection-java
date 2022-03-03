# Collection-java
//I have a basic collection interface program ,here i have extended Set interface from collection nd this set interface then is implemented by HashSet class
package collection;
import java.util.*;
public class Demo1 {

	public static void main(String[] args) {
		Set s=new HashSet();
		s.add(23);
		s.add(2.45f);
		s.add('w');
		s.add("Surya");
		s.add(23.45);
		System.out.println(s.size());
		System.out.println(s.isEmpty());
		System.out.println(s.contains(23));
		System.out.println(s);
		System.out.println(s.remove(23.45));
		System.out.println(s);
		Object []a=s.toArray();
		for(Object i:a) {
			System.out.println(i);
		}

	}

}
