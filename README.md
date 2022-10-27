# HashMap LinkedHashMap and TreeMap in Java

## HashMap


```java
public static void main(String []args)
{
    HashMap<String, Integer> map = new HashMap<>();
    map.put("India", 1);
    map.put("USA", 2);
    map.put("China", 3);
    map.put("Asia", 4);

    for(Map.Entry<String, Integer> mapiterator : map.entrySet())
    {
        System.out.println(mapiterator.getKey() + " " + mapiterator.getValue());
    }
}

```

![image](https://user-images.githubusercontent.com/23376002/198285892-b8844b13-2936-4f99-93cf-7f8601ae8174.png)



## LinkedHashMap

## TreeMap
