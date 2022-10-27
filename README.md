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

### Output :
USA 2
Asia 4
China 3
India 1



## LinkedHashMap

```java
public static void main(String []args)
{
    LinkedHashMap<String, Integer> map = new LinkedHashMap<>();
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

### Output :

India 1
USA 2
China 3
Asia 4



## TreeMap
