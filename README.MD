# MT translation plugin

 MT Manager official translation plug-in source code

 ## project instruction

 The project is developed using Android Studio. On the basis of the default file structure, redundant files and configurations are deleted, only the relevant content required for plug-in development is retained, and the one-click packaging function is integrated.

 The plug-in source code files are in the following four paths:

 -plugin/src/main/resources/manifest.json
 -plugin/src/main/java
 -plugin/src/main/assets
 -plugin/libs

 If you need to re-develop your own module, you can clear the contents of the files in the above 4 paths.

 ## One-click packaging

 Select BuildPlugin at the top of Android Studio and click Run, or execute ./gradlew plugin:buildPlugin in the root directory of the project to automatically package the file and save it to plugin/build/outputs/mtp/plugin.mtp
