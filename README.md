# <img aling src="https://github.com/malegria01/ACI2227/blob/main/img/programacion.jpg" alt="drawing" width="100">  ACI2227  
 


# Curso Programación Aplicada ACI2227 Facultad Ingeniería y Negocios UDLA.

## Profesora: Melissa Alegría. 

Este repositorio contiene material suplementario (pero en ningún caso obligatorio) al curso online de Programación Aplicada ACI2227.
 
##### Aquí encontrarás material para complementar tu aprendizaje y poner en práctica tus conocimientos obtenidos en la plataforma blackboard.


## Material Suplmentario 

Ya has aprendido el modelo cascada o waterfall model, el cual tiene etapas como ```Análisis``` , ```Diseño``` , ```Codificación``` , ```Ejecución``` , ```Verificación``` y ```Mantenimiento y Documentación```.
Este es un modelo clásico que tiene ventajas y desventajas

| Ventajas| Desventajas         
|:--------------------|:--------------------:|
| Lleva un orden del trabajo a realizar. |  Para proyectos grandes o complejos, puede que sea más difícil dividirlo en fases ordenadas, por lo que este modelo puede no ser el más adecuado.
| Útil para comenzar en programación | Al ser una forma de trabajo lineal, no  se puede pasar a la etapa siguiente hasta que completes la anterior.
| Funciona de manera óptima en la mayoría de los dispositivos. | En ocasiones, los fallos no se detectan hasta la última fase del desarrollo por lo que  se regresa a las fases anteriores
| Ayuda a tener claridad en los objetivos desde el comienzo del proyecto ya que es sencillo y fácil de seguir. | No es eficiente para subdividir procesos y trabajar en equipo para proyectos mas complejos
|Al encontrar un problema, se puede fácilmente detectar la fase en la que surgió y así arreglarlo.


> Existen otras metodologías como : 
Agile, desarrollo por etapas, desarrollo concurrente, modelo en espiral, entre otros. Te recomiendo buscar más información sobre AGILE.

### AGILE
**Agile** es una forma más flexible y eficiente de desarrollar o enfocarse en el desarrollo del producto. El significado de Agile (ágil) es la capacidad de moverse rápida y fácilmente.

* Agile es un enfoque incremental e iterativo
* Agile separa un proyecto en sprints
* Agile ayuda a completar muchos proyectos pequeños, 
* Agile trabaja bajo una mentalidad de producto con un enfoque en la satisfacción del cliente. En tanto, la metodología Waterfall se desarrolla con un enfoque en la entrega exitosa del proyecto.

Buscar sobre SCRUM para complementar.


## JAVA
Java proporciona la clase ***Graphics***, que permite dibujar elipses, cuadrados, líneas, mostrar texto y también tiene muchos otros métodos de dibujo. Para cualquier programador, es esencial el entendimiento de la clase Graphics, antes de adentrarse en el dibujo en Java.

Si deseas profundizar en la Clase Graphics y sus métodos te esta [pagina web](https://www.tutorialesprogramacionya.com/javaya/detalleconcepto.php?codigo=130&punto=&inicio=), tiene ejemlpos y videos a esos ejemplos


Cuando el usuario de un programa o applet mueve el ratón, o hace un clic o usa el teclado, genera un Evento. En Java los eventos, como cualquier otra cosa, se representan como instancias u objetos de alguna clase. Para programar una interfaz gráfica es necesario aprender a utilizar los eventos.
Un aspecto importante es conocer que hacen estos eventos, por lo que te recomiendo complementar tu estudio esta [Unidad](https://arquimedes.matem.unam.mx/pasados/java_profundizacion/index4.htm)


## ¿Cómo crear FileFilter para JFileChooser en Java y mostrar el tipo de archivo en consecuencia?

Para crear FileFilter, utilice la clase FileNameExtensionFilter. El siguiente es un ejemplo para mostrar el tipo de archivo en JFileChooser

>Ejemplo

```
import javax.swing.JFileChooser;
import javax.swing.filechooser.FileNameExtensionFilter;
public class SwingDemo {
   public static void main(String[] args) {
      JFileChooser file = new JFileChooser();
      file.setAcceptAllFileFilterUsed(false);
      FileNameExtensionFilter extFilter = new FileNameExtensionFilter("JPEG file", "jpg", "jpeg");
      file.addChoosableFileFilter(extFilter);
      file.showOpenDialog(null);
   }
}

```

Salida

![imagen](https://user-images.githubusercontent.com/8738096/161644808-c647794e-41ee-43a5-8bee-befe4de77821.png)

