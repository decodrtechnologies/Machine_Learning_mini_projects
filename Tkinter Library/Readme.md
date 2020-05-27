# Event Driven Programming using Tkinter

## What is Event Driven Programming?

- Event-driven programming is a programming paradigm in which the flow of program execution is determined by events - for example a user action such as a mouse click, key press, or a message from the operating system or another program. 
- An event-driven application is designed to detect events as they occur, and then deal with them using an appropriate event-handling procedure. 
- In a typical modern event-driven program, there is no discernible flow of control. The main routine is an event-loop that waits for an event to occur, and then invokes the appropriate event-handling routine.
- Event callback is a function that is invoked when something significant happens like when click event is performed by user or the result of database query is available.

Event Handlers: Event handlers is a type of function or method that run a specific action when a specific event is triggered. For example, it could be a button that when user click it, it will display a message, and it will close the message when user click the button again, this is an event handler.

Trigger Functions: Trigger functions in event-driven programming are a functions that decide what code to run when there are a specific event occurs, which are used to select which event handler to use for the event when there is specific event occurred.

Events: Events include mouse, keyboard and user interface, which events need to be triggered in the program in order to happen, that mean user have to interacts with an object in the program, for example, click a button by a mouse, use keyboard to select a button and etc.

## Introduction to GUI:

- A graphical user interface allows the user to interact with the operating system and other programs using graphical elements such as icons, buttons, and dialog boxes.
- GUIs popularized the use of the mouse.
- GUIs allow the user to point at graphical elements and click the mouse button to activate them.
- GUI Programs Are Event-Driven
- User determines the order in which things happen
- GUI programs respond to the actions of the user, thus they are event driven.
- The tkinter module is a wrapper around tk, which is a wrapper around tcl, which is what is used to create windows and graphical user interfaces.

## Tkinter Programming:

- Tkinter is the standard GUI library for Python. 
- Creating a GUI application using Tkinter 

Steps to create a widget. ex- Button.

1. Import the Tkinter module. 
        
        - import tkinter as tk

2. Create the GUI application main window.

        - root = tk.Tk()
        
3. Add one or more widgets to the GUI application.

        - button = tk.Button(root, text='Stop', width=25, command=root.destroy) 
        - button.pack() 
        
4. Enter the main event loop to take action against each event triggered by the user.

        - root.mainloop()




