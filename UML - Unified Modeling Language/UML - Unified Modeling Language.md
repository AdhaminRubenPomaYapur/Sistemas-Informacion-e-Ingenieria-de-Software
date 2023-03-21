# UML - LENGUAJE UNIFICADO DE MODELADO

## Objetivos
> - Explicar el proposito de modelamiento de negocio
> - Aprender un perfil de UML para modelamiento de negocio
> - Entender las vistas de negocio y los patrones resueltos

## Que es un negocio
> Ocupacion que realizan las personas con fines lucrativos.
---
## Que es un modelo
> Un modelo es una simplificacion de la realidad.
>
> Un modelo captura una vista de un sistema del mundo real.
>
> Funciones:
> - Comunicar la estructura de un sistema complejo
> - Especificar el comportamiento deseado del sistema
> - Comprender mejor lo que se esta construyendo
> - Descubrir oportunidades de simplificacion y reutilizacion

### Proposito de los modelos
> - Proveer el Blueprint(diseño y anteproyecto)
> - Proveer plan detallado y vista de alto nivel
### Tipos de modelo
> - Estructurales (estaticos)
> - De Comportamiento (dinamicos)
### Principios de modelamiento
> - Seleccion del Modelo
> - Diferentes Niveles de Precision
> - Tienen relacion clara con la realidad
> - Varios Modelos complementarios

### Tipos de modelados de negocio
> - BPMN Bussiness Process Modeling Notation
> - UML (Unified Modeling Language)
>> - Provee orientacion a la Arquitectura - conjunto de vistas
---
## Que es UML
> Un lenguaje de proposito general para el modelado orientado a objetos.
> Diseñado para visualizar, especificar, construir y documentar software.
> - Combina notaciones como:
>> - Modelado Orientado a Objetos
>> - Modelado de Datos
>> - Modelado de Componentes
>> - Modelado de Flujos de Trabajo (WorkFlows)
### Ventajas
> - El 80% de los problemas puede modelarse utilizando el 20% de UML.
### Desventajas
> - Falta de integracion con otras tecnicas
>> - Diseño de interfaces de usuario
>> - patrones de diseño
>> - documentacion
> - No es una metodologia es una notacion
> - No es libre ambiguedades
> - No se puede usar UML, para señalar que un objeto es persistente o remoto

# Que es un diagrama
> Representacion grafica de una coleccion de elementos de modelado, a menudo dibujado como un grafo con vertices conectados.
## Organizacion de los modelos
> ## 4+1 Vistas de Kruchten (1995)
> - Vista logica
> - Vista de procesos
> - Vista de realizacion
> - Vista de distribucion
> - Vista de los Casos de Uso
>
> ## Vistas de UML: Arquitectura 4 + 1 (5 Vistas y 9 Diagramas)
> - Vista Estructural
> - Vista Comportamiento
> - Vista Ambiente
> - Vista Implementacion
> - Vista Usuario
>
> ## Diagramas UML v1.0
> - Diagrama de Casos de Uso
> - Diagrama de Objetos
> - Diagrama de Clases
> - Diagramas de Comportamiento
>> - Diagrama de Estados
>> - Diagrama de Actividad
> - Diagramas de Interacion
>> - Diagrama de Secuencia
>> - Diagrama de Colaboracion
> - Diagramas de Implementacion
>> - Diagrama de Componentes
>> - Diagrama de Despliegue
>
> ## Diagramas UML v2.5
> - Estructurales (7)
>> - Diagrama de Clases
>> - Diagrama de Componentes
>> - Diagrama de Despliegue
>> - Diagrama de Objetos
>> - Diagrama de Paquetes
>> - Diagrama de Perfiles
>> - Diagrama de Estructura Compuesta
> - Comportamiento (7)
>> - Diagrama de Actividades
>> - Diagrama de Casos de Uso
>> - Diagrama de Maquina de Estados
>> - Diagramas de Interacion
>>> - Diagrama de Secuencia
>>> - Diagrama de Comunicacion
>>> - Diagrama de Tiempos
>>> - Diagrama Global de Interacciones
---

## Paquetes en UML
> - Cada paquete corresponde a un submodelo (Subsistema) del modelo (sistema)
> - Cada elemento pertenece a un solo paquete (add package)
> - Una clase de paquete aparece en otro a traves de la dependencia entre paquetes.
> ![Diagrama!](/assets/Diagrama-Paquetes.PNG)
---
## Aspectos Fisico del Sistema
> - Representacion de aspectos fisicos del sistema mediante:
>> - Diagrama de Componentes
>> - Diagrama de Despliegue
> ![Diagrama!](/assets/Diagrama-AspectoFisico-Combination.PNG)
> ![Diagrama!](/assets/Niveles-De-Descomposicion-Modular.PNG)
---
## Modelo de Procesos
> - Es una extension del diagrama de actividades para un modelo de procesos de negocios.
> ## Muestra:
> - Metas
> - Entradas
> - Salidas
> - Eventos
> - Informacion involucrada en el proceso.
> ## Tiene enfasis en como se hace el trabajo.
> ![Diagrama!](/assets/Modelado-Procesos.PNG)
---
## Modelado de la arquitectura
> ## Vista de Casos de Uso
> - Describe los requisitos del sistema tal como es percibido por los usuarios finales utilizando los siguientes diagramas:
>> - Diagrama de Casos de uso
>> - Diagramas de Interacion
> ## Vista de Diseño
> - Representa el espacio del problema y el espacio de solucion utilizando los siguientes diagramas:
>> - Diagrama de clases
>> - Diagrama de objetos
>> - Diagramas de Interacion
> ## Vista del Proceso
> - Modela los procesos e hilos utilizando los siguientes diagramas:
>> - Diagrama de clases
>> - Diagrama de objetos
>> - Diagramas de Interacion
> ## Vista de Implementacion
> - Modela los componentes y archivos que se utilizan para ensamblar y hacer disponible el sistema fisico.
>> - Diagrama de componentes (estatico)
>> - Diagramas de Interacion (dinamico)
> ## Vista de Despliegue
> - Modela los nodos de la topologia de hardware
>> -  Diagrama de despliegue (estatico)
>> -  Diagramas de Interacion (dinamico)