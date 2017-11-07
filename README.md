# Head First Design Patterns (2014 update)

# How to use this repo

I (Phill Conrad) have forked this repo from Beth Robson's version (see below) and added

* a build.xml file
* publishing the javadoc
* some instructions for running

# To find the main programs you can run

At the Unix command line in the root of the repo, do:

```
grep -r "public static void main" .
```

Example output (truncated)

```
pconrad$ grep -r "public static void main" .
grep: ./.#build.xml: No such file or directory
./src/headfirst/designpatterns/adapter/ducks/DuckTestDrive.java:	public static void main(String[] args) {
./src/headfirst/designpatterns/adapter/ducks/TurkeyTestDrive.java:	public static void main(String[] args) {
./src/headfirst/designpatterns/adapter/iterenum/EI.java:	public static void main (String args[]) {
./src/headfirst/designpatterns/adapter/iterenum/EnumerationIteratorTestDrive.java:	public static void main (String args[]) {
./src/hea
...
```

To run any of those mains, use `java -cp build full.package.name.to.class`

For example:

```
java -cp build headfirst.designpatterns.adapter.ducks.DuckTestDrive
```

# ORIGINAL README.md text

The text below comes from the original repo by Beth Robson, which is here:

<https://github.com/bethrobson/Head-First-Design-Patterns>

I have recently updated all the code for Head First Design Patterns to be compatible
with Java 8. This new code accompanies an update for the book, released in July, 2014.

Download the code and compile and run from the command line, or load the code into 
project in Eclipse (Kepler, with the Java 8 beta patch).

https://wiki.eclipse.org/JDT/Eclipse_Java_8_Support_For_Kepler


Other links for the book are available on the book page at <a href="http://wickedlysmart.com/head-first-design-patterns/">wickedlysmart.com</a>.

