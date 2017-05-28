This Android application is going to be designed around the MVC concept which is utilized in most GUI applications.
The acronym stands for Model, View and Controller.

Model: The model is a term used to represent the basic objects which are utilized to define the data that is being handled.
In our case an example of data representations would be a contact object.

View: The user interface. Any class that displays a user interface and handles user input.

Controller: Generally any class defined in this category handles the manipulation of the data based on input from the user
interface. An example of this would be a class that allows one to store data in a database after a user clicks save.

The main package of this project contains three packages which are meant to store classes of the above three categories.

All three of the packages can be found in the groupalliance.projectreminder package.

data_representations package: This package will hold all classes that fit into the Model category.

user_interface package: This package will hold all classes that fit into the View category.

primary_operations package: This package will hold all classes that fit into the Controller category.

Any class contributions need to be appropriately placed in these packages.
