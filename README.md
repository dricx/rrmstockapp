# RRM StockApp v5.1.7718.17716-alpha2
<center>
<img src="https://github.com/dricx/rrmstockapp/blob/main/screenshots/Screenshot%208.png" alt="Italian Trulli">
</center>

RRM StockApp 5 es un sistema de facturación y gestión de inventario programado en C#. Cuenta con 9 módulos diferentes de los cuales los mas importantes son:

  * Módulo de terceros;
  * Módulo de inventario y Kardex de inventario;
  * Módulo de cotización;
  * Módulo de conduces;
  * Módulo de facturación;
  * Módulo de devoluciones;
  * Módulo de créditos y cobros;
  * Módulo de deudas y pagos;
  * Secuencias de NCF;
  * Blackboard de notas por documento;
  * Funciones de escaneo de documentos, adjuntables a cualquier documento en el programa.
  * Administración de permisos de acceso a usuarios para los diferentes módulos;
  * Configuración de formato de fecha;
  * Configuración de formato de moneda;
  * Tipos de documentos modificables, tanto para kardex como para documentos del módulo de compra y  de facturacion;
  * Soporte de impresión para impresoras térmicas Epson;
  * Capacidad para trabajar con escáneres de código de barra USB;
  
<b><span style="color: red">NOTA IMPORTANTE:</span> El programa esta en versión alpha por lo que es muy probable que contenga varios errores. Mantengase ingresando al repositorio para versiones mejoradas y con mas funciones. Si va a actualizar desde una version anterior, respalde los datos para no perderlos.</b>

## Mejoras de nueva version 🧰

  * Mejoras en el formulario de creacion de backups;
  * Bug arreglado: ahora se pueden crear nuevas base de datos desde el sistema;
  * Bug arreglado: al iniciar el sistema por primera vez, configura la base de datos del sistema en forma de wizard;
  * Bug arreglado: si no hay base de datos seleccionada, no carga los datos de la empresa;
  * Bug arreglado: al presentar los precios y el costo en los documentos de facturacion, compra y devolucion;
  * Bug arreglado: calculo de itbis en facturas, compras y devoluciones;
  * Bug arreglado: Al presionar crear nueva factura desde el toolbar no generaba un nuevo documento;
  * Agregado soporte de impresoras termicas Epson;
  * Mejoras en formularios de tercero, producto, facturacion, devolucion, compras y cotizacion;
  * Presenta mas informacion sobre los productos disponibles;
  * Actualizacion de costes y precios automaticas dependiendo variaciones de costo (opcional);
  * Mejoras en sistema de escaneo de documentos;
  * Eliminacion (Anulacion de linea) de producto de factura guardada;
  * Es posible visualizar todos los proveedores de un producto y el costo desde su ficha;
  * Sistema de respaldo mejorado, ahora se presentan los respaldos en el formulario clasificados por fecha y es posible respaldar desde el mismo formulario;
  * Buscador rápido de documentos por código o Barcode en la ventana principal;

## Comenzando 🚀

Los requisitos de instalación son los que siguen a continuación:
  * .Net Framework 4.7.2;
  * MySql 10.4.16-MariaDB o Xampp 3.2.4;
  * Adobe Acrobat Reader DC; (Para los reportes)
    
### Instalación 🔧

<h4><span style="color: red">Importante:</span> Debe instalar y correr el servidor antes de iniciar el programa.</h4>

  * Ejecute el archivo Setup.exe para instalar la aplicación;
  * Instale el servidor Mysql 10.1.16 o superior O Xampp 3.2.4 o superior (Puede descargarlo desde aquí https://www.apachefriends.org/es/index.html);
  * Cree una base de datos con el nombre <span style="color: red; font-weight: bold">test</span>, es recomendable utilizar el encoding UTF-8 para la base de datos;
  * Vaya a la base de datos creada e importe el archivo squema.sql localizado en la carpeta raíz del programa; (Este paso es opcional)

<b><span style="color: red">Nota</span>: A partir de esta version solo necesita correr el servidor MySQL y ejecutar la aplicacion. Configurar los accesos de usuario, y seguir las indicaciones del programa. La base de datos se configura de manera automatica al iniciar por primera vez a partir de la version v5.1.7718.17716.</b>
  
La aplicacion viene configurada por defecto para acceder como root, pero es posible reconfigurar esas caracteristicas mas adelante.

## Construido con 🛠️

Para crear el proyecto se utilizo:
   * Visual Studio Community 2019;
   * MySQL 10.4.16;
   * Itext7;
   * Adobe Acrobat Reader;
   
## Versionado 📌

Para todas las versiones disponibles, mira los [tags en este repositorio](https://github.com/dricx/rrmstockapp/tags).

## Autores ✒️

   * Richard N. Ramos - Desarrollador - [dricx](https://github.com/dricx) - [Linkedin](https://www.linkedin.com/in/rramos1988)
   
También puedes mirar la lista de todos los [contribuyentes](https://github.com/dricx/rrmstockapp/contributors) quíenes han participado en este proyecto. 

## Screenshots 📺
<center>
<img src="https://github.com/dricx/rrmstockapp/blob/main/screenshots/Screenshot%201.png" alt="Italian Trulli">
</center>

<center>
<img src="https://github.com/dricx/rrmstockapp/blob/main/screenshots/Screenshot%202.png" alt="Italian Trulli">
</center>

<center>
<img src="https://github.com/dricx/rrmstockapp/blob/main/screenshots/Screenshot%203.png" alt="Italian Trulli">
</center>

<center>
<img src="https://github.com/dricx/rrmstockapp/blob/main/screenshots/Screenshot%204.png" alt="Italian Trulli">
</center>

<center>
<img src="https://github.com/dricx/rrmstockapp/blob/main/screenshots/Screenshot%205.png" alt="Italian Trulli">
</center>

<center>
<img src="https://github.com/dricx/rrmstockapp/blob/main/screenshots/Screenshot%206.png" alt="Italian Trulli">
</center>

<center>
<img src="https://github.com/dricx/rrmstockapp/blob/main/screenshots/Screenshot%207.png" alt="Italian Trulli">
</center>

<center>
<img src="https://github.com/dricx/rrmstockapp/blob/main/screenshots/Screenshot%209.png" alt="Italian Trulli">
</center>

## Licencia 📄

Este proyecto está bajo la Licencia (GPL-3.0 License) - mira el archivo [LICENSE.md](LICENSE.md) para mas detalles. El desarrollador se guarda el derecho de realizar cambios de licencia sin previo aviso.

## Código fuente📝

Si estás interesado en el código fuente: richramos1988@gmail.con
