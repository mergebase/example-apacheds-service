# example-apacheds-service

This repository contains a very simple "pom.xml" file that references a single dependency:  

org.apache.directory.server/apacheds-service-2.0.0.AM26.jar

However, this dependency is interesting because it is an uber jar that internally
contains 30+ popular open source libraries.  You can use this repository to test
your favourite SCA tools to see if they are "uber-aware".

