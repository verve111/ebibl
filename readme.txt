Use 'repository' branch

Add jar to the local repo:
mvn install:install-file -DgroupId=com.sun.media -DartifactId=jai-codec -Dversion=1.1.3 -Dfile=c:\liferay-portal-6.1.1-ce-ga2\tomcat-7.0.27\webapps\ROOT\WEB-INF\lib\jai_codec.jar -Dpackaging=jar -DgeneratePom=true -DlocalRepositoryPath=.  -DcreateChecksum=true