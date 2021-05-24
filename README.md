import java.util.HashMap;

public class Jala {
	public static void main(String[] args){
		HashMap<Integer,String> map = new HashMap<Integer, String>();
		

		map.put(1, "Sai");
		map.put(2, "Yesh");
		map.put(3, "John");
		map.put(4, "Yuvraj");
		map.put(5, "Rishabh");
		map.put(6, "Nithin");
		map.put(7, "Anu");
		map.put(8, "Khanna");
		map.put(9, "Jala");
		map.put(10, "Sri");
		
		//insert a key value into map
		map.put(11, "Ram");
		
		//fetch the value of a key
		System.out.println(map.get(5));
		
		//create a clone/copy of hashmap
		System.out.println(map.clone());
		
		//check whether map contains a particular key or not
		System.out.println(map.containsKey(10));
		
		//check whether map contains a particular value or not
		System.out.println(map.containsValue("Anu"));
		
		//check whether map is empty or not
		System.out.println(map.isEmpty());
		
		//print size of map
		System.out.println("Size of map is : "+map.size());
		
		//print all the keys of the map
		System.out.println("Keys are : "+map.keySet());
		
		//print all the values of the map
		System.out.println("Values are : "+map.values());
		
		//remove a specific key-value pair
		map.remove(6);
		
		//copy into another hashmap
		HashMap<Integer,String> map2 = new HashMap<Integer, String>();
		map2.putAll(map);
		System.out.println("The new Hash-Map is : " + map2);
		

	}
}
