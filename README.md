# JavaSE-Loops

See the Udemy course: https://www.udemy.com/course/curso-certificacion-profesional-desarrollador-java-se-11

Loops in Java are used to execute a block of code repeatedly. There are three main types of loops in Java: for, while, and do-while. 

Let me provide you with a brief explanation and some examples for each.

## 1. For Loop:
The for loop is used when the number of iterations is known in advance.

```java
for (int i = 0; i < 5; i++) {
    System.out.println("Iteration " + i);
}
```

In this example, the loop initializes i to 0, executes the block as long as i is less than 5, and increments i in each iteration.

## 2. While Loop:
The while loop is used when the number of iterations is not known in advance, and the loop continues as long as a certain condition is true.

```java
int count = 0;
while (count < 5) {
    System.out.println("Iteration " + count);
    count++;
}
```

Here, the loop continues as long as count is less than 5.

## 3. Do-While Loop:
The do-while loop is similar to the while loop, but it guarantees that the block of code is executed at least once, as the condition is checked after the execution.

```java
int x = 0;
do {
    System.out.println("Iteration " + x);
    x++;
} while (x < 5);
```

This loop will run once, even if x is initially not less than 5.

## 4. Enhanced for-loop

Enhanced for loop, also known as the "for-each" loop in Java. It's used for iterating over collections like arrays or lists. 

The for-each loop simplifies the process of iterating over arrays and collections. 

It eliminates the need for explicit initialization, condition checking, and updating. 

It is especially useful when you want to iterate through all elements in a collection without bothering about the index or size.

```java
// Example: Using for-each loop to iterate over an array
int[] numbers = {1, 2, 3, 4, 5};

for (int num : numbers) {
    System.out.println(num);
}
```

In this example, num takes on the value of each element in the numbers array in each iteration. The loop automatically iterates through all elements in the array without needing an explicit index.

For iterating over other collections like lists, you can use the for-each loop as well:

```java
// Example: Using for-each loop to iterate over a list
List<String> names = Arrays.asList("Alice", "Bob", "Charlie");

for (String name : names) {
    System.out.println(name);
}
```

Here, name takes on the value of each element in the names list.

The for-each loop is concise, easy to read, and reduces the chance of errors related to off-by-one errors in indexing. It's a great choice when you don't need to know the index and just want to iterate over the elements of a collection. 

