# Titres

This project simulates the famous game, namely; Titres. The actual code of the game is NOT written by me, i got it from GitHub two years ago, and unfortunately I dont remember the user to mention him.
In this project, the main goal was to apply design patterns, which are  general repeatable solutions to commonly occurring problems in software design, [See more](https://sourcemaking.com/design_patterns). These design patterns are applied  using Java programming language.
<br>
<br>
Five design patterns have been applied depending on the requirements of the project and the applications of each pattern:

- Facade
  - Facade pattern offers a way of communication between clients and subsystems.
  - Provides a unified interface to a set of interfaces in a subsystem. So, instead of instantiating all classes in the main, you can instaniate only the Facade class.

- Singleton
  - Signleton pattern allows creation of one game only for each player, since a user should
    not be able to start more than one game at a time concurrently depending on the logic of most games.
  
- State
  - Allow an object to alter its behavior when its internal state changes. The object
    will appear to change its class. For example, change state from pause to  resume.

- Observer
  - Define a one-to-many dependency between objects so that when one object
    changes its state, all its dependents are notified and updated automatically.For example, if the user completes a row (wins), the score should be updated and the row should be removed. 

- Decorator
  - Decorator pattern attaches additional responsibilities to an object dynamically.
  - It provides a flexible alternative to subclassing for extending functionality.


# Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes:
- Download the project.
- Unzip the project.
- Run the project on a NetBeans IDE.

# Prerequisites

These are the tools and framewroks used in this project (MUST have):

- Netbeans IDE (one of the latest versions is preferred).



