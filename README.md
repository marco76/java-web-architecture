# java-web-architecture

This project contains the basic structure for a Java EE - Angular / Vue.js / React.js framework.

The frontend module has to be adapted to you javascript framework.
The production deliverable has to be stored in the /dist directory to be packaged.

If you use Spring you can adapt the backend module.

## Achitecture goals
- Only one war (or jar) file  that contains Java classes and frontend deliver.
- 1 instruction to go: `mvn package`

# Where is my war
- mvn package creates a directory in the parent directory. Change it in the parent pom.xml, currently [PROJECT]/deploy_this/READY_TO_DEPLOY.war

## To be adapted for your project
- Spring: change the backend pom.xml
- Angular / Vue / React: in the fronted.xml, `build js` section complete with the instructions that build your prod package
- jar in place of war: change the pom config
- Configuration: change the name of your war and the target directory in the parent pom.xml

## To be done
...
