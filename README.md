#### :warning:This project is now part of the EE4J initiative. This repository has been archived as all activities are now happening in the [corresponding Eclipse repository](https://github.com/eclipse-ee4j/common-annotations-api). See [here](https://www.eclipse.org/ee4j/status.php) for the overall EE4J transition status.
 
---

# Java(TM) Common Annotations

The intention of Java(TM) Common Annotations is to develop annotations for common semantic 
concepts in the Java SE and Java EE platforms that apply across a variety of individual 
technologies. It was envisioned that various JSRs would use annotations to enable a declarative
style of programming. It would be especially valuable to have consistency within the Java EE 
component JSRs, but it is also valuable to allow consistency between Java EE and Java SE.

This standalone release of Java(TM) Common Annotations uses a
[Java Platform Module System](http://openjdk.java.net/projects/jigsaw/spec/)
"automatic" module name of `java.annotation`, to match the module name
used in JDK 9.  A future version will include full module metadata.
