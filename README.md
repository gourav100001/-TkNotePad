# -TkNotePad
We shall import the tkinter library first. In addition, we'll import the "filedailog" module from the tkinter library, which contains the classes and factory functions needed to build file selection windows.

Now, we'll use the "class" keyword to create a class called "Notepad." The parameter "tk. Tk" will be passed during this operation, creating the root object for our GUI application. In this section, we'll define a "__init__" constructor with the following parameters: self, *args, and **kwargs.


The ".title" method will be used in this constructor to define the title. The ".Text()" method will be used to create a Text widget, and the ".pack()" method will be used to fill the entire frame with this widget.

We will use ".Menu()" to create the menu widget so that the notepad can display a menu bar.

In this project, the File menu will offer the following features: New, Open, Save, and Exit.

and the edit menu will offer the following features: cut, copy, and paste.

The ".add_cascade()" method will be used to construct the options listed below. By linking the specified menu with the parent menu, this function will generate a new hierarchical menu. The "command" argument will be used to pass the user-defined functions that will carry the specific functionality during this process. Both primary menu items will be produced in this way.





