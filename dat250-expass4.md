# DAT250: Software Technology Experiment Assignment 4


## Technical problems

I had some trouble getting the **<maven-assembly-plugin>** in the counters **pom.xml-file** to build, it seemed to randomly stop working. It started working a while after adding a <version> bracket then it stopped working again. I'm not sure what the problem was and have no imidiate solution, but it worked long enough to run the counters. Another problem I had was building a database when using the Todo-example, this turned out to be my own fault, as I had forgotten to add :derby: in the path, a suprising amount of time wasted finding the root of this :(
Otherwise things went smoothly.
  
## Code
  
[Experiment 4](https://github.com/Gudolv/restapi-experiment)
  
## Pending issues
  
I think all the required CRUD-operations are functional, but I'm not sure if this is the correct approach to doing it. It might have been better to skip the extra class CreateTodos and just write everything in the Main-class. 
  


