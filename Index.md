### What is java
An object oriented programming language mostly used for creating desktop and web applications

### How to install java
#### fedora 
`sudo dnf install java-devel`
#### windows 
get the latest release of opendjdk form [Windows](https://www.microsoft.com/openjdk)

### Using java to build applications
* java is a good platform to build your applications 
* It can be used to make command line applications or graphical applications using its vast majority of it's libraries.
* The moat commonly used packaging type for java applications is jar type and most java applications are built and managed by *[[Maven]]*.

### Preferred IDE for java 

#### Eclipse 
* eclipse is widely used by java developers to build java applications.
* you can install the eclipse IDE from flatpak or directly from [eclipse org](https://www.eclipse.org/downloads/packages/) (Preferred).

### Creating your First java program (No IDE required)

* All java programs are written in `.java` extension
* A java program should be present inside a class.
* The main method is the entry point for any java application.

The below code is an perfect example of an simple java program

```
public class HelloWorld {
	public static void main(String[] args) {
		System.out.println('Hello World');
	}
}
```

* The above code need to be compiled and executed
* This code snippet can be placed in `HelloWorld.java`  file 
* Once placed the below command can be used to compile the java progrm

```
javac HelloWorld.java
```

* This would have compiled the above java program Now to run the program we can use the following command.

```
java HelloWorld
```
