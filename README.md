This is my Readme file where i will update my work. 
###Date: 23/06/2025

Topic: git and gitbash.

Introduction to GIT: Git is distributed version control system that tracks changes in source code during software development. It helps to collaborate,manage code history and different versions. Created by Linus Torvalds in 2005.

What is Git Bash? it is command-line interface(CLI) that aloow user to interact with Git on windows.

Before git SVN was there which doesn' t work remotely but git provide this.

Local Repository: it is the Git repository stored on our local computer.It includes working directory,staging area and contain .git folder.

Remote Repository: it is a version of our project hosted online usually on platforms like github, gitlab.Used for collaboration, backup, and deployment. You can push your code to remote or pull from it.

GIT Commands echo "#This is my bridgelab" >> README.md -> this is for creating the readme file

git init ->this for initializing the foler into local repository

git add . ->through untracked files to tracked files in local repository

git commit -m "First commit" -> commit all the changes we have done

git remote add origin https://github.com/yourname/repo.git -> connect local with remote repository.

git push -u origin main -> push all the work from local machines to remote repository

nano README.md is used to edit the readme file ->ctrl+X ->yes->enter touch filename: is used to create empty file. git branch branch_name: to used to create different branch

cat README.md : to check content of readme file

###Date:24/06/2025 JAVA PROGRAMMING: History

Java’s journey began with Green team, a group of Sun Microsystems led by JAMES GOSLING(Father of Java).

its principle include simplicity,robustness,portability,platform independence ,security ,high performance ,multipthreading,object orientation ,interpretation and dynamism laid the foundation for its development.

Current version of Java is Java22.

JDK

JDK=JRE+development tools

Java Deveopment Kit is a cross-platformed software developed enviornment that offers a collection of tools and libraries necessory for deveoping Java based software application.

Tools like compilers, JavaDoc, Java Debugger

It is a core package used in java.along with JVM(Java VIrtual Machine)+ JRE(Java Runtime Enviornmet)

JVM:

Working of java Program()

Java virtual Machine is an abstarct machine that enables your computer to run Java program.

When you run the Java program,Java compiler first compiles your java code to bytecode.Then, the JVM translate bytecode into native machine code(Set of instruction that a computers CPU executes directly.)

Source Code → Java Compiler (javac) → Bytecode → JVM → Machine Code

JRE:

Java Runtime Enviornment is a software package that provides Java class libraries , JVM and other comoponents that are required to run java applications. compiler it checks symmetic and spelling error.

How java is platform independent.

Structure of a Program
//Java program to print Hello World.

public class Welcome{

public static void main(String []args){

System.out.println(”Hello World”);

}

}

compile: javac [Welcome.java] → compile code and convert to .class( bytecode) file → then to JVM under JRE convert to machine code

Source Code → Java Compiler (javac) → Bytecode(.class) → JVM → Machine Code(0,1)

if we want to develop java program we use JDK.

if we want to run program we need JRE.

Comments:
The text within the asterisk (/* */) or double slash (//) is treated as comments and ignored by the computer.

// - Single Line Comment

/ / - Multiple Line Comment
