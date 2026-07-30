# Biomec-Lab-Tools-ES
Herramientas y scripts para el procesamiento, análisis y visualización de datos biomecánicos, fisiológicos y de rendimiento deportivo con Python.

## Introducción

El análisis del movimiento humano y del rendimiento deportivo suele implicar el manejo de grandes cantidades de datos procedentes de diferentes fuentes: sistemas de captura de movimiento, plataformas de fuerza, electromiografía, dispositivos GPS, monitores de frecuencia cardiaca, aplicaciones de análisis de vídeo o cuestionarios de percepción del esfuerzo, entre otras.

Aunque muchas tareas pueden resolverse inicialmente mediante hojas de cálculo o programas comerciales, estos recursos no siempre permiten automatizar los procedimientos, reproducir los análisis de forma consistente o adaptar el procesamiento a las características concretas de cada proyecto. En estas situaciones, la programación ofrece una alternativa flexible para desarrollar soluciones específicas y reproducibles.

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

* Detección y selección de los eventos del salto.
* Visualización de la fuerza vertical en función del tiempo.
* Cálculo de la fuerza total cuando se utilizan dos plataformas.
* Estimación de la aceleración del centro de masas.
* Cálculo de la velocidad mediante integración de la aceleración.
* Estimación del desplazamiento vertical del centro de masas.
* Representación conjunta de fuerza, aceleración, velocidad y desplazamiento.
* Gráficas interactivas con desplazamiento, zoom y selección de intervalos.
* Selección visual del evento de interés dentro de la serie temporal.
* Exportación de los resultados para análisis posteriores.

## Licencia

[![Licencia Creative Commons Reconocimiento 4.0 Internacional](https://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/deed.es)

Esta obra está bajo una licencia [Creative Commons Reconocimiento 4.0 Internacional](https://creativecommons.org/licenses/by/4.0/deed.es).

## Autor

**Aarón Miralles Iborra**

## Última actualización

30 de julio de 2026
