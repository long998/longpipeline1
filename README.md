# longpipeline1
maven compile the java project
using maven you have to make very clear about the path: (if using ant, you will set full path in pom.xml)
and the resouce code path : githubprojectname/src/main/java/com/javaprojectname/...maybechildfolder/*.java 
and the test code path: githubprojectname/test/java/com/javaprojectname/...maybechildfolder/*.java
so we can see in the pom.xml
  <groupId>com.javaprojectname</groupId>

  <artifactId>githubprojectname</artifactId>
