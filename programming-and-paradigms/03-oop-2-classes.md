# OOP 2 - Classes and Inheritance
In the last installment you saw how to build programs from units of code called objects.  In the code-series 'Objects' you saw functions that produce objects.  This lesson you will see the next conceptual step (Inheritance) and the JS language feature for implementing it (Classes).
___
### Why Not Literals ?
Object literals are great for representing single objects, but the fail to capture the relationships between single objects.

An intuitive analogy is the tree of life:
* All mammals have hair and warm blood.
* Some mammals have wings and others don't, but they all still have hair.
* Mammals and reptiles all have a spine, but don't share warm blood.
* No two animals have an identical genome.
* ...

There is a hierarchy of traits in the animal kingdom.  Some traits are unique to single animals, some traits are unique to a species, some to a genus, ... until you arrive at a few traits common to ALL animals.

With object literals there is no efficient way to model this, you'd have to go object-by-object and make sure that the jelly fish has what it needs, the bat has what it needs, the lizard, ...  
Wouldn't it be nice if there was a way to simply say 'this object is a lizard' and automatically give it all lizard properties? And if we wanted to change shared properties of lizards without having to find ALL lizards and change them ALL one at a time?

There is with classes and inheritance.
___
### Why Classes and Inheritance ?
* _Dynamic Control_: Modify the behavior of your entire program from a single location (the Class definition).
* _Code Reuse_: Make endless objects without needing to write endless objects by hand.
* _Effective Modeling_: Create large and accurate models of the real world in your program by mimicking real-world classifications (ie. novels and thesauri are both books).

Understanding inheritance allows you to achieve more with less code. With Class syntax it's not only more with less, it's completely new possiblities.  
___
  
instances and classes  
  
what goes in class, what goes in instance?

* [outstanding video](https://www.youtube.com/watch?v=SS-9y0H3Si8)