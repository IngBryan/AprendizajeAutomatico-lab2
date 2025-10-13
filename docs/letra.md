# Aprendizaje Automático Tarea 2

## Tarea 2: El InternAAuta

Este laboratorio tiene por objetivos:
- aplicar métodos de aprendizaje por refuerzos y redes neuronales a un problema,
- analizar los resultados obtenidos.

**Problema**
Abordaremos el problema conocido como Frozen Lake de Gymnasium, un software desarrollado por OpenAI para la evaluación de algoritmos de aprendizaje por refuerzos.

Frozen Lake consta de cruzar un lago congelado, desde una posición inicial hasta una final, sin caer en los agujeros. Debido a que el lago es resbaloso, el jugador no siempre logra moverse en la dirección deseada.

Invitamos a leer las reglas que rigen este entorno en el sitio y utilizar el cuaderno de python adjunto para familiarizarse con el problema, tanto en su versión determinista como no-determinista.

Este problema se encuentra sobre el extremo sencillo del espectro de Gymnasium por ser discreto y pequeño. Fue elegido para minimizar los tiempos de entrenamiento, ya que resolveremos este entorno con dos algoritmos diferentes.

Se deberán implementar dos agentes que resuelvan el problema mediante aprendizaje por refuerzos, descritos a continuación.

1 - Q-Learning Tabular
Aplicaremos Q-Learning tabular a la versión no determinista de entorno.
Buscaremos obtener un agente que haya aprendido una política aceptable, con un éxito mayor al 50% de las ejecuciones.

2 - DQN

Aplicaremos DQN a la versión no determinista de entorno. Buscaremos obtener
un agente que haya aprendido una política aceptable, con un éxito mayor al 50%
de las ejecuciones.

**Entregables**

1. Código escrito para resolver el problema de punta a punta, siguiendo lo pautado en el cuaderno de python entregado^1. El cuaderno también debe contener el código y resultado de los experimentos realizados.
2. Informe con las pruebas realizadas y los resultados obtenidos. El informe a entregar es un artículo en formato IEEE^2 de no más de 5 páginas, cubriendo los siguientes puntos:
 a. Descripción de las soluciones implementadas para Q-Learning Tabular y DQN
 b. Descripción del proceso de selección de parámetros (calibración)
 c. Evaluación del proceso de aprendizaje y desempeño final de cada algoritmo
 d. Análisis de la política obtenida para cada algoritmo
 e. Contraste de ambas soluciones, incluyendo ventajas y desventajas de cada una

**Implementación**

- Se pueden utilizar herramientas de IA durante el desarrollo de la solución
    (e.g. Cursor/Codex/CoPilot/ChatGTP). No está permitido utilizar herramientas
    de IA para la redacción del informe. Si es aceptable su uso para la corrección
    gramatical y estilo.
- Se bonificará a los grupos que implementen agentes que solucionen la
    variante “8x8” del entorno.

**Fecha límite de entrega**
Lunes 27 de Octubre (inclusive)

(^2) https://www.ieee.org/conferences/publishing/templates
(^1) file://FrozenGymQLAndDQN_Tarea.ipynb. La solución tiene que ser autocontenida dentro del cuaderno de python
