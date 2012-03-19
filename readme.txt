This is just a collection maven shortcut batch files. I am trying to create shortcuts for mostly used maven commands.
Please feel free to contribute or raise new requests in issues section of github.com/nutpan.
This project is open source software available under the terms of the Apache 2.0 license.

Short Cuts

mvnci - mvn clean install
mvnciwt - mvn clean install with out tests
mvnt - mvn test
mvnt %1 - mvn test on single test file (eg : mvnt MyTest)
mvnee - mvn eclipse:eclipse

For Windows, copy all the batch files in to a folder and add the folder in classpath
For linux/unix, you can copy the sh files into bin folder and give executable permission using commands in makeItExec.sh 

All the shortcuts will echo the actual mvn command before execute.

For more info visit : http://blog.nutpan.com/2012/03/maven-shortcuts.html