# 🏦 Sistema de Auditoría Predictiva: Análisis de Insolvencia mediante Optimización Matemática

Este repositorio presenta el desarrollo de un modelo de **Machine Learning (Regresión Logística)** codificado íntegramente desde cero. El proyecto destaca por la **omisión de librerías de alto nivel (como Scikit-Learn)**, optando por la implementación manual de los fundamentos matemáticos para demostrar un dominio total sobre la arquitectura del algoritmo y la convergencia de datos.

## 🛠️ Perfil del Desarrollador
**Mateo Jáuregui** *Estudiante de Ingeniería Mecánico Eléctrico* Especializado en la resolución de problemas técnicos complejos, optimización de sistemas dinámicos y análisis de datos mediante rigor matemático y físico.

## 🔬 Ingeniería de Funciones (Feature Engineering)
Desde una perspectiva de ingeniería, se realizó una reducción de dimensionalidad pasando de 95 variables originales a un espacio de **5 dimensiones críticas**. Esta selección no fue aleatoria; se basó en el análisis de variables con mayor peso en la estabilidad financiera de un sistema organizacional:

* **ROA (A/C/D):** Eficiencia operativa y rendimiento sobre activos.
* **Índice de Liquidez:** Solvencia de flujo para cubrir pasivos circulantes.
* **Ratio de Endeudamiento:** Evaluación del apalancamiento y riesgo de estructura de capital.
* **Margen Bruto:** Capacidad de retención de valor frente a costos directos.
* **Net Cash Flow:** Vitalidad y liquidez real del sistema bajo análisis.

## ⚙️ Desarrollo del Algoritmo (Cómputo Matemático desde Cero)
El núcleo del proyecto es la implementación manual de la lógica de aprendizaje, garantizando que cada etapa del proceso sea auditable y transparente:

* **Modelado Matemático:** Implementación de la **Función Sigmoide** para el mapeo de la combinación lineal de entradas en un intervalo probabilístico [0, 1].
* **Optimización por Descenso de Gradiente:** Desarrollo manual del algoritmo de optimización iterativa para la minimización de la función de coste.

![image_alt](https://github.com/Spartacus616/IA-Prediccion-Riesgo-Financiero/blob/2f33e6327b43873c335e63b8bb1b212fd3ef3ff3/Grafica%20Costo%20vs%20Iteraciones.png)

* **Hiperparametrización Técnica:**
    * **Iteraciones:** 5,000 ciclos de entrenamiento para asegurar la estabilidad del gradiente.
    * **Inicialización Profesional:** Conforme a las mejores prácticas de la industria y la academia, los parámetros **w (pesos)** y **b (sesgo)** fueron inicializados en **0**. Esto garantiza un punto de partida neutral, evitando sesgos previos y permitiendo que la matemática dicte la dirección del aprendizaje.
* **Independencia Tecnológica:** Se evitó el uso de herramientas como `Sklearn` para demostrar la capacidad de traducir fórmulas matemáticas directamente a código funcional (Python/NumPy).

![image_alt](https://github.com/Spartacus616/IA-Prediccion-Riesgo-Financiero/blob/2f33e6327b43873c335e63b8bb1b212fd3ef3ff3/Fragmento%20del%20C%C3%B3digo%20del%20Descenso%20de%20Gradiente%20regularizado.png)
    
## 📊 Validación de Resultados de Auditoría
El rigor matemático se traduce en resultados precisos. Tras el proceso de optimización, el modelo fue validado con casos de prueba, obteniendo probabilidades de quiebra diferenciadas:

![image_alt](https://github.com/Spartacus616/IA-Prediccion-Riesgo-Financiero/blob/2f33e6327b43873c335e63b8bb1b212fd3ef3ff3/Resultados.png)

1.  **Perfil Saludable:** Probabilidad de **0.009%** (Inexistencia de riesgo).
2.  **Perfil de Alerta:** Probabilidad de **22.08%** (Necesidad de auditoría preventiva).
3.  **Perfil de Insolvencia Crítica:** Probabilidad de **47.43%** (Riesgo de bancarrota detectado).

## 📂 Contenido del Repositorio
* `algoritmo_optimizacion_quiebra`: Notebook con el desarrollo matemático y código fuente.
* `dataset_taiwan_original`: Datos históricos de referencia.
* `dataset_reducido_feature_engineering`: Datos procesados bajo criterios de ingeniería.

## ⚠️ Propiedad Intelectual
© 2026 Mateo Julián Jáuregui Palacín. Todos los derechos reservados.
Este algoritmo es propiedad intelectual del autor. Se prohíbe la reproducción, distribución o uso comercial del código y la metodología sin autorización expresa.
