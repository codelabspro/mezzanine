# Mezzanine

## Getting Started

http://www.ninjaframework.org/documentation/getting_started/installing_ninja.html


## Steps

mvn archetype:generate -DarchetypeGroupId=org.ninjaframework -DarchetypeArtifactId=ninja-servlet-archetype-simple

After finishing the generation change into your project directory and execute:

cd MY_INSTALLED_PROJECT
mvn clean install     // to generate the compiled classes the first time
mvn ninja:run         // to start Ninja's SuperDevMode


This starts Ninja’s SuperDevMode. Simply open http://localhost:8080 in your browser.



### Emacs navigation

http://www.thegeekstuff.com/2010/07/emacs-editor-navigation/