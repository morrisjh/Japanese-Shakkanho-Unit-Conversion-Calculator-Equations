# Japanese-Shakkanhō-Unit-Conversion-Calculator-Equations
A project for creating a conversion calculator to convert traditional Japanese units to metric and imperial units of measurement.

This project was created to share the source code of a conversion calculator that I created on the online system, vCalc. 

The calculator can be viewed here: https://www.vcalc.com/wiki/jmorris/Japanese+%28Shakkanh%C5%8D%29+Unit+Conversion+Calculator

The calculator was written using Apache Groovy, however, since vCalc fills in the context and other aspects of the code, only the basic algorithms needed for the equations used in calculator are included here. These equations principally define the value of Shakkanhō units based on their metric conversion, but also include a "switch" function. 

Each file contians an edited version of the source code written for the calcualtor hosted on vCalc. On the vCalc system, I created the Shakkanhō units (constants) seperately from their equations, and then imported the units into their respective equations using the "getConstant" function. Since using this function to import unit definitions would be ineffective without access to the vCalc database, I have redacted the source code so that each equation defines each unit according to a metric measurement. The code provided here, therefore, combines both the equations and constants created for the calculator on the vCalc system.

THe files are grouped according to the type of units used (area, length, weight etc.) Feel free to reuse the equations and constant definitions in your own projects.

In the future, I plan develop the code further in order to create a downloadable conversion calculator seperate from the vCalc system.
