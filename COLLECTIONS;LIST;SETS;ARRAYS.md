#COLLECTIONS : LISTS;SETS;ARRAYS

```
list Extends Iterable 
list Extends Collection
Collactions can only take objects and 
```
```
List extends Collection
(T... a) = Takes a List
```
```
AbstractList extends AbstractCollection implements Collection
```
```
ArrayList are resizable, can only handle Objects
```
#SETS
```
*A (Set) is a Collection that cannot contain duplicate elements.
*The Set interface contains only methods inherited from Collection 
and adds the restriction that duplicate elements are prohibited.
*Two Set instances are equal if they contain the same elements.
*
```
###HashSet,TreeSet,LinkedHashSet,EnumSet,BitSet
```
*The Hashset CANT make duplicates of the same element
*Set<String> set = new HashSet<>(Arrays.asList(words));
```
###TreeSets
```
*Similar to HashSet
*Sorts elements 
```
(x < y ) ? -1 : ((x == y) ? 0 : 1);
This is a if statement with a condition 
(?) means do this so 
? = -1
###DemoSet
```
GOOGLE
```

####LinkedHashSet
```
what you add in this sets them to the back of the List
```
add(Animal animal)
{Animal[] temp = new Animal[theAnimals.length +1];
}
*******
#SETS 
```
HashSet = sorts elements in hash order (fast, not predictable)
Does not maintain insertion-order of elements
Elements are positioned by their hash value.
Can retrieve elements quickly due to efficient hash-sorting
________________________________________________________________
TreeSet = sorts elements in ascending sorted order
LinkedHashSet	= provides insertion-order access to elements
EnumSet	= Optimized set for holding enum instances
BitSet	= Optimized for storing sequences of bits
```
#MAPS
```
HOW TO ITERATE OVER A KEYSET?

```
```
*KEYS ARE USED TO LOOK UP VALUES
*Strings are keys and integers are values
*TREE MAP ORDERS BY THE KEYS ALPHABETICAL ORDER
* MAP can be put in order but dont have a order themselves
* 
```