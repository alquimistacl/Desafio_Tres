# Desaf�o 3: Complemento valores UF #


### Descripci�n de la implementaci�n ###

La estructura utilizada es la siguiente:

src/main/java
* **com.previred.desafio.tres**
* **com.previred.desafio.tres.dto**
* **com.previred.desafio.tres.service**


src/test/java
* **com.previred.desafio.tres.service**


Donde la base, contiene la clase GenerarListaApplication, que permite ejecutar la aplicaci�n.
En dto, se encuentran los objetos que permite generar el archivo de salida de la aplicaci�n.
En service, se encuentra la implementaci�n de negocio asociada a la generaci�n del archivo json.


### Tecnolog�a y librer�as utilizadas ###

Para esta implementaci�n, se utiliz�: 
* java 8
* maven 3.6.3
* gson 2.8.6
* junit 4.13
* mockito 1.10.19



### Detalles de compilaci�n y ejecuci�n ###

Para compilar esta aplicaci�n, es necesario ejecutar en el directorio ra�z de la misma, la
siguiente instrucci�n:

```mvn clean compile package```

Al ejecutar lo anterior, se generar� el archivo **Desafio_Tres-0.0.1-SNAPSHOT.jar**

Una vez compilado, se pueden ejecutar las pruebas con la siguiente instrucci�n:

```mvn test -Dtest=ComplementoValoresServiceTests```


Por �ltimo, para ejecutar la aplicaci�n, se debe ejecutar la siguiente instrucci�n:

```java -jar target\Desafio_Tres-0.0.1-SNAPSHOT.jar```

