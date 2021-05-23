You can compile, package and run this simple java application with the commands below. If hello.jar file and the class files are already created you can delete them.

1. javac src/\*/\*.java   src/\*/\*/\*.java -d classes
2. cd classes/
3. java hello/hello
4. cd ..
5. jar -cvfe hello.jar hello/hello -C classes .
6. java -jar hello.jar
