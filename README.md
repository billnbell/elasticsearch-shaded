Shade Elastic v5.2.2 in Maven so that there won't be any conflicts when building other repos.

Install into Maven Repo for usage:

./mvnw install:install-file -Dfile=PATH/elasticsearch-shaded/target/elasticsearch-shaded-5.2.2.jar -DgroupId=com.brightspot -DartifactId=elasticsearch -Dversion=5.2.2 -Dpackaging=jar

