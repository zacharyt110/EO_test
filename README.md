# EO_test
Concept for a program to aid in EO test setup and data recording. It currently simulates data entry by generating random numbers and checks them for greater than/less than.

I also like how the GUI is set up in this code because:
   - The GUI is modular in that each component is contained in their own function.
   - initUI calls each of the functions to add them and place them into a sub-layout which is managed by initUI.
   - Other classes are instantiated in the __init__ function and are accessible by the rest of the GUI through initUI.

For these reasons I may want to use this as a model for all future GUIs.
