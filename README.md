# Bigram
## Bigram App

A bigram is any two adjacent words in the text disregarding case. A histogram is the count of how many times that particular bigram occurred in the text. The project is created as a maven project. Project build will create an executable jar file. To run this project you can either build using maven or can run the jar afile available in target folder as below:

# Run the jar file
Command to run program:  
```
java -jar bigramutil.jar 
```
This will prompt you to provide an input file. You can type as below. This file is included in the scrpts. You can provide any readable file you want.
```
test.txt 
```
# To Build using Apache maven:
Run the below command from the root folder(you need to have maven in classpath).
```
mvn clean package
```

This will create a folder "/target" and will generate "bigramutil.jar" with all dependencies. run the blow command from target folder.
```
java -jar bigramutil.jar 
```
