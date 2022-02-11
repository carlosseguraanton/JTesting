# JTesting
Trabajo Práctico 1
Tercera evaluación
Entornos de Desarrollo

Para poder llevar a cabo las pruebas unitarias necesitaremos usar el fichero.jar de JUnit que podemos descargar desde el sitio web oficial de maven:
https://mvnrepository.com/artifact/junit/junit/4.8.1

Git clone:

    $ git clone https://github.com/carlosseguraanton/JTesting.git
    
Cd JTesting:

    $ cd JTesting
    
 Compilamos primeramente la clase Math.java dando la dirección de los jars, recordando la dependencia:

    $ javac -cp /home/alumnado-pc10/misjars/junit-4.8.1.jar/libs/*:.  Math.java

Compilamos el testing:
    
    $ javac -cp /home/alumnado-pc10/misjars/junit-4.8.1.jar/libs/*:.  MathTest.java

Corremos el test:
    
    $ java -cp /home/alumnado-pc10/misjars/junit-4.8.1.jar/libs/*:. org.junit.runner.JUnitCore  MathTest

