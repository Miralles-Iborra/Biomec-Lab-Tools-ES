# Biomec-Lab-Tools-ES
Herramientas y scripts para el procesamiento, análisis y visualización de datos biomecánicos, fisiológicos y de rendimiento deportivo con Python.

## Introducción

El análisis del movimiento humano y del rendimiento deportivo suele implicar el manejo de grandes cantidades de datos procedentes de diferentes fuentes: sistemas de captura de movimiento, plataformas de fuerza, electromiografía, dispositivos GPS, monitores de frecuencia cardiaca, aplicaciones de análisis de vídeo o cuestionarios de percepción del esfuerzo, entre otras.

Aunque muchas tareas pueden resolverse inicialmente mediante hojas de cálculo o programas comerciales, estos recursos no siempre permiten automatizar los procedimientos, reproducir los análisis de forma consistente o adaptar el procesamiento a las características concretas de cada proyecto. En estas situaciones, la programación ofrece una alternativa flexible para desarrollar soluciones específicas y reproducibles.

Python es un lenguaje de programación gratuito y de código abierto que dispone de numerosas librerías para el tratamiento de datos científicos. Con unas nociones básicas, permite automatizar tareas repetitivas, reducir errores manuales y documentar con precisión cada paso del análisis.

Entre sus posibles aplicaciones se encuentran:

La importación y organización automática de grandes conjuntos de datos.
La limpieza, transformación y filtrado de señales biomecánicas y fisiológicas.
El cálculo de variables relacionadas con el movimiento, la carga y el rendimiento.
La realización de análisis estadísticos descriptivos e inferenciales.
La creación de figuras y gráficos con calidad de publicación.
La generación automática de informes, tablas y archivos de resultados.
El desarrollo de herramientas interactivas para investigadores y profesionales.

Este repositorio reúne scripts, cuadernos de Google Colab y ejemplos prácticos dirigidos principalmente al ámbito de la biomecánica, la fisioterapia y la medicina deportiva. Las herramientas se desarrollan con el objetivo de facilitar procedimientos que, de otro modo, requerirían una gran cantidad de trabajo manual.

Cada herramienta aborda una necesidad concreta e incluye, siempre que sea posible, una explicación de su funcionamiento, los archivos de entrada necesarios, las decisiones metodológicas aplicadas y la interpretación de los resultados obtenidos.

El propósito de este repositorio no es ofrecer soluciones universales, sino compartir recursos transparentes, modificables y reproducibles que puedan adaptarse a diferentes contextos de investigación y práctica profesional. 

## Uso de las herramientas en Google Colab
En los cuadernos de Google Colab, el procesamiento se realiza mediante celdas ejecutables, por lo que no es necesario instalar Python ni utilizar una aplicación externa.
Abre el cuaderno mediante el botón Abrir en Google Colab.
Ejecuta las celdas siguiendo el orden indicado.
Selecciona el modo de entrada de datos.
Carga los archivos solicitados o utiliza los datos de ejemplo.
Revisa las señales y selecciona los eventos de interés.
Comprueba los resultados y descarga los archivos generados.

## Aviso 
Los scripts deben considerarse herramientas de apoyo para la investigación, la docencia y la práctica profesional. El usuario es responsable de comprobar la calidad de los datos, la adecuación de los procedimientos y la interpretación de los resultados.

## Contribuciones

Las sugerencias, correcciones y propuestas de mejora son bienvenidas. También puedes abrir una issue o proponer cambios mediante una pull request.

## Scrips de interés
### Análisis de zonas de frecuencia cardiaca

Herramienta interactiva para calcular el tiempo acumulado en diferentes zonas de frecuencia cardiaca durante las partes de fuerza, funcional y resistencia de cada sesión.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/14najmM9AenrtVdPAOIq2pX93NqBPa4re?usp=sharing)

### Análisis de saltos mediante plataformas de fuerza

Herramienta desarrollada en Google Colab para importar, procesar y visualizar datos obtenidos mediante una o dos plataformas de fuerza durante diferentes tipos de salto vertical.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1-vxn9aJDPOOvY3PhVocSpSOvW_r53-yq?usp=sharing)

El cuaderno permite trabajar mediante tres modalidades:

Cargar un archivo propio exportado directamente desde la plataforma de fuerza.
Cargar una matriz de datos previamente organizada.
Utilizar los datos de ejemplo incluidos en el cuaderno.

La herramienta facilita la inspección de las señales registradas y el análisis de las principales variables mecánicas relacionadas con el salto.

Entre sus funcionalidades se incluyen:

Detección y selección de los eventos del salto.

Visualización de la fuerza vertical en función del tiempo.

Cálculo de la fuerza total cuando se utilizan dos plataformas.

Estimación de la aceleración del centro de masas.

Cálculo de la velocidad mediante integración de la aceleración.

Estimación del desplazamiento vertical del centro de masas.

Representación conjunta de fuerza, aceleración, velocidad y desplazamiento.

Gráficas interactivas con desplazamiento, zoom y selección de intervalos.

Selección visual del evento de interés dentro de la serie temporal.

Exportación de los resultados para análisis posteriores.


## Licencia

![68747470733a2f2f692e6372656174697665636f6d6d6f6e732e6f72672f6c2f62792f342e302f38387833312e706e67.png](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAFgAAAAfCAMAAABUFvrSAAAAAXNSR0IB2cksfwAAAARnQU1BAACxjnz7UZMAAAAgY0hSTQAAeiUAAICDAAD5/wAAgOkAAHUwAADqYAAAOpgAABdvkl/FRgAAAW5QTFRFAAAAAAAA////////////7+/v39/f1tXV09bS0tXS0tXR0dTR0dTQ0NTQ0NPPz9PPztLOztHNzdHNzdHMz8/PzdDMzNDMzNDLzM/Ly8/Ly8/Ky87Kys3Jyc3Jyc3IyMzIyMzHx8vHxsrGxsrFxcnFxcnExMnExMjDw8jDxMfDw8fCwsfCwcXAwMXAwMW/wMS/v8S+v8O+vsO+vsK9vcK9vcK8v7+/vMG8vMG7vMC8u8C7u8C6ur+6ur+5ub65ub64uL23t7y2tru1tbq0tLqztLmzs7iysrixsrexsbewsbawsLavsLWvr7Wur7SusLOvrrStrrOtr7KvrbOsrLKrr6+vq7Gqn6OenqCdn5+flpmWk5iTkZSRkZORj4+PiYyJhIaEhIWEgoWCgICAfX98fH98eXx5cHJvcHBwYGBgXV5dUFFQUFBQQ0RDQEBAPj8+NTY1MjMxMDAwKSkpKCkoICAgGxsbEBAQDg4ODQ4N2y3MbAAAAAR0Uk5T/wAKDnDBpeYAAALVSURBVHjatZX9V9JgFMdvNQh1Tme2zU1othSl5WsQZoqIrxmmqaUpqS2JKczibfLfd5+hHCYybB6/B859ftg+5+57Xx54Ag+iR/hPxGPRSXVYkf2SwHGC2C8rQXUiOhdPLK992tze3vn6/wKLOxseCykBkWXoNp+vrYNh+wJKaDQ8S8jJze0dl2TkvgkOSCx9kqsAqpI7prtFeUh9i+SV9eRWY8rpAqAKaWdwDLkyz6TKUFP5kOECg2p4Lr60ut6Q8kERwMhkDIDigRM4OhaUOfocT6auRSKabuLxfORZYGg0GltAM26k/O0Ssl4K5c3C5YEDeDI0wBOuqXmoqvYRXRzh5NDEzHwCU7aDi6DjMwDkQSg6gFVFYpCb91I1efKYMyMqahhT/rhh8yIN2adVMCoL6ebg4RdsCrmYrp182B0Ijs/EF1eTW/XgAtRl4IVCc7Ai0mUweymbPCaU6T5FfRdLrNi9AINC6QA6iQY0B8s9JwCanUvsg2NWDk3Nohd2cIZCAYrEjAPY35UDE42IZA1Dq4Yf+IoJOaafeLG0tuEOLNEV0BEIRMauFXTysZUOcXD0/fziWtKdFUI7AKaYh5I3UtrPY3vslvYtL9oERY1iwyG4oXgALYvH+wAiFGX5XAvWF/i4l41gbDfKod3cgu0DksEBuYsVnt6ShlaQ0GCF00g7F++qaleBZFOhpcbiEXIRIK9n8q2WkL/rHEyq1m67hhWoErabPzj+odpubtam3JNCL24fkNdTcwvLZPLcLPpX1kh7HUbaJRiX0N5tSyjFBoYncPDIEnIFhlOJOUNy3RryWmtT+gn31G+hs37RezQT4A/Nn8K99YvrPLtxNdHPv0MzVeeDHFqTBWav/jJNMXxzLlBXP+oubkgsnbq+/g9pVnLy4Xptwl3094vY00W3+3ztNMP2fb4AB9mMaK2Lo2lJ4HlBmj4iWLcZP7wePwz20T8rQcP0CuFIbQAAAABJRU5ErkJggg==)

Este obra está bajo una licencia de [Creative Commons Reconocimiento 4.0 Internacional.](https://creativecommons.org/licenses/by/4.0/)

## Autor

Aarón Miralles Iborra

## Última actualización

30/07/2026
