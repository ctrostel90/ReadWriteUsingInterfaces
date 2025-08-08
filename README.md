# Using Interfaces to split Set and Get on a Property

With this example it shows how one could have a variable on an class that the class can chose to distribute READ only access or both READ/WRITE access to a variable by the use of interfaces.

##

Set Mover.Parameter.Position, the internal Task on the mover will then set that to the Mover.Status output.

Notice that you are not able to edit Mover.Status in logic.

As a seperate implementation, one can also use the __QUERYPOINTER() function to use pointers to acomplish the same effect. Use the `Mover.PointerExample` bit to swap between using the pointer implementation and the interface implementation.

