```java
// Sofabeddd.java
package io.github.sofabeddd;

class Sofabeddd {

  static String[] userInfo = {

    "Age: 16",
    "Sex: Male",
    "Profession: Student",
    "Location: United States"

  };

  static String[] contactInfo = {

    "Discord: sofabeddd#0001"

  };

  public static void main(String[] args) {

    System.out.println("I am just your average Minecraft plugin developer.");
    System.out.println("\nSome info about me:");
    
    for (String info : userInfo) {
    
      System.out.println(" - " + info);
      
    }

    System.out.println("\nWays to contact me:");

    for (String info : contactInfo) {
    
      System.out.println(" - " + info);
      
    }
    
  }
  
}
```

```console
Console
> I am just your average Minecraft plugin developer.
>
> Some info about me:
>  - Age: 16
>  - Sex: Male
>  - Profession: Student
>  - Location: United States
>
> Ways to contact me:
>  - Discord: sofabeddd#0001
```
