# IBM Cloud - Estimado de Costos ☁💳
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

1. En el catálogo busque el servicio *Virtual Server for VPC*. Para ello filtre el servicio mediante la categoría ```Cálculo/Compute``` y porteriormente de click sobre la opción *Virtual Server for VPC*.

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

<p align="center"><img width="700" src="https://github.com/emeloibmco/IBM-Cloud-Estimado-Costos/blob/main/Imagenes/VSI.gif"></p>
<br />

## Estimado Databases for PostgreSQL :books:
<br />

## Estimado Block Storage for VPC :package:
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
