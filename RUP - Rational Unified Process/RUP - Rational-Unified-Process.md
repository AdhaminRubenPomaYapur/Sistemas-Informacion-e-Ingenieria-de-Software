# ***Introduccion a RUP : Introduccion a RUP Requisitos.***
> ## ***Concepto:***
>> Conjunto de actividades necesarias para transformar los requisitos de un usuario en un sistema de software. Es un conjunto de metodologias adaptables al conexto y necesidades de cada organizacion.
>>
>> Dirigido por casos de uso, centrado en la arquitectura y es iterativo e incremental.
> ## ***Principios de Desarrollo:***
>> Esta basado en 6 principios clave los cuales son:
>>> ### ***Adaptar el proceso:***
>>> - El proceso debe adaptarse a las necesidades del cliente tomando en cuenta lo siguiente:
>>>> - Las caracteristicas del proyecto.
>>>> - El tamaño del mismo.
>>>> - Condiciones para el alcance del proyecto.
>>> ### ***Equilibrar prioridades:***
>>> - Los requisitos pueden ser diferentes, contradictorios o disputarse recursos ilimitados. Debe poder encontrarse un punto de equilibrio.
>>> ### ***Demostrar valor iterativamente:***
>>> - Los proyectos se entregan en modo de etapas iteradas. En cada iteracion se analiza lo siguiente:
>>>> - Opinion de los inversores.
>>>> - Estabilidad.
>>>> - Calidad del producto.
>>>> - Refinamiento de la direccion del proyecto.
>>> ### ***Colaboracion entre equipos:***
>>> - Tener una comunicacion fluida para coordinar requisitos, desarrollo, evaluaciones, planes, resultados.
>>> ### ***Enfocarse en la calidad:***
>>> - Debe hacerse en todos los aspectos de produccion, es una estrategia de desarrollo de software.
>>> ### ***Elevar el nivel de abstraccion:***
>>> - Este principio dominante motiva el uso de conceptos reutilizables tales como patrones de diseño, lenguajes 4GL o esquemas (FrameWorks).
>>
> ## ***Ciclo de Vida:***
>> - Es una implementacion del desarrollo en espiral.
>> - Divide el proceso en 4 fases.
>> - Las primeras iteraciones (Fase Inicio y Elaboracion) esta enfocado en:
>>> - Comprension del problema y tecnologia a usar.
>>> - Delimitacion del ambito del proyecto.
>>> - Eliminacion de riesgos criticos.
>>> - Establecimiento de linea base de la arquitectura.
>> - En la fase inicio hace enfasis en actividades de modelado de negocio y requisito.
>> - En la fase de elaboracion se enfoca en:
>>> - baseline de la arquitectura.
>>> - Flujos de trabajo (Requisitos).
>>> - Modelo de negocios (Refinamiento).
>>> - Analisis.
>>> - Diseño.
>> - En la fase de construccion se lleva a cabo la construccion del producto por medio de iteraciones.
>> - En la fase de transicion se pretende garantizar que se tiene un producto preparado para su entrega a los usuarios.
> ## ***Principales Caracteristicas:***
>> - Desarrollo iterativo.
>> - Administracion de requisitos.
>> - Uso de arquitectura basada en componentes.
>> - Control de cambios.
>> - Modelado visual del software.
>> - Verificacion de la calidad del Software.
>> - Implementar las mejores practicas de IS para adaptar a cualquier proyecto.
> ## ***Fases:***
> - Establece oportunidad y alcance.
> - Identifica entidades con los que se trata.
> - Identifica casos de uso.
> ## ***Dos aspectos importantes que establecen las disciplinas:***
> - ## ***Proceso:***
>> - Modelado de negocio.
>> - Requisitos.
>> - Analisis y diseño.
>> - Pruebas.
>> - Despliegue.
> - ## ***Soporte:***
>> - Gestion del cambio y configuraciones.
>> - Gestion del proyecto.
>> - Entorno
> ## ***Fase de Inicio:***
>> Define el alcance, los riesgos y da una vision general de la arquitectura del software, produciendo un plan de fases e iteraciones posteriores.
> ## ***Fase de Elaboracion:***
>> Se selecciona los casos de uso que permiten definir la arquitectura base del sistema y se los desarrolla, se realiza el dominio del problema y la solucion preliminar.
> ## ***Fase de Desarrollo o Construccion:***
>> Completar la funcionalidad del sistema, clarifica los requisitos pendientes, administrar cambios y realizar mejoras al proyecto.
> ## ***Fase de Transicion***
>> Asegurar que este disponible el software para los usuarios finales, ajustar errores y defectos en las pruebas de aceptacion.
>>
>> ![Image](/assets/RUP-Proceso.PNG)
>> ![Image](/assets/Ciclos.PNG)
>> ![Image](/assets/FlujosTrabajoRUP.PNG)
>> ![Image](/assets/Modelos.PNG)
>> ![Image](/assets/Requisitos.PNG)
>>
> ## ***Clasificacion de los casos de uso:***
>> Por su importancia:
>>> - Primario
>>> - Secundario
>>> - Opcional
>>>
>> Por el nivel de detalle:
>>> - Alto nivel
>>> - Expandido
>>>
>> Por el nivel de abstraccion:
>>> - Esencial.
>>> - Real.
>>>
>> ## ***Ejemplo:***
>>> ### ***Caso de uso:***
>>>> - Comprar productos en Efectivo.
>>> ### ***Actores:***
>>>> - Cliente (Iniciador)
>>>> - Cajero
>>> ### ***Proposito:***
>>>> - Capturar una venta y su pago en efectivo.
>>> ### ***Resumen:***
>>>> - Un cliente llega a chequear las cosas a comprar. El cajero registra las cosas y toma el pago en efectivo. El cliente se lleva las cosas.
>>> ### ***Curso Basico:***
>>>> ### ***Accion del actor:***
>>>>> 1. Comienza cuando un cliente llega a la TPDV con cosas a comprar.
>>>>> 2. El cajero identifica el codigo de cada Producto.
>>>>> 4. Al terminar el cajero indica a la TPDV que termino.
>>>>> 4. El cajero indica el total al cliente.
>>>> ### ***Accion del sistema:***
>>>>> 3. Determinar el precio e incorpora a la transaccion actual la informacion. Muestra descripcion y precio del producto.
>>>>> 5. Calcula y presenta total.
>>>>>
>> ## ***Ejemplo2:***
>> ![Image](/assets/CasoDeUso2.PNG)
>> ![Image](/assets/CasoDeUso2-1.PNG)
>> ![Image](/assets/CasoDeUso2-2.PNG)