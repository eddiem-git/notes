#STREAMS
```
Stream<String> stringStream = Arrays.stream(stringArray)
(System.out::print)
```
```
Stream<String> stringStream = Stream.of("The", "Quick", "Brown", "Fox")
(System.out::print)
```
```
Stream<String> stringStream = Stream.generate() -> "Hello World");
return stringStream
```
```
Stream<Double> randoms = Stream.generate(Math :: random);
return randoms;
```
```
Stream.SubStream
Stream.concat
Stream.Iterator

```
```
FILTER = like .equals (transformation yeilds a new stream 
with elements that match the specified crtieria)

MAP = transformation takes an arguement of a function applies 
the function to each elment and returns the respective stream
Stream.of(listWords ).map(w ->

FLATMAP = 
```
```
Distinct = returns the stream with duplicates removed
return Stream.of(words).distinct();
```
```
.count = length stream
.min and .max = 
```
