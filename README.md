# JavaSE-Loops

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


