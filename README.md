# JTesting
Trabajo Práctico 1 tercera evaluación Entornos de Desarrollo

Para poder llevar a dcabo las pruebas necesitaremos del fichero.jar de JUnit que se puede descargar desde la página oficial de maven. https://mvnrepository.com/artifact/junit/junit/4.8.1

    Git clone:

$ git clone https://github.com/carlosseguraanton/JTesting.git
$ cd JTesting

    Compilamos primeramente la clase Math.java dando la dirección de los jars, recordando la dependencia:

$ javac -cp /home/alumnado-pc10/misjars/junit-4.8.1.jar/libs/*:.  Math.java

    Compilamos el testing:

$ javac -cp /home/alumnado-pc10/misjars/junit-4.8.1.jar/libs/*:.  MathTest.java

    Corremos el test:

$ java -cp /home/alumnado-pc10/misjars/junit-4.8.1.jar/libs/*:. org.junit.runner.JUnitCore  MathTest
