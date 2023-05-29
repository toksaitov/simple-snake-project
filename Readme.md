Simple Snake Game
=================

![Snake](https://i.imgur.com/Y1gZNtL.png)

The main goal of this project is to build a simple [Snake](https://en.wikipedia.org/wiki/Snake_(video_game_genre)) game written in Java with the use of JSwing GUI framework.

The game should adhere to the best Object-Oriented Programming (OOP) principles. All classes and objects should demonstrate the principles of Encapsulation, Inheritance, Polymorphism, and Abstraction.

Your code should be consistently formatted, following best practices for coding style in Java. This includes proper naming conventions, indentation, use of whitespace, and concise comments.

The game should follow the [Model-View-Controller](https://en.wikipedia.org/wiki/Model–view–controller) (MVC) pattern. The Model classes should contain game state data and game logic, the View classes should contain the Canvas drawing logic, and the Controllers should link the Model and View by responding to external and internal events.

The Snake game project should help students apply the concepts they've learned in class, like OOP principles, software architectural patterns, and coding best practices. Good luck with your project!

You can watch the video below demonstrating a possible game that you may create:

[![Snake Game](https://i.imgur.com/F7BC1tz.png)](https://drive.google.com/file/d/1kBe7nehKKlx5k5kf540wZAcEm3r-lgOj/view)

Remember that this is just an example. You can build your own game with your design and features. Be creative, but implement at least the following things outlined below.

## Required Game Elements:

* Title Screen: The game should start with a 'Title' screen featuring a game logo and a button to start the game.

![Title Screen](https://i.imgur.com/eZYHJcl.png)

* Game Screen: By pressing the button to start the game, the program should switch to the gameplay screen, allowing the player to control the snake and play.

![Game Screen](https://i.imgur.com/40sYY8Z.png)

* Pause Screen: The player should be able to pause the game by pressing the `ESC` key. When the game is paused, a 'Pause' screen should appear with a button that allows the player to resume the game. Pressing the `ESC` key again should also unpause the game.

![Pause Screen](https://i.imgur.com/QPXNVRE.png)

* Defeat Screen: If the player loses, a 'You Lost' screen should appear with a button that allows the player to return to the 'Title' screen.

![Defeat Screen](https://i.imgur.com/6bAQjbu.png)

## Additional Requirements:

* Do the code yourself and keep a detailed project commit history. You will not get any points if we suspect you have copied the code from somewhere else (even if it is not true). Remember that this is a bonus project. You are not required to do it. If you do it, do it yourself. Extra points are not given, if we have any doubts about anything or are not impressed by the quality of the work.

## Deliverables

* The project should contain separate packages for Model, View, and Controller classes.
* The program's main entry point should be the `Main.java` file.
* The project should be developed in your private course directory and the sources should be placed into a module under the name `project`.
* The final project should include all source code and support files (images, fonts, sounds, etc.) needed to run the game.

When you finish, your repository should look something like this:

```
.
└── project
    ├── data
    │   └── ... (images, fonts, sounds, etc.)
    ├── project.iml
    └── src
        ├── Main.java
        └── game
            ├── ... (other game classes you need)
            ├── controllers
            │   ├── ...
            │   ├── ...
            │   └── ... (your controllers)
            ├── models
            │   ├── ...
            │   ├── ...
            │   └── ... (your models)
            └── views
                ├── ...
                ├── ...
                └── ... (your views)
```

Commit and push your work periodically. Finally, submit the last commit ID before the deadline to your (!) Lecture instructor's email, NOT your lab instructor's email.

## Deadline

Check your instructor's correspondence for information about the deadlines.

## Links

### JSwing

* [Creating a GUI With Swing](https://docs.oracle.com/javase/tutorial/uiswing/)

## Books

* Intro to Java Programming, Comprehensive, 12th Edition by Y. Liang
