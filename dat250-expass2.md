# DAT250 Software Technology Experiment Assignment 2

## Technical problems during installation

I had some technical troubles during this assignment, but not only with using JPA. First I had some trouble building the maven-project, I think this was due to me 
using java 16 as it sorted it self out when i downgraded to java 11. Further I had some trouble creating the database, this turned out to be because I didn't read 
the comment in the persistence.xml-file telling me to change the path. Changing the path (obviously) sorted that out. Otherwise things worked as intended.
I also had some trouble with using git, as I originally had hoped to use 1 repo with 3 branches, one for each code-example, but this turned out to be more trouble
than it was worth due to me not being that well versed with git so I ended up creating one repo for each answer. 


## Links to the code

[Example1](https://github.com/Gudolv/dat250-jpa-ex1/tree/master) /
[Example2](https://github.com/Gudolv/dat250-jpa-ex1-2/tree/master) /
[Experiment2](https://github.com/Gudolv/dat250-exp2/tree/master) /

## Inspecting tables and what tables where created

I used the database-tool in intellij to inspect the tables that were created. Connecting to the database using its path and inspecting it.

### Example 1 - Todo
Here there was just one table created called TODO

![Example1](https://github.com/Gudolv/dat250oblig1/blob/main/Screenshots/Example1.png)

### Example 2 - Family

Here there were 5 tables created, one for each class and  one for each relationship between the different classes. 

![Example2](https://github.com/Gudolv/dat250oblig1/blob/main/Screenshots/Exmple2.png)

### Experiment 2 - Bank

Here there are 10 tables created, one for each of the classes and one for each relationship between the different classes.

![Experiment2](https://github.com/Gudolv/dat250oblig1/blob/main/Screenshots/Experiment2.png)



