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
sh(script:"mvn -f /var/lib/jenkins/workspace/opsMathi_learnDevops_master-2RXKEKXSBX3VCQWUVPLYJNMPZCOAPDMDHDUZA6RKOTWJDRPE5TTQ/docker-springboot/pom.xml clean ")
sh(script:"mvn -f /var/lib/jenkins/workspace/opsMathi_learnDevops_master-2RXKEKXSBX3VCQWUVPLYJNMPZCOAPDMDHDUZA6RKOTWJDRPE5TTQ/docker-springboot/pom.xml install ")
sh (script:"ls -ltr")
sh (script:"cd /var/lib/jenkins/workspace/opsMathi_learnDevops_master-2RXKEKXSBX3VCQWUVPLYJNMPZCOAPDMDHDUZA6RKOTWJDRPE5TTQ/docker-springboot/target sh ls -ltr")
sh (script:"ls -ltr")
}