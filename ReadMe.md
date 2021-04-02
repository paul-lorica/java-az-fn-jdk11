#Generated using maven
`mvn archetype:generate "-DarchetypeGroupId=com.microsoft.azure" "-DarchetypeArtifactId=azure-functions-archetype" "-DjavaVersion=11" "-Ddocker"`


#To run in Docker:
`docker build -t java-az-fn:1.0 .`
`docker run -p 8080:80 -it java-az-fn:1.0`