# java


### Hello java 

```syntax
public class Hello {
    public static void main (String kaushik[])
    {
        System.out.println("Welcome to fwsa");
    }
}
```

## Hello java Result

![Screenshot (94)](https://user-images.githubusercontent.com/93571059/161693524-d54333a9-0575-4d6b-8584-19bd304cc4e0.png)

### Naming 

```syntax
public class naming {
    public static void main (String args[]){
        String name = "kaushik" ;
        System.out.println(name);
    }
```

## Naming Result

![Screenshot (95)](https://user-images.githubusercontent.com/93571059/161693585-4f7f925d-4c85-4ba2-83da-eca1f01b8727.png)

### Number 

```syntax

public class number {
    public static void main (String args[]){
        int age = 18;
        System.out.println(age);

    }
```

## Number Result
![Screenshot (96)](https://user-images.githubusercontent.com/93571059/161693626-d8adde75-bb7e-4331-9fdc-f95f9928c09e.png)

### Changing Numbers 

```syntax
public class changingnumb {
    public static void main (String args[]){
        int age = 18;
        age = 20;
        System.out.println(age);
    } 
 ```
 
 ## Changing Numbers Result
 
 ![Screenshot (97)](https://user-images.githubusercontent.com/93571059/161693662-6c37173b-1528-4dac-99b6-04d799ed0baf.png)

 ### Final OR Const
 
 ```syntax
 public class finalORconst {
    public static void main (String args[]){
          final int number = 18;
          number = 20; // will generate an error: cannot assign a value to a final variable
          System.out.println(number);
    }
}
```

### Data Types 

```syntax
public class Datatypes {
    public static void main (String args[]){
        String name = "Kaushik";                                    // String
        int age = 18;                                              // Integer (whole number) 
        char gender = 'M';                                        // Character
        boolean active = true;                                   // Boolean
        float rating = 4.5f;                                    // Floating point number  
        System.out.println(name +age +gender +active +rating);
    }
}
```

### Primitive Data Types

## A primitive data type specifies the size and type of variable values, and it has no additional methods.

## There are eight primitive data types in Java:

![Screenshot (103)](https://user-images.githubusercontent.com/93571059/161821015-42ce7baf-f968-4f99-8cd5-fe4684d2d75f.png)


## Data Types Result

![Screenshot (104)](https://user-images.githubusercontent.com/93571059/161821633-f4f35996-201d-42b8-a369-914fa23ab377.png)

### Printing variables

```syntax
public class addingopp {
    public static void main (String args[]){
    String firstName = "Kaushik ";
    String lastName = "Singh";
    String fullName = firstName + lastName;
    System.out.println(fullName);

//adding num:

    int x = 5;
    int y = 6;
    System.out.println(x + y);
    
    }
}
```

## Printing Variables Result

![Screenshot (100)](https://user-images.githubusercontent.com/93571059/161819816-5e3d7bc3-a9ea-4c2f-b54a-2304e5d5963b.png)

### Declare Many Variables

```syntax
public class addingint {
    public static void main (String args[]){
        int x = 5;
        int y = 5;
        int z = 50;
        System.out.println(x + y + z);
    //Can be written simple..

    // int x = 5, y = 6, z = 50;
    // System.out.println(x + y + z);
    }
}
```

## Declare Many Variables Result

![Screenshot (101)](https://user-images.githubusercontent.com/93571059/161819887-b471fdb7-297b-4a02-9bba-f8e94cbcb911.png)
