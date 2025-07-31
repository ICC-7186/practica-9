# Práctica 9: Archivos de Texto y CSV. 📌

Nombre: 

NumCuenta: 

En esta práctica se trabajará con archivos de texto simples y archivos csv.

## Autores 😊
* **Salvador López Mendoza** - *Titular* - [Correo](slm@ciencias.unam.mx)
* **Gerardo Emiliano Figueroa Sandoval** - *Teoría* - [Emiliano-Fs](https://github.com/Emiliano-FS)
* **Ramsés Antonio López Soto** - *Laboratorio* - [ramseslopez](https://github.com/ramseslopez)
  
## Objetivos 🚀

- Entender que hay más tipos de persisitencia además de la serialización.
- Comprender un uso simple de los archivos de texto y csv.

### Pre-requisitos 📋

- Sistema Operativo Linux (Ubuntu, Debian, Fedora, etc.)
- Git versión 2.43.0
- Java versión 21.0.7
- Perfil de GitHub

### Instalación 🔧

- Git

Para instalar la versión más reciente de Git:

```bash
sudo apt-get install git

```
Una vez finaliado, verifica la versión instalada.

```bash
git -v
```

- Java
  
Instala Java con el siguiente comando:

```bash
sudo apt-get install openjdk-21-jre
```

Al finalizar, verifica la versión instalada.

```bash
java --version
```
y también del compilador:

```bash
javac --version
``` 

## Recursos 📖

Puedes encontrar más información de los recursos a utilizar en:

- [Archivos de Texto](https://puntocomnoesunlenguaje.blogspot.com/2013/05/ficheros-de-texto-en-java.html)
- [OpenCSV](https://opencsv.sourceforge.net/)
- [Uso de OpenCSV](https://vaadin-com.translate.goog/blog/read-and-display-a-csv-file-in-java?_x_tr_sl=en&_x_tr_tl=es&_x_tr_hl=es&_x_tr_pto=tc)

## Ejercicios ⌨️

Lee con mucha atención las instrucciones:

### Carta

Haciendo uso de los archivos de texto deberás de creear una clase `Carta` que se encarge de crear cartas con el siguiene formato:

```
Fecha: // fecha actual
De: // remitente
Para: // destinatario

// cuerpo del mensaje

P.D: // mensaje extra

```
El programa debe ser capaz de escribir línea por línea y solo debe de terminar si se coloca la palabra `"FIN"`. Puedes usar excepciones adicionales si lo crees necesario.


### Calificaciones

Para este ejercicio debes de crear un proyecto similar a los que hemos estdo usando en prácticas anteriores si deseas utilizar la libreria OpenCSV. Debes agregar lo siguiente en el archivo `pom.xml`:

```
<dependency>
  <groupId>com.opencsv</groupId>
  <artifactId>opencsv</artifactId>
  <version>5.6</version>
</dependency>
```

También puedes usar la clase `StringBuilder` si es más sencillo para ti.

Por otro lado, este ejercicio consiste en realizar una pequeña lista de 15 estudiantes para poder registrar las calificaciones de 5 materias de primer semestre, así como de su promedio total.

Debes de implentar un programa que genere un archivo `.csv` con el siguiente formato:

```
Num,Cuenta,Nombre,Algebra,ICC,Mate,ED,Ingles,Promedio
1, // datos
2, // datos
.
.
.
15, // datos
```

El programa debe ser capaz de crear el archivo, escribir en él y leerlo sin ningún incoveniente.


## Instrucciones

* La práctica se entrega de forma individual.
* Debes de clonar el este repositorio con el comando `git clone`, agregar tu nombre en la parte de `Nombre: ` y seguido de tu número de cuenta en `NumCuenta: `.
* El código debe ser legible y el nombre varialbes y métodos debe ser adecuado. Debes de seguir las reglas correspondientes.
* Sube la solución de la práctica antes de las 23:59 del día de mañana con los comandos `git add`, `git commit` y `git push`.
* Una vez en el repositorio, debes de entregar en el Classroom la liga **HTTPS** que direcciona a tu repositorio.
* La calificación se determinará dependiendo del número de pruebas que pasen.
* Ningún tipo de copia y/o plagio será tolerado.

## Licencia 📄

Este proyecto está bajo la Licencia MIT - mira el archivo [LICENSE.md](LICENSE.md) para más detalles.
