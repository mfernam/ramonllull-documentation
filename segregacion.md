# Segregación

Supuesto de hecho:
Los hermanos Pérez,  María y Juan, han heredado por mitades un terreno y quieren dividir la finca en dos parcelas de la misma extensión con el fin de adjudicarse cada uno de ellos una de las parcelas resultantes. Se ha obtenido la correspondiente licencia de segregación. María se adjudica la finca segregada y Juan se queda con el resto de finca matriz.

La referencia catastral: 

**03900A04900121**


![](/images/seg1.jpg)

Resumen de la operación:

**La Notaría** genera la operación correspondiente a la segregación, descarga la finca correspondiente a esa referencia catastral, lo asigna al técnico y archiva el expediente.


Procedimiento a seguir:

1. Generamos un nuevo expediente en la pestaña de **Nuevo expediente**.
2. El programa asigna un número de expediente automáticamente.
3. Le indicamos el tipo de operación que se va a realizar, en este caso **Segregación**.
4. Le indicamos el solicitante o los solicitantes.
5. Insertamos una breve descripción del proyecto.
6. Con el botón derecho sobre **Operaciones**, se despliega un menú con las operaciones que puedes realizar.
7. Le indicamos la operación que vamos a realizar, en este caso **Nueva Segregación**.
8. En **Descargar finca matriz** se añade la referencia catastral de la finca objeto de la operación. ![](/images/seg2.jpg) 
![](/images/seg3.jpg)

9. Ventana donde se carga la referencia catastral de la finca objeto de la operación de segregación.
10. Hay que **Guardar los expediente**, para que se pueda generar fichero para técnico competente.
11. La notaría asigna a este expediente un técnico competente. 
12. Asignamos nuevo técnico, **Asignar nuevo técnico**.
13. Desde la notaría, rellena los datos de asignación de técnico y le da al botón **Asignar**, entonces se asigna este expediente a un técnico competente
![](/images/seg4.jpg)

14. En el árbol del expediente ya aparecen los técnicos asociados a ese expediente.
15. Hay que asegurarnos, siempre de guardar el expediente, antes de salir.
![](/images/seg5.jpg)
**El técnico** abre el expediente que le ha sido asignado y genera, desde la aplicación, el **fichero para técnico competente** (fichero DXF), sobre el que adaptará el proyecto técnico de segregación al perímetro dado en este fichero (en coordenadas geográficas UTM de Catastro).
![](/images/seg6.png)
16. Abrir el gestor de expedientes y pinchando  en el botón de nº de expediente.
17. Se abrirá la ventana donde aparece una lista de todos los expedientes que tiene asignados ese técnico con independencia de la Notaría que lo haya asignado. Pinchamos sobre el expediente con el que estamos trabajando, en este caso el **03000000001201200000017**, que en la imagen aparece rodeado en rojo.
18. Al pinchar sobre él aparecerá el expediente con todos los datos, que se han generado inicialmente en la notaria, en nuestra ventana de Gestión de expedientes. Generamos el fichero DXF (fichero de intercambio), que será utilizado como base por el técnico para la segregación de la parcela en un programa de edición gráfica.
19. Le indicamos donde se guardará el fichero y le damos a aceptar.
![](/images/seg7.png)
Desde un programa CAD, parte la finca con una polilínea que divida la finca en dos parcelas (la finca segregada y el resto de finca matriz), adaptando al fichero generado por el Ramón Llull el trabajo previo de campo o de gabinete.