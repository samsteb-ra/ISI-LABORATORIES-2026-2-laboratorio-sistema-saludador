# ISI-LABORATORIES-2026-2-laboratorio-sistema-saludador

# Sistema Saludador

Aplicación de escritorio en Java y JavaFX. Pide nombre, edad y momento del día (AM/PM) y genera un saludo personalizado.

## Requisitos

- JDK 17 o superior (recomendado JDK 21) con `JAVA_HOME` configurado.
- No hace falta instalar Maven: el proyecto incluye Maven Wrapper (`mvnw` / `mvnw.cmd`).

## Compilar y ejecutar

Abre una terminal en la carpeta raíz del proyecto (donde está el `pom.xml`).

Windows:

```
.\mvnw.cmd clean javafx:run
```

Linux / macOS:

```
./mvnw clean javafx:run
```

La primera vez descarga Maven y las dependencias, compila y abre la aplicación.

## Funcionamiento

- Campos: nombre, edad (0–120) y selección AM/PM.
- Botón **Solicitar saludo**: muestra "Buenos días" (AM) o "Buenas tardes" (PM) con el nombre y la edad.
- Validaciones: campos vacíos, edad no numérica o fuera de rango.

## Estructura

```
lab-5
├── .mvn/wrapper/maven-wrapper.properties
├── prompts/prompts.txt
├── src/main/java/com/saludador/{App,SaludadorController}.java
├── src/main/resources/com/saludador/{saludador.fxml,styles.css}
├── .gitignore  README.md  Reflexion.txt
└── mvnw  mvnw.cmd  pom.xml
```
