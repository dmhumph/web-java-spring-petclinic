# web-java-spring-petclinic

Spring PetClinic Sample Application

# Developer Workspace
[![Contribute](http://codeready-codeready.apps.ocpcloudsolutions.com/factory/resources/factory-contribute.svg)](http://codeready-codeready.apps.ocpcloudsolutions.com/f?url=https://github.com/dmhumph/web-java-spring-petclinic)

This Eclipse Che Factory can also be invoked with any host:
{hostURL}/f?url=https://github.com/che-samples/web-java-spring-petclinic
It will read the `.factory.json` from the repository to instanciate the developer workspace.

Example:
http://che.openshift.io/f?url=https://github.com/che-samples/web-java-spring-petclinic


# How to run

| #       | Description           | Command  |
| :------------- |:-------------| :-----|
| 1      | Build and copy war | `mvn -f ${current.project.path} clean install && cp ${current.project.path}/target/*.war $TOMCAT_HOME/webapps/ROOT.war` |
| 2      | Run Tomcat      |   `$TOMCAT_HOME/bin/catalina.sh run` |
| 3 | Stop Tomcat      |    `$TOMCAT_HOME/bin/catalina.sh stop` |
| 4 | Tomcat Debug Mode      |    `$TOMCAT_HOME/bin/catalina.sh jpda run` |

