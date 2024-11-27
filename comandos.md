### Comandos Usados 
Inicializar proyecto maeven, se debe usar CMD, no sirve en powershell
```
mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.5 -DinteractiveMode=false
```
Compila el archivo y realiza el test unitario
```
mvn compile
```
Crear el archivo .jar o war para paginas web
```
mvn package
```
Realiza la instalación del programa ejecuta el compile y package
```
mvn install 
```
eliminar el archivo .jar o .war a l finalizar la intalación
```
mvn clean install 
```
Realizar instalación sin la prueba unitaria
```
mvn clean install -DskipTest=true
```
