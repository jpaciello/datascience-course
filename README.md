# Data Science con Impacto Social - Julio Paciello

Curso práctico sobre la ciencia de los datos y su aplicación al estudios de fenómenos sociales mediante el uso de _**datos abiertos**_ por el gobierno nacional. El curso ofrece una introducción a las principales conceptos, técnicas, y herramientas necesarios para extraer conocimiento de los datos. En el curso se aprenderá a colectar y pre-procesar datos, plantear preguntas de investigación, responder a estas preguntas, y visualizar los resultados.

## Objetivos

1. Aprender los conceptos básicos sobre ciencia y análisis de datos
2. Aprender y aplicar técnicas para la obtención y pre-procesamiento de datos en bruto
3. Aplicar herramientas estadísticas básicas para el análisis exploratorio de datos
4. Aprender y aplicar técnicas de inferencia estadística que permitan derivar conclusiones a partir de muestras de datos
5. Aprender y aplicar técnicas de aprendizaje supervisado que permitan explorar relaciones en los datos y derivar predicciones

## Requisitos

* Experiencia en programación orientada a objetos. Obs. __Para alumnos de Ing. Informática de la UC, haber aprobado la asignatura Lenguaje de Programación II__
* Conocimientos básicos de estadística (distribución normal, promedio, mediana, modo, varianza, desviación estándard, estadarización) Obs. __Para alumnos de Ing. Informática de la UC, haber aprobado la asignatura Estadística__

 ## Datos del Curso

* __Inicio__: 24-10-2017
* __Finalización__: 12-12-2017
* __Limite de Inscripción__: 20-10-2017
* __Modalidad__: Presencial (8 clases de 3 horas por semana)
* __Lugar__: Facultad de Ciencias y Tecnología, Universidad Católica “Nuestra Señora de la Asunción”, Campus Santa Librada, Asunción
* __Día y hora de Lección__: Martes de 9:00 a 12:00
* __Dedicación y créditos__: 2 créditos por asistencia y presentación de trabajos prácticos. Se podrán considerar créditos adicionales con la continuidad del proyecto posterior a la culminación de la materia, que derive en artículos científicos publicables en conferencias internacionales

## Inscripción

Completar el formulario de inscripción al curso [aquí](https://goo.gl/forms/tOsDDGlfnqG3Yb0r2)

## Tópicos

1. Introducción a la ciencia de los datos y base teórica
2. Herramientas para análistas y científicos de datos
3. Colección y pre-procesamiento de datos
4. Análisis Exploratorio de datos
5. Inferencia Estadística
6. Aprendizaje supervisado

## Becas Don Carlos Antonio López (BECAL)
**Programa Nacional de Becas de Postgrados en el Exterior**
>Becas destinadas a egresados de una carrera con el fin de llevar a cabo sus estudios de especialización (maestrías o doctorados en un país extranjero). El principal desafío de BECAL es mejorar la oferta del capital humano avanzado, mediante el financiamiento de becas de estudios de entrenamiento docente y postgrados en centros de excelencia del exterior. El mismo, tiene por objetivo contribuir a aumentar los niveles de generación y aplicación de conocimiento en las áreas de Ciencias y Tecnología (CyT) y en los niveles de aprendizaje en la educación. El principal problema a ser abordado por este programa es la baja capacidad del país para generar y aplicar conocimiento requerido para el desarrollo.

[Referencia](http://www.becal.gov.py/)

### Datasets
En esta sección se presenta una descripción de los Datasets que contienen información de las becas otorgadas incluyendo datos de becarios, convocatoria y estudios a realizar en el extranjero, y además datos referentes a la cobertura otorgada a los becarios para cubrir los gastos de sus estudios.

#### Dataset: Becas otorgadas
| Atributo | Descripción | Tipo | Valores de ejemplo |
| --- | --- | --- | --- |
| Nº | Número ordinal del registro en el conjunto de datos | Ordinal | 1,2,3 |
| Condición | Indica la situación del becario | Categórico | Becario, Becario retornado, No becario, Pendiente |
| Nº | Número ordinal del registro en el subconjunto de datos correspondiente a la convocatoria a la que pertenece | Ordinal | 1,2,3 |
| Tipo de Convocatoria | Clasificador de la convocatoria | Categórico | 1ra. Convocatoria autogestionada, 2da. Convocatoria autogestionada, 3ra. Convocatoria autogestionada, 4ta. Convocatoria autogestionada, Chevening, Docente – Francia, Docente – España, Francia – SFERE, Fullbright, Laspau – Doctorado, Laspau |
| Fecha de adjudicación | Indica la fecha en que se adjudicó la beca | Fecha | DD de MM de AAAA |
| C.I. | Cédula de identidad del becario | Discreto | 1234567 |
| Sexo | Sexo del becario | Categórico | Masculino, Femenino |
| Edad | Edad del becario | Discreto | 25 |
| Funcionario Público (Institución) | En caso de ser funcionario público, indica la institución pública a la que está vinculado | Categórico | Lista de instituciones públicas del Paraguay |
| Cargo | En caso de ser funcionario público, indica el cargo que ocupa | Texto | Director general, Funcionario UNA, ... |
| Goce de Sueldo | En caso de ser funcionario público, si goza de sueldo durante la beca | Categórico | SI, SI parcial, NO... |
| Tipo de Beca (según Programa aprobado) | Clasificador de la beca otorgada | Categórico | Doctorado para investigación, Maestría para investigación, Maestría para profesionales, ... |
| Área de la ciencia | Área científica del estudio a cubrir por la beca | Categórico | Ciencias Agrícolas, Ciencias Sociales, Ciencias Médicas, ... |
| Disciplina | Disciplina específica dentro del área científica del estudio | Categórico | Ciencias biológicas, Ciencias de la información y comunicación, ... |
| Sector priorizado Conacyt | Clasificador del Conacyt que indica el sector de ciencias correspondiente | Categórico | Ciencias Agrícolas, Ciencias Sociales, Educación, ... |
| Subsector priorizado | Clasificador del Conacyt que indica el subsector de ciencias | Categórico | Tecnologías cognitivas, Biomedicina, ... |
| Maestría / Doctorado | Descripción del estudio de postgrado a realizar | Texto | PhD Estructura de grupos superficies abelianas, Master in Management, ... |
| Universidad de Destino | Descripción de la Universidad donde se realizan los estudios | Texto | Universidad de Chile, Universidad de Bremen, ... |
| Ranking | Clasificador que indica la fuente de ránking universitario utilizado | Categórico | QS, THE, Times, ... |
| Nº | Número ordinal que indica el ránking de la Universidad de destino según la fuente | Ordinal | 1,2,3 |
| Ranking de Área Específica | Clasificador que indica la fuente de ránking de áreas específicas utilizado | Categórico | QS, Times, Computer Sciences, ... |
| Nº | Número ordinal que indica el ránking de la Universidad de destino en el área específica del estudio según la fuente | Ordinal | 1,2,3 |
| Ciudad de destino (en español) | Descripción de la ciudad de destino del estudio | Categórico | Lista de ciudades del mundo |
| País de Destino | Descripción de la país de destino del estudio | Categórico | Lista de países del mundo |
| Meses de duración de estudios | Cantidad de meses que dura el estudio  | Discreto | 24,48 |
| Inicio (cobertura de beca) | Fecha de inicio de la cobertura de la beca | Fecha | MM/DD/AAAA |
| Fin (cobertura de beca) | Fecha de finalización de la cobertura de la beca | Fecha | MM/DD/AAAA |
| Ciudad de Origen | Descripción de la ciudad de nacimiento del becario | Categórico | Lista de ciudades del Paraguay |
| Departamento de Origen | Descripción del departamento de nacimiento del becario | Categórico | Lista de departamentos del Paraguay |
| Ciudad de Residencia | Descripción de la ciudad de residencia del becario | Categórico | Lista de ciudades del Paraguay |
| Departamento de Residencia | Descripción del departamento de residencia del becario | Categórico | Lista de departamentos del Paraguay |
| Nivel socioeconómico | Clasificador del nivel socioeconómico del becario | Categórico | 1, 0.5, 0.7, sin dato |
| Tiempo de cobertura | Cantidad de meses de cobertura de la beca | Discreto | 24,48 |
| Contrato Nº | Indica el número de contrato firmado entre el becario y el Ministerio de Hacienda del Paraguay | Discreto | 78/2015 |
| Fecha firma de Contrato | Fecha en que se firmó el contrato entre las partes | Fecha | MM/DD/AAAA |
| Fecha firma de Adenda | Fecha en que se firmó la última Adenda del contrato entre las partes si hubiere | Fecha | MM/DD/AAAA |

#### Dataset: Coberturas de las becas otorgadas
| Atributo | Descripción | Tipo | Valores de ejemplo |
| --- | --- | --- | --- |
| No | Número ordinal del registro en el conjunto de datos | Ordinal | 1,2,3 |
| C.I. | Cédula de identidad del becario | Discreto | 1234567 |
| Nombre y Apellido | Descripción del nombre y apellido del becario | Texto | Alejandra Recalde Carballo |
| Tipo de Beca (según Programa aprobado) | Clasificador de la beca otorgada | Categórico | Doctorado para investigación, Maestría para investigación, Maestría para profesionales, ... |
| Maestria / Doctorado | Descripción del estudio de postgrado a realizar | Texto | PhD Estructura de grupos superficies abelianas, Master in Management, ... |
| Universidad de Destino | Descripción de la Universidad donde se realizan los estudios | Texto | Universidad de Chile, Universidad de Bremen, ... |
| Pais | Descripción de la país de destino del estudio | Categórico | Lista de países del mundo |
| Dept. de Origen | Descripción del departamento de nacimiento del becario | Categórico | Lista de departamentos del Paraguay |
| Total General | Monto en dólares americanos otorgado al becario | Discreto | 82896 |
