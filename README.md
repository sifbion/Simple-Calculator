

The simple calculator application is a core java project
which makes use of swing library with in java SDK. This application has a user
interface popping up as we run the application. The arithmetic operations are
performed using the library found in  https://github.com/swampy2b/calculator
 from GitHub. By downloading calculator-master.zip
and extracting it in to a folder, I have imported the package com/calculate, as
mentioned in the documentation.  I had to
rename the package declarations of the library classes to match my package
structure, since I am directly adding the source code in to my project.  The library was not packaged as a pluggable
components and I had to make some changes on the package names. The other minor
fault was that methods start with capital letters (Java standard naming is that
methods start with lower case letters), other than that the library is very
easy to reuse. Methods are overloaded to performer the same operation on
varying input types, like integers, float, double, making it very easy to call
the methods. 


To run this calculator app, import the project in to
Eclipse, do a build, navigate to basicOperations package under src folder,
right click on SimpleCalculator and click run as a java project. A java swing
pop up window will appear to take inputs and when we hit the "=" sign
the results should be displayed.


