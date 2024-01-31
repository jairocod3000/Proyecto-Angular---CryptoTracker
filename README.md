# Proyecto-Angular---CryptoTracker
Rastreador de Criptomonedas con Angular

Aspectos importantes sobre el proyecto
Al darle al añadir una moneda, si esta no aparece que me suele ocurrir puede ser por 2 motivos:
CORS: Bloqueado por la página por límite de peticiones
Al darle a agregar manedas muy rápido, alguna de ellas tardará en aparecer lo que tarde la API en enviar la información
Por el momento, los datos se actualizan cada 5 minutos para evitar problemas con la API. Se podrá cambiar en cualquier momento.
En el detalle de la moneda, a veces tarda un poco el historial de precios (depende de la moneda, ya que si lleva mucho tiempo existiendo, mas datos habrá)
Servidor de desarrollo
Ejecute ng servepara un servidor de desarrollo. Navegar a http://localhost:4200/. La aplicación se recargará automáticamente si cambia alguno de los archivos fuente.

Andamio de código
Ejecute ng generate component component-namepara generar un nuevo componente. También puedes usar ng generate directive|pipe|service|class|guard|interface|enum|module.

Construir
Ejecute ng buildpara construir el proyecto. Los artefactos de compilación se almacenarán en el dist/directorio.

Ejecución de pruebas unitarias
Ejecute ng testpara ejecutar las pruebas unitarias a través de Karma .

Ejecución de pruebas de un extremo a otro
Ejecute ng e2epara ejecutar las pruebas de un extremo a otro a través de una plataforma de su elección. Para utilizar este comando, primero debe agregar un paquete que implemente capacidades de prueba de un extremo a otro.

Más ayuda
Para obtener más ayuda sobre el uso de Angular CLI ng helpo consulte la página Descripción general y referencia de comandos de Angular CLI .
