A [giter8] based [Akka] 2.0 tutorial project using [Java] and [Maven].

Now you have created the tutorial as a local project on your computer.

To run and test it use [Maven]:

	$ cd akka-pi-calculation-tutorial
	$ mvn compile exec:java
	[INFO] Scanning for projects...
	[INFO]                                                                         
	[INFO] ------------------------------------------------------------------------
	[INFO] Building Akka Pi Calculation Tutorial 0.1-SNAPSHOT
	[INFO] ------------------------------------------------------------------------
	[INFO] 
	[INFO] --- maven-resources-plugin:2.5:resources (default-resources) @ pi-calculation ---
	[debug] execute contextualize
	[INFO] skip non existing resourceDirectory /Users/theuser/code/akka-pi-calculation-tutorial/src/main/resources
	[INFO] 
	[INFO] --- maven-compiler-plugin:2.3.2:compile (default-compile) @ pi-calculation ---
	[WARNING] File encoding has not been set, using platform encoding MacRoman, i.e. build is platform dependent!
	[INFO] Compiling 1 source file to /Users/theuser/code/akka-pi-calculation-tutorial/target/classes
	[INFO] 
	[INFO] >>> exec-maven-plugin:1.2.1:java (default-cli) @ pi-calculation >>>
	[INFO] 
	[INFO] <<< exec-maven-plugin:1.2.1:java (default-cli) @ pi-calculation <<<
	[INFO] 
	[INFO] --- exec-maven-plugin:1.2.1:java (default-cli) @ pi-calculation ---
	    Pi approximation:    3.1415926435897883
	    Calculation time:    565 milliseconds
	[INFO] ------------------------------------------------------------------------
	[INFO] BUILD SUCCESS
	[INFO] ------------------------------------------------------------------------
	[INFO] Total time: 3.027s
	[INFO] Finished at: Thu Mar 08 21:03:48 CET 2012
	[INFO] Final Memory: 9M/81M
	[INFO] ------------------------------------------------------------------------


[giter8]: https://github.com/n8han/giter8
[Akka]: http://akka.io
[Java]: http://java.com/
[Maven]: http://maven.apache.org/
