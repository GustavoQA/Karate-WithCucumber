# Karate-WithCucumber
Proyecto Spotify con reporte de cucumber
-ejecucion por consola bash --
reporte Karate : mvn clean test -Dkarate.env=cert "-Dkarate.options=--tags @SPY"
reporte Cucumber : 
mvn clean verify "-Dcucumber.options=--tags @SPY"
ó
mvn clean test  -Dcucumber.options="--tags @SPY"

