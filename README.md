# spinnaker-jar-downloader

the test.groovy coode needs the jars as follows in the build path.

commons-logging-1.2.jar

commons-cli-1.3.1.jar

spring-web-4.3.6.RELEASE.jar

spring-core-4.3.6.RELEASE.jar

clouddriver-cf-0.1.0-SNAPSHOT.jar



to run:
groovy -cp ./commons-cli-1.3.1.jar:./clouddriver-cf-0.1.0-SNAPSHOT.jar:./commons-codec-1.10.jar:./commons-logging-1.2.jar:./spring-core-4.3.6.RELEASE.jar:./spring-web-4.3.6.RELEASE.jar test.groovy

