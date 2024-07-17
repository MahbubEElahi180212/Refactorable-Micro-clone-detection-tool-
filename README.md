
# Important Micro-clone Detection Tool

This is a tool which will identyfy micro-clone that can be considered important for refactoring.

Code clone: it refers to duplicate or nearly duplicate code segments within a codebase. These clones can arise for various reasons, such as copying and pasting code to reuse functionality quickly without implementing proper abstractions.

 Micro-clone: Code clone which which is less than 5 LOC (lines of code) is called micro-clone.

 Refactoring:Refactoring involves restructuring existing code without changing its external behavior which will increase the readability of the code,increase the computation cost and deseacrease code smell.

 In code clone refactoring can be done by merging the similar code segemet by renaming variable if required.

 Our tool will identify important candidate for refactoring.
## Deployment of the projoect



#### 1. Install Java Runtime Environment

First, ensure that Java is installed on your system. You can install it using the package manager of your Linux distribution.
```bash
sudo apt update
sudo apt install default-jre
```


#### 2. Verify Java Installation:

```bash
 java -version
```

#### 3.Navigate to the Directory Containing the JAR File:

```bash
 cd /path/to/your/jar/file
```

### 4.Run the JAR File:
Use the java -jar command followed by the name of the JAR file to run it. For example:

```bash
 java -jar ICMS.jar

```
### 5.Run the program : 
ICMS (Integrated Clone Management system) terminal will open. 
 #### (i) Set subject system path
  ####  (ii)Set the programming language
  ####  (iii) Set the last Revision
  ####  (iv) Set the Database Connection seeting.
   ####  (v) Click the "Show Method Analysis Dialog" button which will lead you to a   new terminal
   ####  (vi) Run all the button from "Extract Methods" to "Map changes to Methods"

  
  ####  (vii) Now click the "Show Clone Analysis Dialog" button which will lead you to a new terminal
  ####  (viii) Set the clone type in that terminal
  ####  (ix) Run all the button from "Show Clone Analysis Dialog" to "Refactorable Micro clone"

  This willl store all the refactorable micro-clone candidate in the database

  


