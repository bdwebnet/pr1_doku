# Benutzer Eingabe

## Zahlen oder Text Eingabe - ```Scanner```

### Scanner Importieren

```java 
import java.until.Scanner; 
```
### Scanner Objekt erstellen

```java
Scanner scannerName = new Scanner(System.in);
```

### Auslesen von einer Eingabe

```java

String name = scannerName.nextLine(); //Auslesen von einer Zeichenkette 

```
``` java

int alter = scannerName.nextInt(); //Auslesen von einer Ganzzahl

```
``` java

double groese = scannerName.nextDouble(); //Auslesen von einer Fließkommazahl

```

### Scanner am Ende schließen

``` java
scannerName.close();
```

Weiterführende Links / Quellen:

 - https://docs.oracle.com/javase/7/docs/api/java/util/Scanner.html