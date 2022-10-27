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


## TreeMap
