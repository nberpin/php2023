# Curso PHP: Introducción al PHP

##  Introducción

 En esta presentación, profundizaremos en el mundo de PHP, un lenguaje de programación ampliamente utilizado en el desarrollo web. Analizaremos su historia, estructura y consideraciones clave sobre sus ventajas y desventajas.

##  Origen de PHP

PHP, acrónimo de "Hypertext Preprocessor", fue creado en 1994 por Rasmus Lerdorf como un proyecto personal para rastrear visitas a su sitio web. Desde entonces, ha evolucionado significativamente y se ha convertido en uno de los lenguajes de programación más populares para el desarrollo web.

##  PHP: Lenguaje del Lado del Servidor y su Naturaleza

Para comprender mejor PHP y su papel en el desarrollo web, es esencial abordar su naturaleza como un lenguaje del lado del servidor, entender si se considera compilado o interpretado y conocer los servidores que pueden interpretarlo.

### PHP como Lenguaje del Lado del Servidor

PHP es un lenguaje del lado del servidor, lo que significa que su código se ejecuta en el servidor web antes de que el resultado se envíe al navegador del usuario. Esto tiene varias implicaciones clave:

- El cliente (navegador del usuario) solo recibe el resultado final (HTML, CSS, JavaScript, etc.), no el código fuente de PHP.
- Permite generar contenido dinámico y personalizado en función de las solicitudes de los usuarios.
- PHP puede interactuar con bases de datos, gestionar sesiones de usuario y realizar otras tareas del lado del servidor.

### ¿PHP es Compilado o Interpretado?

PHP se considera un lenguaje interpretado. Esto significa que el código fuente de PHP se ejecuta línea por línea en tiempo de ejecución, en lugar de ser compilado en un programa ejecutable antes de la ejecución. Algunos detalles importantes sobre la interpretación de PHP incluyen:

- El código fuente de PHP se procesa en el servidor cada vez que se realiza una solicitud, lo que permite la flexibilidad de modificar el código sin requerir una compilación previa.
- Los archivos PHP generalmente tienen la extensión ".php" y contienen mezclas de código PHP y HTML, lo que facilita la generación dinámica de contenido web.

### Servidores que Pueden Interpretar PHP

PHP es compatible con varios servidores web populares, lo que lo convierte en una opción versátil para el desarrollo web. Algunos de los servidores web más conocidos que pueden interpretar PHP incluyen:

- **Apache:** Apache es uno de los servidores web más utilizados y es compatible con PHP a través de módulos como mod_php.
- **Nginx:** Nginx puede interpretar PHP utilizando el módulo PHP-FPM (FastCGI Process Manager) para manejar solicitudes PHP.
- **LiteSpeed:** Este servidor web de alto rendimiento es compatible con PHP y es conocido por su capacidad para gestionar aplicaciones web de manera eficiente.
- **IIS (Internet Information Services):** Si utilizas Windows Server, puedes utilizar IIS para alojar aplicaciones PHP.

**Nota:** Además de estos servidores web, existen soluciones de servidor web embebidas como PHP's built-in web server, que es útil para el desarrollo y pruebas locales.

##  Ventajas de PHP

 PHP ofrece una serie de ventajas notables en el desarrollo web. Estas ventajas incluyen:

- **Lenguaje del lado del servidor:** PHP se ejecuta en el servidor, lo que permite generar contenido dinámico y personalizado antes de que llegue al navegador del usuario.

- **Amplia compatibilidad:** PHP es compatible con una amplia variedad de sistemas operativos y servidores web, lo que lo hace altamente versátil.

- **Comunidad activa:** PHP cuenta con una comunidad de desarrolladores activa y una amplia base de usuarios, lo que facilita el acceso a recursos y soporte.

- **Bibliotecas y frameworks:** PHP ofrece numerosas bibliotecas y frameworks como Laravel, Symfony y CodeIgniter, que aceleran el desarrollo web.

- **Integración con bases de datos:** PHP se integra fácilmente con bases de datos populares como MySQL, PostgreSQL y MongoDB.



## Ventajas de PHP

**Narrador:** PHP ofrece una serie de ventajas notables en el desarrollo web. Estas ventajas incluyen:

- **Lenguaje del lado del servidor:** PHP se ejecuta en el servidor, lo que permite generar contenido dinámico y personalizado antes de que llegue al navegador del usuario.

- **Amplia compatibilidad:** PHP es compatible con una amplia variedad de sistemas operativos y servidores web, lo que lo hace altamente versátil.

- **Comunidad activa:** PHP cuenta con una comunidad de desarrolladores activa y una amplia base de usuarios, lo que facilita el acceso a recursos y soporte.

- **Bibliotecas y frameworks:** PHP ofrece numerosas bibliotecas y frameworks como Laravel, Symfony y CodeIgniter, que aceleran el desarrollo web.

- **Integración con bases de datos:** PHP se integra fácilmente con bases de datos populares como MySQL, PostgreSQL y MongoDB.

## Desventajas de PHP

 Sin embargo, no podemos pasar por alto las desventajas de PHP:

- **Rendimiento:** PHP puede tener problemas de rendimiento en comparación con lenguajes altamente compilados como C++.

- **Seguridad:** La seguridad es una preocupación clave, ya que PHP puede ser vulnerable a ataques si no se siguen buenas prácticas de seguridad.

- **Mantenibilidad:** A medida que los proyectos crecen, PHP puede volverse más difícil de mantener debido a la falta de estructura en algunos casos.

- **Inconsistencias en la sintaxis:** PHP tiene algunas inconsistencias en su sintaxis que pueden dificultar la comprensión y el mantenimiento del código.

## Casos de Uso de PHP

 Para comprender mejor la aplicación práctica de PHP, examinemos algunos ejemplos notables de sitios web y aplicaciones que lo utilizan:

- **WordPress:** El popular sistema de gestión de contenido (CMS) WordPress está construido en PHP y es utilizado por millones de sitios web en todo el mundo.

- **Facebook (etapas iniciales):** Facebook se desarrolló en PHP en sus etapas iniciales antes de migrar a otros lenguajes.

- **Joomla:** Otro CMS conocido, Joomla, se basa en PHP y es ampliamente utilizado para crear sitios web y aplicaciones.

##  Ejemplos de Código PHP

A continuación, exploraremos algunos ejemplos de código PHP para comprender su sintaxis básica y su capacidad para generar contenido dinámico en el lado del servidor.


```
<?php
  $nombre = "Juan";
  echo "Hola, $nombre";
?>
```

##  Seguridad en PHP
La seguridad es una prioridad fundamental en el desarrollo web. Algunos aspectos importantes de la seguridad en PHP incluyen:

Validación de datos: Validar y filtrar los datos de entrada es esencial para prevenir ataques como SQL Injection y XSS.

Uso de Frameworks: Utilizar frameworks como Laravel o Symfony puede ayudar a implementar medidas de seguridad robustas.

Actualizaciones regulares: Mantener PHP y sus componentes actualizados es crucial para proteger contra vulnerabilidades conocidas.

## Futuro de PHP

¿Qué nos depara el futuro de PHP? A medida que las tecnologías web evolucionan, PHP continúa siendo relevante en el panorama actual. La introducción de PHP 7 y posteriores ha mejorado significativamente el rendimiento y la seguridad.

## Ofertas de trabajo en PHP
Desde hace años siempre leo y escucho que nuevos lenguajes sustituirán el PHP sin embargo, varios de los mejores programadores que conozco siguen trabajando principalmente en PHP y varios de los proyectos con los que he trabajado se basaban en PHP o en algunas de sus librerías. Busca ofertas de trabajo, encuentra estadísticas y entrega un pequeño resumen del nivel de uso del PHP en proyectos actuales. 

# Primera Clase: Sintaxis básica y funciones

## Entorno de desarrollo y ejecución
Para estas primeras clases utilizaremos el Visual Estudio Code en Windows. 
Creen una carpeta el directorio htdocs de Apache con el nombre "cursophp1" o similar.
Vamos a instalar las siguientes extendiones para poder trabajar más cómodamente:
**LiveServer** de Ritwick Dey
**PHP y Composer** de Devsense

Iremos averiguando más sobre estas extensiones pero investiga por tu cuenta sobre sus principales funcionalidades.

Una vez instaladas las extensiones podremos lanzar un server de PHP directamente desde el VSCode, abre el proyecto desde la carpeta donde lo creaste y desde la consola del VSCode escribe:
```
php -S localhost:3000
```

##Hola, mundo!

Para poder introducir scripts de php vamos a crear un index.php en la carpeta e introducimos las etiquetas que abren y cierran los scripts dentro de nuestro código html. Crea un fichero index.php y escribe lo siguiente:
```
<h1><?php echo "Hola mundo en PHP!";?></h1>
```
Si no se ve lo que esperas...por qué crees que puede ser??
```

<?php
    echo "<h1>Hola mundo! </h1>";
    //otras funciones para mostrar print y print_r

    //la otra función que vamos a utilizar para mostrar datos es var_dump, para qué crees que la usaremos?
    var_dump("hola mundo");



?>
```

Después de hacer nuestro primer y tradicional "hola mundo" en PHP, descarguen el fichero zip incluido en el campus y descompriman en la carpeta htdocs del Apache.

Como ven en el proyecto hay una carpeta includes que nos va a servir para definir las partes del proyecto repetitivas que queremos utilizar en varias páginas en nuestro archivo "01-hola-mundo.php" utilizaremos el siguiente código para darle formato a nuestro tutorial. 

Para repasar los contenidos de LND, modifiquen los archivos que haga falta para personalizar el aspecto. 
En el CSS actual tenemos las siguientes lineas de código: 
```
body {
    background: #4b6cb7;  /* fallback for old browsers */
    background: linear-gradient(to right, #182848, #b74bb7);  /* Chrome 10-25, Safari 5.1-6 */
    background: linear-gradient(to right, #182848, #b74bb7); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}
```

¿Para qué sirven esas líneas? ¿cómo comprobamos si realmente en la actualidad son necesarias?? 


