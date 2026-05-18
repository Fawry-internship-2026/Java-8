# Java 8 Streams & Lambdas

This repository contains my solution for the Java 8 task as part of the **Fawry Internship**. 

##  Topics
*   **Java Streams API:**

  
     Building data pipelines using `.stream()`, `.filter()`, `.flatMap()`, `.mapToDouble()`,


    and terminal operations like


    `.forEach()` and `.average()`.
*   **Lambda Expressions:** Writing concise, inline implementations to reduce boilerplate code.
*   **Method References:** Using shorthand syntax like `System.out::println` for cleaner readability.
*   **Functional Interfaces:** 
    *   `Predicate<T>`: For evaluating boolean conditions (e.g., checking if a book is published).
    *   `Consumer<T>`: For executing actions (e.g., printing objects to the console).
    *   `Function<T, R>`: For transforming data (e.g., mapping an Author to a Stream of Books).
    *   `ToDoubleFunction<T>`: For extracting primitive `double` values efficiently without object wrapper overhead.
    *   `OptionalDouble`: For safely handling the results of mathematical stream operations.

