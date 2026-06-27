1. '0-ingenieria-del-conocimiento.pdf'.
Resumen hecho con notebooklm.google

La Ingeniería de Conocimiento (IC) se define como una rama de la Inteligencia Artificial (IA) dedicada a la adquisición, representación y procesamiento del conocimiento para la construcción de Sistemas Expertos (SE) o Sistemas Basados en el Conocimiento (SBC). Su propósito central es capturar la experiencia de expertos humanos en dominios específicos y complejos —donde la informática convencional falla debido a la falta de estructura o a la imprecisión de los datos— y transformarla en una base de conocimiento inteligible para una computadora.

Los pilares de esta disciplina son el Ingeniero de Conocimiento (ICO), quien actúa como mediador y arquitecto del sistema, y el Experto Humano, fuente del conocimiento especializado. El proceso se articula a través de fases críticas que incluyen la adquisición, formalización, implementación y validación, utilizando diversos esquemas de representación que van desde la lógica simbólica y redes semánticas hasta estructuras de frames (marcos) y árboles de decisión.

1. Conceptos Fundamentales y Actores Clave

Para comprender la Ingeniería de Conocimiento, es preciso definir los elementos que la integran según la perspectiva de la IA:

El Conocimiento y sus Tipos

El conocimiento se interpreta como la combinación de estructuras de datos y procedimientos interpretativos que modelan el mundo real. Se clasifica en tres tipos principales:

* Declarativo: Se expresa mediante hechos, atributos de objetos o conceptos y sus relaciones.
* Procedural: Conjunto de reglas basadas en conocimiento que el experto emplea para resolver problemas.
* Metaconocimiento: Conocimiento sobre el propio conocimiento y las capacidades de razonamiento del sistema (operación del motor de inferencia).

Roles Principales

* Ingeniero de Conocimiento (ICO): Especialista informático que extrae el conocimiento del experto, conoce las herramientas de desarrollo y posee nociones de psicología para interpretar las manifestaciones del experto.
* Experto Humano: Persona de reconocido prestigio que aporta su experiencia y saber hacer para ser integrados en el sistema.
* Usuario: Persona final que utilizará el sistema; su nivel de conocimiento debe ser considerado durante el desarrollo.

2. El Proceso de la Ingeniería de Conocimiento

La IC puede definirse estrictamente como el ciclo de adquisición, representación, validación, inferenciación, explicación y mantenimiento del conocimiento. Su importancia radica en su capacidad para manejar dominios donde la información puede ser inconsistente, incompleta o mal estructurada.

Procesos Fundamentales

1. Adquisición del Conocimiento (AC): Extracción de información de fuentes humanas o documentales.
2. Representación del Conocimiento (KR): Codificación del conocimiento en una forma que la máquina pueda procesar.
3. Base de Conocimiento: Repositorio donde la información se almacena, comúnmente mediante reglas de producción (implicaciones lógicas de causa-efecto).
4. Validación: Asegurar que el sistema actúe con la misma fidelidad que el experto humano.
5. Inferencia: Diseño del software que permite a la computadora realizar deducciones.
6. Explicación y Justificación: Capacidad del sistema para mostrar al usuario el porqué de sus conclusiones.

3. Adquisición del Conocimiento (AC)

Este proceso busca comprender cómo un individuo realiza una actividad para automatizarla. Se nutre de dos tipos de fuentes:

* Estáticas (Secundarias): Conocimiento tangible e invariable (libros, revistas, artículos).
* Dinámicas (Primarias): Basadas en la experiencia cambiante del Experto Humano.

Etapas de la Adquisición

Etapa	Descripción
Identificación	Se reconoce el problema, se divide en subproblemas y se identifican los recursos necesarios.
Entendimiento	Se determinan los conceptos clave y las relaciones. Se decide cómo se representará la información.
Formalización	Se organiza el conocimiento en la Base de Conocimiento. Es una etapa crítica de interacción con el experto.
Implementación	Programación del conocimiento en la computadora y desarrollo de un prototipo.
Pruebas	El ICO evalúa el sistema con ejemplos y el experto humano valida los resultados (depuración).

4. Esquemas de Representación del Conocimiento (KR)

La elección del esquema depende del problema y los métodos de inferencia. Una representación ideal debe ser sencilla, fácil de modificar, transparente (para detectar inconsistencias), independiente y relacional.

Principales Modelos de Representación

* Reglas de Lógica Simbólica:
  * Lógica Proposicional: Evalúa la verdad o falsedad de hechos usando conectivos (Ʌ, V, ~, →, ≡). Utiliza mecanismos como el Modus Ponendo Ponens (afirmar afirmando) y el Modus Tollendo Tollens (negar negando).
  * Lógica de Predicados: Sistema más sofisticado con sintaxis propia que utiliza constantes, variables, funciones, predicados y cuantificadores (existencial y universal).
* Redes Semánticas: Representaciones gráficas de objetos y sus relaciones mediante nodos (elementos) y enlaces (relaciones como "ES-UN" o "ES-SUBCONJUNTO").
* Frames (Marcos) o Slots: Estructuras de datos para representar objetos o situaciones típicas. Se dividen en slots (ranuras/atributos) y facets (facetas). Permiten la herencia de valores jerárquicos y combinan aspectos declarativos y procedimentales.
* Árboles de Decisión: Representan espacios de búsqueda de soluciones donde los nodos son metas y las ramas son decisiones o resultados.
* Gráficos Conceptuales: Expresan conocimientos mediante relaciones secuenciales de precedencia o jerarquía, generalmente de causa-efecto.

5. Métodos y Técnicas de Obtención de Conocimiento

Existen tres metodologías principales para extraer el saber del experto:

A. Métodos Manuales

Basados en la interacción directa.

* Entrevistas: Pueden ser estructuradas (preguntas específicas y sistemáticas), semiestructuradas (puntos clave con flexibilidad) o no estructuradas (informales, para obtener una estructura básica).
* Análisis de Protocolo: Seguimiento de la "trayectoria de pensamiento" del experto mientras resuelve un problema.
* Otras técnicas: Lluvia de ideas, casos de análisis, mapas conceptuales, prototipos y escalamiento multidimensional.

B. Métodos Semiautomatizados

* Soporte al Experto: Herramientas como el Análisis de Rejilla (Repertory Grid Analysis), basado en la Teoría de Construcción Personal de Kelly, que ayuda al experto a estructurar su razonamiento cuando no puede expresarlo claramente.
* Soporte al Ingeniero: Editores de conocimiento, interfaces amigables y herramientas de documentación.

C. Métodos Automatizados

Buscan minimizar o eliminar la necesidad del ICO y del experto mediante:

* Reglas de Inducción: Algoritmos (como el ID3) que convierten matrices de atributos en árboles de decisión o reglas. Es ideal para problemas complejos y determinísticos, aunque puede generar reglas difíciles de interpretar para humanos.
* Aprendizaje Automatizado: Programas heurísticos que permiten a las computadoras aprender directamente de la experiencia y los datos almacenados.

2. 'C-sistemasExpertosBasadosEnReglas.pdf'
Resumen hecho con notebooklm.google

Resumen 

Los sistemas basados en reglas (SBR) constituyen la metodología más sencilla y eficiente para abordar situaciones complejas de naturaleza determinista, como sistemas de control de tráfico, seguridad y transacciones bancarias. Estos sistemas operan mediante una base de conocimiento estática compuesta por reglas y una memoria de trabajo dinámica que almacena hechos. El motor de inferencia es el núcleo operativo que, aplicando lógica clásica y estrategias como el encadenamiento hacia adelante o hacia atrás, extrae conclusiones a partir de las premisas dadas. El éxito de estos sistemas depende críticamente del control de coherencia —para evitar contradicciones entre reglas y hechos— y de la capacidad de proporcionar explicaciones sobre las conclusiones alcanzadas. Si bien son herramientas robustas en entornos deterministas, su limitación reside en la incapacidad de la lógica clásica para gestionar la incertidumbre, lo que posiciona a los sistemas probabilísticos como su generalización necesaria.

1. Arquitectura de la Base de Conocimiento

El funcionamiento de un sistema experto basado en reglas se sustenta en la interacción de dos componentes principales:

* Hechos: Representan el conocimiento declarativo sobre una situación particular. Son de naturaleza dinámica y temporal, almacenándose en la memoria de trabajo del sistema.
* Reglas: Constituyen el conocimiento permanente y estático. Definen las relaciones generales entre objetos y gobiernan cómo se procesa la información. Se almacenan en la base de conocimiento.

Definición y Componentes de una Regla

Una regla es una afirmación lógica que relaciona dos o más objetos mediante la estructura: "Si premisa, entonces conclusión".

* Premisa o Antecedente: Expresión lógica (simple o compuesta) que utiliza palabras clave como si y operadores lógicos (y, o, no).
* Conclusión o Consecuente: Expresión lógica que sigue a la palabra clave entonces.

Restricciones y Sustitución de Reglas

Para facilitar la programación, algunos sistemas imponen restricciones, como prohibir el operador o en la premisa o limitar las conclusiones a expresiones simples. Sin embargo, esto no implica pérdida de generalidad gracias a la sustitución de reglas, donde una regla compleja se reemplaza por un conjunto equivalente de reglas simples.

Regla Original	Reglas Equivalentes
Si A o B, entonces C	Si A, entonces C; Si B, entonces C
Si A, entonces B y C	Si A, entonces B; Si A, entonces C
Si (A o B) y C, entonces D	Si A y C, entonces D; Si B y C, entonces D

2. El Motor de Inferencia y sus Reglas

El motor de inferencia es el encargado de procesar hechos y reglas para obtener conclusiones siguiendo tres pasos básicos:

1. Reconocimiento de patrones: Compara los elementos de la memoria de trabajo con las reglas.
2. Resolución de conflictos: Selecciona la regla adecuada cuando hay varias opciones ejecutables.
3. Ejecución: Aplica la regla, generando cambios en la memoria de trabajo.

Reglas de Inferencia Fundamentales

Para obtener conclusiones, el motor utiliza principalmente dos mecanismos complementarios:

* Modus Ponens: Se mueve hacia adelante, de la premisa a la conclusión. Si se sabe que "A es cierto" y la regla es "Si A, entonces B", se concluye que "B es cierto".
* Modus Tollens: Se mueve hacia atrás, de la conclusión a la premisa. Si se sabe que "B es falso" y la regla es "Si A, entonces B", se concluye que "A es falso".

El uso combinado de ambas estrategias permite una base de conocimiento más potente que su aplicación por separado, permitiendo derivar información incluso cuando los datos son incompletos o negativos.

Mecanismo de Resolución

Se utiliza para obtener conclusiones compuestas basadas en dos o más reglas. El proceso implica sustituir las reglas por expresiones lógicas equivalentes, combinarlas y simplificarlas para derivar la conclusión final. Bajo la hipótesis del mundo cerrado, si algo no puede demostrarse como cierto, el sistema lo asume como falso.

3. Estrategias de Encadenamiento

Existen dos enfoques principales para gestionar el flujo de inferencia:

Encadenamiento hacia adelante (Encadenamiento de reglas)

Se utiliza cuando los hechos iniciales son conocidos y se buscan todas las conclusiones posibles.

* Proceso: Se asignan valores a los objetos conocidos, se ejecutan las reglas cuyas premisas se cumplen, se añaden las nuevas conclusiones como hechos y se repite el ciclo hasta que no se puedan obtener más datos.
* Utilidad: Ideal para diagnósticos donde los síntomas son el punto de partida para identificar una enfermedad.

Encadenamiento hacia atrás (Orientado a un objetivo)

El usuario selecciona una variable objetivo y el sistema navega a través de las reglas buscando una conclusión para dicho nodo.

* Proceso: Si la información existente es insuficiente, el algoritmo solicita al usuario datos específicos sobre los elementos relevantes para alcanzar el objetivo.
* Utilidad: Eficiente cuando se desea verificar una hipótesis específica (objetivo) buscando los hechos que la sustentan.

Compilación de Reglas

Cuando tanto los datos como los objetivos están predefinidos, las reglas pueden compilarse en ecuaciones objetivo. Esto permite expresar los objetivos directamente en función de los datos de entrada, agilizando la obtención de resultados.

4. Control de Coherencia y Consistencia

Un sistema experto debe garantizar que el conocimiento introducido no sea contradictorio para evitar conclusiones absurdas.

* Coherencia de Reglas: Un conjunto de reglas es coherente si existe al menos una combinación de valores de objetos que no produzca contradicciones. El sistema debe verificar la consistencia de cada regla nueva antes de incorporarla a la base de conocimiento.
* Coherencia de Hechos: El sistema no debe aceptar evidencias que contradigan las reglas o los hechos ya existentes.
* Valores no factibles: Son aquellos valores que, de ser asignados, producirían contradicciones lógicas. El subsistema de control de coherencia debe eliminar estos valores de las opciones disponibles para el usuario en tiempo real.

5. Explicación de Conclusiones y Aplicaciones

Una característica distintiva de los SBR es su capacidad para proporcionar una justificación lógica. Dado que el motor de inferencia sabe exactamente qué regla utilizó para derivar cada hecho, el sistema puede presentar al usuario una lista de los hechos iniciales y la secuencia de reglas ejecutadas.

Ejemplo de Aplicación: Control de Tráfico Ferroviario

El documento detalla un sistema para evitar colisiones en un trazado de cinco vías (S1-S5) con 14 señales (U1-U8, L1-L6). Las reglas definen:

* Prioridades de salida para evitar conflictos entre vías (S1 vs S2).
* Prevención de entrada en vías ocupadas (S1 ocupada → U2 en rojo).
* Coordinación de señales opuestas para evitar que ambas estén en verde simultáneamente.

Limitaciones: La Gestión de la Incertidumbre

La lógica clásica utilizada en estos sistemas es puramente determinista. En casos reales, como el diagnóstico médico, una premisa no siempre conduce con certeza absoluta a una conclusión. Esta limitación requiere la evolución hacia sistemas expertos probabilísticos, que extienden los SBR incorporando medidas de incertidumbre para modelar situaciones donde las evidencias no son definitivas.

