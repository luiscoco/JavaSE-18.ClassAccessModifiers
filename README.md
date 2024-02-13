# JavaSE-Class Access Modifiers

See the Udemy course: https://www.udemy.com/course/curso-certificacion-profesional-desarrollador-java-se-11

In Java, access modifiers are keywords that determine the visibility or accessibility of classes, methods, and other members in a program. 
 
There are four main types of access modifiers in Java:

## 1. Public

Members declared as public are accessible from any other class.

Example:

```java
public class MyClass {
    public int publicVariable;
    
    public void publicMethod() {
        // code here
    }
}
```

## 2. Private

Members declared as private are only accessible within the same class.

Example:

```java
public class MyClass {
    private int privateVariable;
    
    private void privateMethod() {
        // code here
    }
}
```

## 3. Protected

Members declared as protected are accessible within the same package and by subclasses in other packages.

Example:

```java
public class MyClass {
    protected int protectedVariable;
    
    protected void protectedMethod() {
        // code here
    }
}
```

## 4. Default (Package-Private):

If no access modifier is specified (default), it is visible only within the same package.

Example:

```java
class MyClass {
    int defaultVariable;
    
    void defaultMethod() {
        // code here
    }
}
```

Access modifiers help in encapsulation and control the access level of the members, providing a way to implement information hiding and control the scope of your classes and their members.
