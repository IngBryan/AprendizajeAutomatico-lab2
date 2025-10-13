# Curso de Aprendizaje Automatico
## Laboratorio 2 — El InternAAuta

### Descripción del Problema

Este laboratorio aborda el problema **Frozen Lake** de Gymnasium (desarrollado por OpenAI), aplicando métodos de aprendizaje por refuerzos y redes neuronales.

**Frozen Lake** consiste en cruzar un lago congelado desde una posición inicial hasta una final, evitando caer en los agujeros. Debido a que el lago es resbaloso, el jugador no siempre logra moverse en la dirección deseada, lo que introduce incertidumbre en el entorno.

### Objetivos

- Aplicar métodos de aprendizaje por refuerzos y redes neuronales a un problema práctico
- Analizar los resultados obtenidos mediante diferentes enfoques
- Implementar y comparar dos algoritmos distintos de aprendizaje por refuerzos

### Algoritmos a Implementar

#### 1. Q-Learning Tabular
- Aplicación a la versión no determinista del entorno
- Meta: Obtener un agente con éxito mayor al 50% de las ejecuciones

#### 2. Deep Q-Network (DQN)
- Aplicación a la versión no determinista del entorno
- Meta: Obtener un agente con éxito mayor al 50% de las ejecuciones

### Entregables

1. **Código completo**: Implementación de punta a punta en el cuaderno Jupyter (`FrozenGymQLAndDQN_Tarea.ipynb`)
2. **Informe técnico**: Artículo en formato IEEE (máx. 5 páginas) que incluya:
   - Descripción de las soluciones implementadas
   - Proceso de selección de parámetros (calibración)
   - Evaluación del proceso de aprendizaje y desempeño final
   - Análisis de las políticas obtenidas
   - Contraste entre ambas soluciones (ventajas y desventajas)

### Bonificación
Se otorgará bonificación a los grupos que implementen agentes que solucionen la variante **8x8** del entorno.

**Fecha límite de entrega**: Lunes 27 de Octubre (inclusive)

---

## Estructura del Proyecto

```
AprendizajeAutomatico-lab2/
├── FrozenGymQLAndDQN_Tarea.ipynb  # Cuaderno principal con implementaciones
├── README.md                       # Este archivo
├── requirements.txt                # Dependencias del proyecto
└── docs/
    └── letra.md                   # Enunciado completo de la tarea
```

### Archivos Principales

- **`FrozenGymQLAndDQN_Tarea.ipynb`**: Cuaderno Jupyter que contiene toda la implementación requerida, incluyendo:
  - Familiarización con el entorno Frozen Lake
  - Implementación de Q-Learning Tabular
  - Implementación de Deep Q-Network (DQN)
  - Experimentos y análisis de resultados

---

## Información Adicional

### Recursos Útiles
- **Gymnasium Frozen Lake**: Documentación oficial del entorno
- **Q-Learning**: Algoritmo de aprendizaje por refuerzos tabular
- **DQN**: Deep Q-Network para espacios de estados grandes
- **Plantillas IEEE**: https://www.ieee.org/conferences/publishing/templates

### Notas de Implementación
- Se permite el uso de herramientas de IA para el desarrollo del código (Cursor, Copilot, ChatGPT, etc.)
- **NO** se permite el uso de IA para la redacción del informe (solo para corrección gramatical y estilo)
- La solución debe ser autocontenida dentro del cuaderno Jupyter

### Criterios de Éxito
- **Q-Learning Tabular**: Tasa de éxito > 50% en el entorno no determinista
- **DQN**: Tasa de éxito > 50% en el entorno no determinista
- **Bonus**: Implementar solución para la variante 8x8 del entorno

---

## Instrucciones de Instalación

### Mediante pyenv en Linux (Ubuntu)

Para instalar y utilizar pyenv: https://github.com/pyenv/pyenv

1. Instalar Python 3.13.6 usando pyenv:
```bash
pyenv install 3.13.6
```

2. Crear un entorno virtual con la versión de Python instalada:
```bash
pyenv virtualenv 3.13.6 ml_project_env
```

3. Activar el entorno virtual:
```bash
pyenv activate ml_project_env
```

4. Instalar paquetes requeridos:
```bash
pip install -r requirements.txt
```

### Desarrollo

Asegúrate de activar siempre el entorno virtual antes de trabajar en el proyecto:
```bash
pyenv activate ml_project_env
```
