# Laboratorio 2: Analizar una necesidad y diseñar alternativas de intervención

**Duración:** 28 min

## Descripción
Copilot organizará indicadores, segmentos agregados, antecedentes y restricciones separando hechos, posibles explicaciones y aspectos que requieren validación. Los participantes solicitarán tres alternativas con población objetivo, beneficio esperado, riesgo, dependencia, indicador de éxito y evidencia que faltaría antes de ejecutarlas. Pedirán a Copilot que identifique sesgos posibles, explicaciones alternativas y preguntas que deberían resolverse antes de atribuir causas o priorizar una intervención. Ejecutarán la misma solicitud con dos modelos y evaluarán cuál mantiene mejor la prudencia, la utilidad del análisis y la separación entre evidencia y recomendación.

## Pasos para ejecutar la práctica

1. **Análisis de la situación y alternativas de intervención:**
   * Abre Copilot Chat, adjunta el archivo `Marco_Analisis_Talento_Sostenibilidad.docx` y envía:
     ```text
     Con base en el marco definido en Marco_Analisis_Talento_Sostenibilidad.docx, analiza una situación ficticia donde un segmento agregado registra un descenso del 12% en compromiso y un retraso del 20% en metas de reciclaje corporativo.
     
     Entrega:
     1. Un desglose que separe estrictamente HECHOS OBSERVADOS de POSIBLES EXPLICACIONES.
     2. Tres alternativas de intervención estructuradas con: Población_Objetivo, Beneficio_Esperado, Riesgo, Dependencia, KPI_Exito y Evidencia_Faltante.
     ```

2. **Cuestionamiento de sesgos y comparación de modelos:**
   * En el mismo chat, envía el siguiente prompt para detectar sesgos:
     ```text
     Analiza las 3 alternativas propuestas identificando posibles sesgos de atribución, explicaciones alternativas no contempladas y preguntas de validación antes de ejecutar cualquier acción.
     ```
   * En el selector de modelos de Copilot (si está disponible en el tenant), cambia entre el modelo estándar y el modelo de razonamiento/precisión, reejecuta la solicitud y observa cuál mantiene mayor prudencia analítica.

3. **Exportación de las alternativas a Word:**
   * Selecciona **Exportar a Word** y guarda el documento como: `Alternativas_Intervencion_Talento.docx`.

## Resultado esperado
Un documento guardado como `Alternativas_Intervencion_Talento.docx` con las 3 alternativas de intervención evaluadas bajo un enfoque de prudencia, sesgos y validación de evidencias.
