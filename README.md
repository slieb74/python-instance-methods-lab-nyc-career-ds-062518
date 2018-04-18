
# Practice with Instance Methods

## Introduction
In the last lesson, we talked about what are instance methods. In this lab, we are going to put our new skills to the test and start writing our own instance methods on our classes.

## Objectives

* Practice defining classes and instantiating instances of those classes
* Practice deinfing instance methods and calling them

## Defining Classes

In this section, define two classes, `Driver`, `Passenger`. 

In the `Driver` class, define the instance method `greeting` that returns the string `"Hey, how are you?"`. Then define the method `ask_for_destination`, which returns the string `"Where would you like to go today?"`. 

In the `Passenger` class, define the instance method `reply_greeting` that returns the string `"I am doing well! Thanks for picking me up today!"`. Then define the method `in_a_hurry`, which returns the string `"Punch it! They're on our tail!"`. 

> **Note:** remember that our instance methods need to be defined with the `self` argument in order to be called on an instance of the class. 


```python
# define Driver class and instance methods here
class Driver:
    
    def greeting(self): 
        return "Hey, how are you?"
    
    def ask_for_destination(self): 
        return "Where would you like to go today?"
```


```python
# define Passenger class and instance methods here
class Passenger:
    
    def reply_greeting(self): 
        return "I am doing well! Thanks for picking me up today!"
    
    def in_a_hurry(self): 
        return "Punch it! They're on our tail!"
```

## Instantiate Instances and Practice Using Instance Methods
Great! We've defined our classes and our instance methods. Now, in this section we are going to actually use them!

Start by instantiating two drivers and two passengers. Assign the drivers to the variables `daniel` and `meryl` and assign the passengers to `niky` and `terrance`.


```python
# daniel = None # driver
# meryl = None # driver
# niky = None # passenger
# terrance = None # passenger
daniel = Driver()
meryl = Driver()
niky = Passenger()
terrance = Passenger()
```

Alright, we have our passengers and drivers! Now we need to put those instance methods to use. Let's try them out below. Let's assign the return values to variables too. Let's have `daniel` greet his passenger, who is going to me `niky`. Assign the greeting to the variable, `polite_greeting`. Have `niky` respond by calling `in_a_hurry`, and assign the return value to the variable, `no_time_to_talk`.


```python
polite_greeting = daniel.greeting()
print(polite_greeting)
```


```python
no_time_to_talk = niky.in_a_hurry()
print(no_time_to_talk)
```

## Summary
In this lab, we practiced defining classes and instance methods. We then instantiated instances of our classes and used them to practice calling our instance methods. 
