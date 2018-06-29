#!/bin/groovy
node{
def name="muhilmathi"
print name
sh (script:"ls -ltr")
checkout scm 
sh (script:"pwd")
sh (script:"ls -ltr")
sh (script:"cd docker-springboot")
sh (script:"ls -ltr")
sh(script:"mvn -f /docker-springboot/pom.xml install")
sh (script:"ls -ltr")
sh (script:"cd target")
sh (script:"ls -ltr")
}