# JSR-382 Examples - JavaConfig

## Projects
Project         | description
--------------- | -------------
[SimpleDependencyInjection](https://github.com/SouJava-Rio/soujava-rio-labs/tree/master/JSR-382-JavaConfig/SimpleDependencyInjection/javaconfig) | Simple Dependency Injection
[SimpleProgrammatic](https://github.com/SouJava-Rio/soujava-rio-labs/tree/master/JSR-382-JavaConfig/SimpleProgrammatic/javaconfig) | Simple Programmatic 

## informative links

* Configuration API 1.0 - JSR 382-JCP [Configuration API 1.0 - JSR 382](https://jcp.org/en/jsr/detail?id=382)
* Apache/geronimo-config [apache/geronimo-config]( https://github.com/apache/geronimo-config/tree/ConfigJSR) - Some of the implementations -RI not defined
* Eclipse ConfigJSR [Eclipse ConfigJSR](https://github.com/eclipse/ConfigJSR)


# - Attention

Json-B is only for displaying a better output.

To execute the project the user must have the builds locally of JavaConfig and Geronimo-config, in addition to calling Weld main (org.jboss.weld.environment.se.StartMain)

for this you just have to fork the https://github.com/eclipse/ConfigJSR and the https://github.com/apache/geronimo-config/tree/ConfigJSR
and run on both the command:
```bash
mvn clean install -DskipTests
```
