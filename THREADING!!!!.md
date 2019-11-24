#THREADING
```
1. THREADS CAN BE CREATED BY USING TWO MECHANISMS : 
 *Extending the Thread class
 *Implementing the Runnable Interface
```
```
1. We create a class that extends the java.lang.Thread class
2. This class overrides the run() method available in the Thread class
3. A thread begins its life inside run() method.
4. We create an object of our new class and 
call start() method to start the execution of a thread. 

5. Start() invokes the run() method on the Thread object.
```
###Thread Class vs Runnable Interface
```
1. If we extend the Thread class, our class cannot extend any other
class because Java doesn’t support multiple inheritance. 
But, if we implement the Runnable interface, our class can
still extend other base classes.

2. We can achieve basic functionality of a thread by extending
Thread class because it provides some inbuilt methods like yield(),
interrupt() etc. that are not available in Runnable interface.


```
