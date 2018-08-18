# spring-boot-angular-multi-project
Project with angular frontend included to the fat jar

* Used frontend-maven-plugin
* Fornt is packaged as a jar file, don't forget to change output folder for "build" script in the package.js:
```
ng build --prod --output-path dist/META-INF/resources
```
