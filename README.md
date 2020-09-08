# ReportISW2-ModuloSWTesting

Di seguito vengono riportate i link delle classi di test realizzate :

------------------PROGETTO BOOKKEEPER--------------------------------------------------------------------------------------------------------


- BookkeeperAdmin : https://github.com/CecBazinga/bookkeeper/tree/master/bookkeeper-server/src/test/java/org/apache/bookkeeper/client

- ZKUtils : https://github.com/CecBazinga/bookkeeper/tree/master/bookkeeper-server/src/test/java/org/apache/bookkeeper/util


------------------PROGETTO OPENJPA--------------------------------------------------------------------------------------------------------

- QualifiedDBIdentifier : https://github.com/CecBazinga/openJpa/tree/master/openjpa-jdbc/src/test/java/org/apache/openjpa/jdbc/identifier

- ClassUtil : https://github.com/CecBazinga/openJpa/tree/master/openjpa-lib/src/test/java/org/apache/openjpa/lib/util


Di seguito le istruzioni per compilare ed eseguire i test dal terminale dell ide utilizzata dopo aver fatto clone della repository :

1) mvn clean install 

2) mvn clean org.jacoco:jacoco-maven-plugin:prepare-agent verify  (per statement e branch coverage utilizzando il plugin jacoco)

3) mvn org.pitest:pitest-maven:mutationCoverage surefire:test  (per mutation coverage utilizzando il plugin pit)
