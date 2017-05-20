# JTesting
Trabajo Práctico 1 tercera evaluación Entornos de Desarrollo

Para poder llevar a dcabo las pruebas necesitaremos del fichero.jar de JUnit que se puede descargar desde la página oficial de maven. https://mvnrepository.com/artifact/junit/junit/4.8.1

Para ejecutar el test necesitamos seguir las siguientes instrucciones:

1. Realizamos una copia local del repositorio.

   `$ git clone https://github.com/carlosseguraanton/JTesting.git`
   
2. Cambiamos nuestra ubicación a la carpeta del proyecto.

    `$ cd JTesting`

3. Compilamos primeramente la clase Math.java dando la dirección de los jars, recordando la dependencia:

    `$ javac -cp /home/alumnado-pc10/misjars/junit-4.8.1.jar/libs/*:.  Math.java`

4. Compilamos el testing:

    `$ javac -cp /home/alumnado-pc10/misjars/junit-4.8.1.jar/libs/*:.  MathTest.java`

5. Ejecutamos el test:

    `$ java -cp /home/alumnado-pc10/misjars/junit-4.8.1.jar/libs/*:. org.junit.runner.JUnitCore  MathTest`
