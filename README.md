# Compile instructions for JAVA
add line

javac --source-path myapp -d bin myapp/*
 - creates a seperate "bin" folder and compiles the code there
 - source-path myapp points to where to look for the file
 - -d bin defines the output of the .class file to be bin folder

java -cp bin myapp.HelloWorld
- -cp is classpath, tells where to find the class

jar -c -v -f hWorld.jar -e HelloWorld . (run jar --help to see options)
- -f XXX denotes the file name as XXX
- -e is the main class name, indicates to look for this class
- . to create the jar file in the current working directory 


java -jar hWorld.jar HelloWorld