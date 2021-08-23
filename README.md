# IBM Cloud - Estimado de Costos ☁💳
*IBM Cloud®* cuenta con un estimador de costos, esta calculadora de precios en la nube sirve para configurar los productos de *IBM Cloud®* y generar estimaciones de costos confiables, de esta manera podrá comparar configuraciones, conocer como se determina el precio detallado de un producto y descargar cotizaciones. 

La presente guía pretende generar un resumen de los costos asociados a diferentes productos de *IBM Cloud*:  VSI for VPC,  base de datos PostgreSQL, Block Storage for VPC y Load Balancer for VPC.

<br />

## Índice  📰
1. [Pre-Requisitos](#Pre-Requisitos-pencil)
2. [Acceder al estimador de costos](#Acceder-al-estimador-de-costos-heavy_dollar_sign)
3. [Estimado Virtual Server for VPC](#Estimado-Virtual-Server-for-VPC-computer)
4. [Estimado Databases for PostgreSQL](#Estimado-Databases-for-PostgreSQL-books)
5. [Estimado Block Storage for VPC](#Estimado-Block-Storage-for-VPC-package)
6. [Estimado Load Balancer for VPC](#Estimado-Load-Balancer-for-VPC-cloud)
7. [Acceso al resumen de estimados](#Acceso-al-resumen-de-estimados-clipboard)
8. [Referencias](#Referencias-mag)
9. [Autores](#Autores-black_nib)
<br />

## Pre Requisitos :pencil:
* Contar con una cuenta en <a href="https://cloud.ibm.com/"> IBM Cloud </a>.
<br />

## Acceder al estimador de costos :heavy_dollar_sign:
Para acceder a la herramienta del estimador de costos de *IBM Cloud*, realice lo siguiente:
1. Dentro de su cuenta de *IBM Cloud* acceda al ```Estimador de costos/Cost estimator``` dando click en la pestaña <a href="https://cloud.ibm.com/estimator/review"><img width="25" src="https://github.com/emeloibmco/IBM-Cloud-Estimado-Costos/blob/main/Imagenes/Estimador.PNG"></a>, que se ubica en la parte superior derecha del portal. 

2. Una vez cargue la herramienta, de click en el botón ```Ir al catálogo/Go to catalog``` y allí busque los respectivos servicios que desea estimar.
<br />

## Estimado Virtual Server for VPC :computer:
Para realizar el estimado de un *Virtual Server for VPC* en el portal de *IBM Cloud*, siga los pasos que se muestran a continuación:

1. En el catálogo busque el servicio *Virtual Server for VPC*. Para ello, filtre el servicio mediante la categoría ```Cálculo/Compute``` y porteriormente de click sobre la opción *Virtual Server for VPC*.

2. Configure los campos que se solicitan para realizar la estimación del servicio, de la siguiente manera:

   **Detalles/Details**
   * ```Nombre/Name```: indique un nombre exclusivo para la *VSI*. 
   * ```Grupo de recursos/Resource group```: seleccione el grupo de recursos.
   * ```Ubicación/Location```: indique la región en la cual ubicará la *VSI* que desea estimar.
   * ```Tipo de servidor virtual/Virtual server type```: seleccione el tipo de servidor virtual.
   <br />

   **Sistema Operativo/Operating System**
   * ```Imagen/Image```: seleccione el sistema operativo de la *VSI* que desea estimar. Por ejemplo: ```CentOS```.
   <br />

   **Perfil/Profile**
   * Seleccione el perfil de la *VSI* que desea estimar. Por ejemplo: ```bx2-2x8```
   * ```Claves SSH/SSH Keys```: seleccione la clave *SSH* si tiene alguna o deje el campo sin seleccionar (esto no afectará la estimación).
   <br />

   **Grupo de colocación/Placement group**
   * Deje el campo sin seleccionar.
   <br />

   **Volumen de arranque/Boot volume**
   * Por defecto deje un volumen de 100 GB de almacenamiento.
   <br />

   **Volúmenes de datos/Data volumes**
   * Puede dejar este campo vacío para realizar la estimación. Si requiere un disco adicional agregue el almacenamiento en el volumen de datos.
   <br />

   **Redes/Networking**
   * ```Nube privada virtual/Virtual private cloud```: seleccione la *VPC* en donde se ubica la *VSI*.
   <br />

   **Interfaces de red/Network interfaces**
   * Seleccione la subred en la que trabaja la *VSI* en *VPS*.
   <br />

3. De click en el botón ```Añadir a estimación/Add to estimate```.

4. Posteriormente, observará una ventana que indica información breve sobre el costo de la *VSI* estimada. De click en el botón ```Revisar estimación/Review estimate```.

5. Espere mientras carga la herramienta. Finalmente, podrá visualizar la estimación realizada al servicio *VSI for VPC*.
<br />

<p align="center"><img width="800" src="https://github.com/emeloibmco/IBM-Cloud-Estimado-Costos/blob/main/Imagenes/VSI.gif"></p>
<br />

## Estimado Databases for PostgreSQL :books:
Para realizar el estimado de un servicio *Databases for PostgreSQL* en el portal de *IBM Cloud*, siga los pasos que se muestran a continuación:

1. En el catálogo busque el servicio. Para ello, filtre el servicio mediante la categoría ```Bases de datos/Databases``` y porteriormente de click sobre la opción *Databases for PostgreSQL*.

2. Configure los campos que se solicitan para realizar la estimación del servicio, de la siguiente manera:

   **Detalles del servicio/Service Details**
   * ```Nombre/Service name```: indique un nombre exclusivo para el servicio. 
   * ```Grupo de recursos/Resource Group```: seleccione el grupo de recursos.
   * ```Ubicación/Location```: indique la ubicación en la cual se encuentra el servicio que desea estimar.
   <br />
   
   **Asignación de recursos/Resource Allocation**
   * ```Plantillas/Templates```: puede seleccionar alguna de las plantillas establecida por defecto si lo desea.
   * ```Personalizado/Custom```: puede configurar de forma personalizada el servicio. Por ejemplo: memoria RAM de 4 GB, disco de 100 GB y 0 núcleos dedicados. Esta es la opción        elegida para este caso.

   Deje los demás campos con los valores que se establecen por defecto.
   
   <br />

3. De click en el botón ```Añadir a estimación/Add to estimate```.

4. Posteriormente, observará una ventana que indica información breve sobre el costo de la *VSI* estimada. De click en el botón ```Revisar estimación/Review estimate```.

5. Espere mientras carga la herramienta. Finalmente, podrá visualizar la estimación realizada al servicio *Databases for PostgreSQL*.
<br />

<p align="center"><img width="800" src="https://github.com/emeloibmco/IBM-Cloud-Estimado-Costos/blob/main/Imagenes/PostgreSQL.gif"></p>
<br />

## Estimado Block Storage for VPC :package:
Para realizar el estimado de *Block Storage for VPC* en el portal de *IBM Cloud*, se debe realizar lo siguiente:
<br />

1. Busque el servicio *Block Storage for VPC*. Para ello filtre el servicio mediante la categoría Almacenamiento/Storage y posteriormente de click sobre la opción *Block Storage for VPC*.
<br />

2. Una vez cargue la nueva ventana complete la configuración del servicio de la siguiente manera:
* ```Ubicación/Location```: seleccione la ubicación en la cual desplegará el servicio.

**Detalles/Details**: 
* ```Método de Facturacción/Billing Method```: seleccione el método de facturación que desea utilizar ya se Por horas/For hours o Por meses/For month.
* ```Tamaño/Size```: especifique el tamaño, recuerde que debe ser un valor entre 20 y 12000 GB.
* ```Espacio de Instantáneas/Snapshot Space```: especifique el espacio de las instantáneas.
* ```Tipo de SO/SO Type```: determine el tipo de sistema operativo que va utilizar.

**Perfil de IOPS/IOPS Profile**: 
* ```Resistencia (niveles)/Resistance (levels)```: seleccione el nivel de resistencia en IOPS/GB.
* ```Rendimiento (personalizadas)/Performance (custom)```: Deje el valor por defecto (100).
<br />

3. Cuando ya tenga todos los campos configurados de click en el botón ```Añadir a estimación/Add to estimate```. Asegurese de que se encuentre con el tamaño que eligio previamente.
<br />

4. A continuación, elija ```Calcular costo/ Calculate cost``` > ```Guardar/Save```.
<br />

5. Para revisar que la estimación quedo guardada, haga click en ```Revisar estimado/ Review estimate```. 
<br />

7. Finalmente observe un resumen del producto que acabo de configurar con el costo estimado.
<br />

<p align="center"><img width="800" src="https://github.com/emeloibmco/IBM-Cloud-Estimado-Costos/blob/main/Imagenes/blockstorage.gif"></p>
<br />

## Estimado Load Balancer for VPC :cloud:
<br />

## Acceso al resumen de estimados :clipboard:
<br />

## Referencias :mag:
* <a href="https://cloud.ibm.com/estimator/review">Estimador de costos</a>.
<br />

## Autores :black_nib:
Equipo *IBM Cloud Tech Sales Colombia*.
<br />
