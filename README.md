import java.util.*;

public class Main {
    public static void main(String[] args) {
    HashMap<String,String> map=new HashMap<>();
        map.put("kk","kalaikulfi");
        map.put("km","kalaimani");
         map.put("vs","venkaiyan sumathi");
        map.remove("kk");
        System.out.println(map.get("vs"));
        System.out.println(map.get("kk"));
        System.out.println(map.get("km"));
        System.out.println(map.getOrDefault("kalai","not fount"));
     for(String key:map.keySet()){
        System.out.println(key +" "+map.get(key));
     System.out.println(map.size());
        System.out.println(map.isEmpty());
     System.out.println(map.containsKey("kk"));
         System.out.println(map.containsValue("kalaikulfi"));
    }
  }
}
