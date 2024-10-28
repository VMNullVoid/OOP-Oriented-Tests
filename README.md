# **This repository contains basically all of my exams from College about Object-Oriented-Programming, using JAVA.**
## ***"But what do these programs do? what problems do they solve?"***
## **Here's a quick resume about what each file on this repository do : ** 

### **First Test**
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
***Question 1 (2 points): What are the advantages of working with Object-Oriented Programming (OOP)? Justify your answer by presenting the main differences between OOP and Structured Programming.***
**Answer:**
*Object-Oriented Programming is advantageous compared to Structured Programming because it allows us to work with distinct types and classes for various uses.* 
*We can customize how we solve proposed problems, developing applications more efficiently than when implementing Structured Programming.* 
*Lastly, there are gains in code organization and performance when creating projects.*

***Question 2 (2 points): Explain what you know about Object-Oriented Programming, explaining and correlating the concepts of Classes, Complex Types, Attributes, Methods, Objects, and Instances.***
**Answer:**
*Object-Oriented Programming is based on creating new Classes composed of Complex Types, which are types that originate by combining various primitive data types such as String, int, etc.* 
*The created Classes can contain Attributes and Methods for interaction between the class and the program.*
*Once "called" in the main through the creation of an Object of the Class, which takes the Constructor method with all the base attributes of the Class, we can instantiate it,allocating the necessary space for each variable in memory, and interact with the entire object.*

***Question 3 (2 points): Define and explain the Abstraction pillar of Object-Oriented Programming.
   When thinking about high-level abstraction, how would you define the classes for the types House, Animal, and Patient?***
**Answer:**
*The concept of Abstraction, which encompasses Object-Oriented Programming, consists of "abstracting" a real-world object to identify its attributes and functions and implement them in code. The House class can be defined with attributes such as size, number of floors, doors, windows, rooms, wall color, and anything relevant to the solution. The Animal class can be defined by breed, color, size, sex, age, habitat, and so on. Finally, the Patient class can take into account the name, social security number, ID, date of birth, blood type, medical history, vaccination card, etc.*

***Question 4 (9 points): Regarding the class diagram below, answer the following:***
**c) (1 point) What is the relationship between Car and Accessory? And the relationship between Car and Engine? Explain both relationships.**
**Answer:**
*A Car necessarily has an engine, while it has an accessory but does not depend on it. The primary difference lies in the types of dependency one class has on another when instantiating objects. In the case of the engine, the car is entirely dependent on it to be functional, being a fundamental characteristic of the car, while the accessory is a bonus, which may or may not be present in the car. (I forgot the names of the relationships, but one is "optional" and the other is "mandatory.")*

**d) (2 points) Mark V (True) or F (False) for each alternative:**

    (F) Through only one of a car's accessories, we can determine the engine power of that car.
    (F) We can define a car model by creating a complex type Model.
    (T) A car object contains a relationship to an accessory object, not the other way around.
    (T) To include an accessory object to a car, it is necessary to first instantiate the accessory list and use the add() method.
    (F) It is not possible for an engine object with attribute code = 1 to exist alongside a car object with attribute code = 1.

**e) (2 points) How can we alter the abstraction of the above classes to allow knowing all the accessories of a car that has the same engine through an engine object?**
**Answer:**
*It would be necessary to create a logic where the Engine possesses a car, which in turn has an accessory. We could create a function to display the accessories in the main after instantiating the engine and the car, or attempt to call them directly from the engine.*
Question 1 (2 points): What are the advantages of working with Object-Oriented Programming (OOP)? Justify your answer by presenting the main differences between OOP and Structured Programming.
Answer:
Object-Oriented Programming is advantageous compared to Structured Programming because it allows us to work with distinct types and classes for various uses. We can customize how we solve proposed problems, developing applications more efficiently than when implementing Structured Programming. Lastly, there are gains in code organization and performance when creating projects.

Question 2 (2 points): Explain what you know about Object-Oriented Programming, explaining and correlating the concepts of Classes, Complex Types, Attributes, Methods, Objects, and Instances.
Answer:
Object-Oriented Programming is based on creating new Classes composed of Complex Types, which are types that originate by combining various primitive data types such as String, int, etc. The created Classes can contain Attributes and Methods for interaction between the class and the program. Once "called" in the main through the creation of an Object of the Class, which takes the Constructor method with all the base attributes of the Class, we can instantiate it, allocating the necessary space for each variable in memory, and interact with the entire object.

Question 3 (2 points): Define and explain the Abstraction pillar of Object-Oriented Programming. When thinking about high-level abstraction, how would you define the classes for the types House, Animal, and Patient?
Answer:
The concept of Abstraction, which encompasses Object-Oriented Programming, consists of "abstracting" a real-world object to identify its attributes and functions and implement them in code. The House class can be defined with attributes such as size, number of floors, doors, windows, rooms, wall color, and anything relevant to the solution. The Animal class can be defined by breed, color, size, sex, age, habitat, and so on. Finally, the Patient class can take into account the name, social security number, ID, date of birth, blood type, medical history, vaccination card, etc.

Question 4 (9 points): Regarding the class diagram below, answer the following:
c) (1 point) What is the relationship between Car and Accessory? And the relationship between Car and Engine? Explain both relationships.
Answer:
A Car necessarily has an engine, while it has an accessory but does not depend on it. The primary difference lies in the types of dependency one class has on another when instantiating objects. In the case of the engine, the car is entirely dependent on it to be functional, being a fundamental characteristic of the car, while the accessory is a bonus, which may or may not be present in the car. (I forgot the names of the relationships, but one is "optional" and the other is "mandatory.")

d) (2 points) Mark V (True) or F (False) for each alternative:

    (F) Through only one of a car's accessories, we can determine the engine power of that car.
    (F) We can define a car model by creating a complex type Model.
    (V) A car object contains a relationship to an accessory object, not the other way around.
    (V) To include an accessory object to a car, it is necessary to first instantiate the accessory list and use the add() method.
    (F) It is not possible for an engine object with attribute code = 1 to exist alongside a car object with attribute code = 1.

e) (2 points) How can we alter the abstraction of the above classes to allow knowing all the accessories of a car that has the same engine through an engine object?
Answer:
It would be necessary to create a logic where the Engine possesses a car, which in turn has an accessory. We could create a function to display the accessories in the main after instantiating the engine and the car, or attempt to call them directly from the engine.

**f) (2 points) Observe the code below:**

      |------------------------------|
      |Motor motor1 = new Motor();   |
      |Motor motor2 = new Motor();   |
      |Carro carro1 = new Carro();   |
      |Carro carro2 = new Carro();   |
      |carro1.motor = motor1;        |
      |carro2.motor = motor2;        |
      |motor1.potencia = 100.0;      |
      |motor2.potencia = 200.0;      |
      |carro2.motor = carro1.motor;  |
      |carro1.motor.potencia = 100.0;|
      |carro2.motor.potencia = 200.0;|
      |------------------------------|
**At the end of the program, what is the power of the engine of car1? And what is the power of the engine of car2? Discuss your answer explaining what you know about the concept of object references.**
**Answer:**
*Power of the engine of car1: 200.0*
*Power of the engine of car2: 200.0*
*There was a prior assignment of the powers separately. However, when doing "carro2.motor = carro1.motor;", both car2 and car1 point to the same memory reference, so any alteration in one of the objects results in a change in both. Therefore, both powers are equal to 200.0.*

|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|

### **Second Test**
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
**The majority of the questions were in-code related, so the following questions will be about the non-code related questions!
1)
a- (2 points) - Identify and present the elements that characterize inheritance and polymorphism;**
**Answer:**
*The term extends in: public class Corrente extends Conta, the reference to superclass attributes in: super(codigo); super.transferir(valor, conta); and super.transferir(valor, conta);, as well as the Override in @Override public void sacar(double valor).*

**b- (3 points) - Present a possible Conta class that is compatible with the Corrente class. Thus, the Corrente class must conform to the Conta class, respecting all OOP principles.
2)
4- What are the names given to the method creations made in topics 2 and 3? Explain the difference.**
*In topic 2, the name is Override, while in topic 3 it is Overload. Override consists of using a structure similar to Super in the received parameters but performing different operations from the originals. 
On the other hand, Overload consists of writing methods with the same name but with different signatures (parameters varying in type, quantity, or value).*
**Question 1 (5 points): Observe the class below and do:
public class Corrente extends Conta {
    public Corrente(int codigo) {
        super(codigo);
    }
    @Override
    public void sacar(double valor) {
        double juros = getSaldo() * 0.01;
        sacar(valor, juros);
    }
    public void transferir(double valor, Poupanca conta) {
        super.transferir(valor, conta);
    }
    public void transferir(double valor, Corrente conta) {
        super.transferir(valor, conta);
    }
}
a) (2 points) - Identify and present the elements that characterize inheritance and polymorphism.
b) (3 points) - Present a possible Conta class that is compatible with the Corrente class. Thus, the Corrente class must conform to the Conta class, respecting all OOP principles.**
**Question 2 (5 points): Observe the class below and do:
public class Calculadora {
    public int calcular(int a, int b) {
        return a + b;
    }
}
Implement subclasses for Multiplication, Division, Subtraction, and Addition that inherit from the Calculadora class.
For each subclass, consider how to perform the specific calculation for each class. For example, the calcular method in the Subtraction class should perform the subtraction of a - b. The calcular method in the Multiplication class should perform the multiplication of a * b.
Also write, for each subclass, a method capable of performing calculations considering decimal values.
What are the names given to the method creations made in topics 2 and 3? Explain the difference.**

**Question 3 (5 points): Implement the problem below:
a)Implement a Produto class that has the attributes nomeloja and preco, and create the set and get methods for these attributes.
Also, create the attribute descricao and its method called getDescricao that returns a String with the simple content “Produto de informática”.**

**b)Create two subclasses of Produto, which will be Mouse with the attribute tipo and Livro with the attribute autor. 
In the constructor of each of these classes, pass as an argument the description of this product, for example, Mouse(“Optical Mouse, USB Output. 1,600 dpi”);
Override the getDescricao method to return the description passed in the constructor argument concatenated with the attribute the class has, for example: 
“autor” in the case of a book and “tipo” in the case of a mouse. This method should have the same signature as the getDescricao method from the parent class Produto.**

**c)Create a class for the main method that will simulate a customer purchasing various mice and books. Therefore, there should be only one array/list in the class to store all the books and mice. 
This array/list should be called carrinho, simulating the shopping cart of a customer's varied products in an e-commerce setting. 
Insert several mice and books into this carrinho and then call the getDescricao method of all the objects present in the array/list so that the user of the cart knows the information of the products in their cart.**

|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|

### **Last Test**
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
**a) (6 points) Implement the diagram represented above in Java. Use your knowledge of OOP to ensure that the implementation is as faithful to the represented diagram as possible. To do this, consider:
  Enhance your implementation with the pillars of abstraction, encapsulation, inheritance, and polymorphism, which should be identified and added;
  When withdrawing, a Physical Account should deduct 2% of the amount to be withdrawn, and a Legal Account should deduct 4% of the amount to be withdrawn;
  The ContaImpl class should not be instantiable;**

**b) (2 points) What are the relationships between <<interface>> Account, ContaImpl, ContaFisica, and ContaJuridica?**
*The Account interface establishes the contract to be formed according to the main characteristics that an account must have; 
the ContaImpl class implements this interface, establishing methods that meet the contract; ContaFisica, in turn, customizes certain methods of ContaImpl,
just as ContaJuridica also customizes but following the requirements made in relation to a company.*

**c) (2 points) What are the relationships between Pessoa and ContaFisica, Empresa and ContaJuridica, Banco and ContaFisica, and ContaJuridica?**
*A Pessoa has a ContaFisica, just as a Empresa has a ContaJuridica. A Banco has a list of accounts, which can be of type ContaFisica or ContaJuridica.*

**d) (2 points) Describe details of how we can implement the ContaImpl class, considering that it cannot be instantiated. Explain!**
*The ContaImpl class cannot be directly instantiated, as it is an abstract class. However, it is the superclass of ContaFisica and ContaJuridica,
so it is enough to use one of the two types when instantiating a certain account.*

**e) (3 points) Evaluate the implementation below and present the results of contaA, contaF, and contaJ:**
contaA: Balance 0
contaF: Balance 0
contaJ: Balance 204

**Question 3 (10 points): Mark V for true statements or F for false statements.
(F) - A class must always contain attributes and methods.
(F) - Attributes cannot be public.
(F) - Methods must be private.
(T) - A subclass can also be a superclass.
(T) - We should inherit a class using extends.
(T) - We should create polymorphism using super.
(F) - Overload polymorphism allows us to create methods with the same signature.
(F) - We can override a method that is not being inherited.
(T) - An abstract class cannot be instantiated.
(F) - A static class can be instantiated.
(T) - An abstract class can be inherited.
(T) - A static class cannot be inherited.
(T) - An abstract class uses the abstract modifier.
(T) - A static class uses the static modifier.
(F) - An abstract class will always be a superclass.
(F) - In an abstract class, all methods must be abstract.
(F) - A single abstract method can exist in a non-abstract class.
(T) - In a static class, all members must be static.
(F) - An interface defines a series of methods and their implementations.
(F) - We should implement an interface through interfaces.**
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
