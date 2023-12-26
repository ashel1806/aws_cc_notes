# AWS Well-Architected Framework

AWS Well-Architected Framework es un marco de trabajo que permite a los arquitectos, desarrolladores y usuarios, crear una buena arquitectura dentro de AWS, es decir, ayuda a crear una infraestructura segura de alto rendimiento, resistente y eficiente para crear sus aplicaciones. Este marco de trabajo se compone por seis pilares: excelencia operativa, seguridad, fiabilidad, eficiencia del rendimiento, optimización de costos, y sostenibilidad.

Existe una herramienta en AWS llamada AWS Well-Architected Tool, que nos ayuda a evaluar la infraestructura que deseamos implementar y ver si se alinea con los seis pilares de este marco de trabajo

## Excelencia operativa
Este pilar se refiera a la capacidad de ejecutar y supervisar sistemas para ofrecer valor empresarial y mejorar continuamente los procesos y procedimientos de soporte.

**Principios de diseño:**
- Realización de operaciones como código
- Anotación de documentación
- Anticipación a errores
- Cambios pequeños y reversibles

**Ejemplo**: automatizar cambios con pipelines de DevOps  o automatizar la respuesta a eventos de las operaciones diarias

## Seguridad
Capacidad de proteger la información, los sistemas y los activos, al mismo tiempo que se otorga valor empresarial mediante evaluaciones de riesgo y estrategias de mitigación

**Prácticas recomendadas:**
- Automatizar las prácticas recomendadas de seguridad siempre que sea posible
- Asegurar todas las capas
- Proteger los datos en tránsito y en reposo

**Principios de diseño:**

**Ejemplo:** cuando se comprueba la integridad de sus datos mediante el uso de cifrado en tránsito y en reposo.

## Fiabilidad
Capacidad de un sistema para:
- Recuperarse de las interrupciones de infraestructura o del servicio
- Adquirir recursos de cómputo de forma dinámica para satisfacer la demanda
- Mitigar interrupciones como configuraciones erróneas o problemas transitorios de red

Este pilar también incluye pruebas de procedimientos de recuperación, escalado horizontal para aumentar la disponibilidad y recuperación automática de errores.

**Prácticas recomendadas:**

**Principios de diseño:**

**Ejemplo:** Recuperación de una interrupción en una instancia de Amazon EC2.

## Eficiencia del rendimiento
Capacidad de utilizar los recursos de cómputo de forma eficiente para satisfacer los requisitos del sistema y mantener esa eficiencia a medida que la demanda cambia y la tecnología evoluciona. La evaluación de la eficiencia del rendimiento incluye la posibilidad de experimentar con mayor frecuencia, de utilizar arquitecturas sin servidor y de diseñar sistemas para lograr alcance global en cuestión de minutos.

**Prácticas recomendadas:**

**Principios de diseño:**

**Ejemplo:** Usar el tipo y tamaño correctos en instancias de Amazon EC2 según los requisitos de carga de trabajo y de memoria. También abarca la toma de decisiones informadas  y el mantenimiento de la eficiencia  a medida que evolucionan las necesidades del negocio.

## Optimización de costos
Capacidad de ejecutar sistemas para ofrecer valor empresarial al precio más bajo. La optimización de costos incluye la adopción de un modelo de consumo, el análisis y la atribución de gastos, y el uso de **servicios administrados** para reducir el costo de propiedad

**Prácticas recomendadas:**

**Principios de diseño:**

**Ejemplo:** Comprobar si se ha sobrestimado el tamaño de una instancia de Amazon EC2  o identificando recursos aprovisionados pero sin utilizar
## Sostenibilidad
Este pilar fue agregado en diciembre del 2021. Hace referencia a la capacidad de mejorar continuamente los impactos de sostenibilidad con la reducción del consumo de energía y el aumento de la eficiencia en todos los componentes de una carga de trabajo, y maximizar los beneficios de los recursos aprovisionados y minimizar los recursos totales requeridos.

**Prácticas recomendadas:**
- Comprenda su impacto
- Establezca metas de sostenibilidad
- Maximice la utilización
- Anticipe y adopte ofertas nuevas y eficientes de hardware y software
- Utilice servicios administrados
- Reduzca el impacto de la distribución de sus cargas de trabajo de la nube.

**Principios de diseño:**


**Ejemplo:**