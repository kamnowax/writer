# Zadanie 1 – Dependency Injection

## Punkt 1

W projekcie istnieje już mechanizm Dependency Injection typu Constructor Injection.

Obiekt klasy `Writer` oraz wartość `myName` są przekazywane do klasy `Test`
przez konstruktor:

```java
Test test = new Test(new Writer(), "Ohoho");
