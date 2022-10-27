# HashMap LinkedHashMap and TreeMap in Java

- All of these cannot be used to store duplicates. We cannot have multiples values for a single key, and just in case we have 2 values then the hashtable will store the latest value for that particular key. 


## HashMap

- HashMap is implemented as a hash table, and there is no ordering on keys or values. 


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

#### Output :

```java
USA 2
Asia 4
China 3
India 1
```


## LinkedHashMap

- LinkedHashMap preserves the insertion order.


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

#### Output :

```java
India 1
USA 2
China 3
Asia 4
```


## TreeMap

- TreeMap is implemented based on a red-black tree structure, and it is ordered by the key.

```java
public static void main(String []args)
{
    TreeMap<String, Integer> map = new TreeMap<>();
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

#### Output :

```java
Asia 4
China 3
India 1
USA 2
```





