Polymorphism & Composition Homework - Quiz

Polymorphism

What does the word 'polymorphism' mean?
Many Forms

What does it mean when we apply polymorphism to OO design? Give a simple Java example.
It means that we can treat an instance of a class as if it is an instance of a different class. E.g. a car object can be treated as a vehicle object.

What can we use to implement polymorphism in Java?
We can use abstract classes or interfaces.

How many 'forms' can an object take when using polymorphism?
It can take as many forms as it has implemented interfaces, and it can implement as many interfaces as we like

Give an example of when you could use polymorphism.
E.g. In Java, all objects in an array must be of the same class. If we want to create an array of computer input devices, but each device has it's own class, then we can use interfaces and polymorphism to give them the same class and put them in an array together.


Composition
What do we mean by 'composition' in reference to object-oriented programming?
Objects being composed of other objects

When would you use composition? Provide a simple example in Java.
A kitchen object might be composed of a cooker object, a fridge object and a sink object.

What is/are the advantage(s) of using composition?
It allows an object to use the behaviour of other objects of which it is composed. It also allows those behaviours to change at runtime.

What happens to the behaviours when the object composed of them is destroyed?
The behaviours are also destroyed.
