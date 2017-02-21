/************************************************************/
Codigo curso: CSOF5101 - 2017.
Nombre curso: CONCEPTOS AVANZADOS EN INGENIERIA DE SOFTWARE.
Nombre de la tarea: Assignment Kit for Program 1.
Fecha de envío de la tarea: 5 Febrero 2017 (00:55), GithHub: 20 Feb 2017. (23:23)
Autor: Walter Javier Alonso Roa
/************************************************************/


¨** Descripcion:
Primero se debe colocar el archivo a procesar en la carpeta "ArchivoProcesar". (deben ser txt),
el codigo fuente se encuentra en el repo: https://github.com/WalterAlonso/PSP0.git

** Ambiente de ejecucion:
Este programa fue realizado con JRE 1.7 en S.O 7.



**************** Instrucciones de ejecucion ************************
** pull repo desde github.
$git remote add origin https://github.com/WalterAlonso/PSP0.git

** Ejecucion maven

	 mvn package

** Ejecute el programa:

	java -cp target/PSP0_Calculo_Media_DesviacionEstandar-1.0-SNAPSHOT.jar uniandes.ecos.conceptosAvanzados.controlador.EstadisticaControlador "archivo a ser cargado.txt"


