# rrmstockapp
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
  * Entre otras funciones que pueden ser verificadas dentro del mismo.
  
<b><span style="color: red">NOTA IMPORTANTE:</span> El programa esta en versión alpha por lo que es muy probable que contenga varios errores.</b>

Los requisitos de instalación son los que siguen a continuación:
  * .Net Framework 4.7.2;
  * MySql 10.4.16-MariaDB o Xampp 3.2.4;
  
<h1> Pasos para instalar el programa </h1>

<h4><span style="color: red">Importante:</span> Debe instalar el servidor antes de iniciar el programa.</h4>
 * Ejecute el archivo Setup.exe para instalar la aplicación;
 * Instale el servidor Mysql 10.1.16 o superior O Xampp 3.2.4 o superior (Puede descargarlo desde aquí https://www.apachefriends.org/es/index.html);
 * Cree una base de datos con el nombre <span style="color: red; font-weight: bold">test</span>, es recomendable utilizar el encoding UTF-8 para la base de datos;
 * Vaya a la base de datos creada e importe el archivo squema.sql localizado en la carpeta raíz del programa;
 
La aplicacion viene configurada por defecto para acceder como root, pero es posible reconfigurar esas caracteristicas mas adelante.

Mas abajo podra encontrar algunas screenshots de la aplicación:
