# JenkinsDetails

############ Global Tool Configuration ###############

1. Add JDK

E:\OpenJDk11-New

2. Add Maven 

E:\Maven-3.6.3\apache-maven-3.6.3

###########  pom.xml dependencies ############ 

find in pom.xml file <Plugin Section>


########### Mvn Command-Execute Windows Batch Command ################
NOTE: Change the below values as discussed in Video with your details

mvn clean deploy -DmuleDeploy -DskipTests -Dmule.version=4.3.0 -Danypoint.username=<YOUR Cloudhub UserName> -Danypoint.password= <YOUR CloudhubPassword> -Denv=DEV -Dappname=testcicdlakshmi-mar23 -Dbusiness=LakshmiMule -DvCore=Micro -Dworkers=1 
