Detalles generales de la implementación:
Las tecnologías utilizadas para el desarrollo de las pruebas automatizadas son las siguientes:

Karate DSL: Para la implementación de las APIs.
Appium para la automatización móvil requiere tener previamente instalado un emulador y servidor Appium para ejecutar la prueba.

Serenity BDD: es una biblioteca de código abierto que tiene como objetivo hacer realidad la idea de documentación viva. Ayuda a escribir pruebas de regresión y aceptación automatizadas más limpias y fáciles de mantener. Serenity también utiliza los resultados de las pruebas para producir informes ilustrados y narrativos que documentan y describen qué hace la aplicación y cómo funciona.

Cucumber: es una herramienta que respalda el desarrollo guiado por comportamiento (BDD). Cucumber lee especificaciones ejecutables escritas en texto plano (Gherkin) y valida que el software haga lo que las especificaciones dicen. Las especificaciones consisten en múltiples escenarios de prueba.

ScreenPlay es un patrón de diseño para la automatización de calidad, y su comportamiento gira en torno a la metodología de Desarrollo Guiado por Comportamiento (BDD).

Gradle: es una herramienta de compilación de código abierto con un enfoque en flexibilidad y rendimiento.

Se requiere Java versión 8 o superior.

Para ejecutar las pruebas, utiliza el siguiente comando:
./gradlew clean test
