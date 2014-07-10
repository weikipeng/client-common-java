Java library for Kontalk clients
================================

This library holds the common source code used by Kontalk clients.

Note that this is not a complete client implementation, but a few classes shared
by all the clients.

Build requirements:

* [Smack](http://www.igniterealtime.org/projects/smack/) 4.0.0
* [kXML](http://www.kxml.org/)


Building
========

Building is automated via Gradle, but first you have to choose a build file:

~~~
./setup [asmack|smack]
~~~

This will copy the right `build.gradle` file. Then run Gradle as usual:

~~~
./gradlew assemble
~~~
