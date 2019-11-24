@Ron D Typically
One of the biggest headaches when trying to build a console-based application is retrieving input from the user.
Typically, when fetching user-inpout, you will _prompt_ the user with some output. This code comes in the form of


```
Scanner scanner = new Scanner(System.in);

System.out.println("Please enter your name:");
String name scanner.nextLine()


System.out.println("Please enter your age:");
String ageAsString = scanner.nextLine();
Integer age = Integer.parseInt(ageAsString);


System.out.println("Please enter your initial balance");
String ageAsString = scanner.nextLine();
Double balance = Double.parseDouble(ageAsString);

BankAccount bankAccount = new BankAccount(name, age, balance);
```

However, we can abstract this fetching of input and sending of output by creating methods to handle each _type_ of input.

> `getStringInput`
> `getIntegerInput`
> `getDoubleInput`


After abstraction, the code reforms as

```
String name =  Console.getStringInput("Please enter your name:");
Integer age =  Console.getStringInput("Please enter your age:");
Double balance =  Console.getStringInput("Please enter your name:");
BankAccount bankAccount = new BankAccount(name, age, balance);
```
