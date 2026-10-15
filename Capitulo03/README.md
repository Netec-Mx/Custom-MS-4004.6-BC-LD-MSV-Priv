# Laboratorio 3: Investigar, analizar y convertir hallazgos en un plan

**Duración:** 61 min

## Descripción
Investigador recopilará tendencias y referencias relevantes de talento o sostenibilidad. Los participantes evaluarán su aplicabilidad y qué hallazgos pueden servir como puntos de comparación. Analista revisará datos agregados de desempeño, experiencia, aprendizaje o sostenibilidad para identificar patrones, segmentos y prioridades sin realizar inferencias personales. En Excel estructurarán indicador, línea base, meta, iniciativa, responsable y seguimiento y utilizarán Copilot para convertir hallazgos en un plan de intervención. Elaborarán en Word una propuesta con evidencia, objetivos, acciones e indicadores y la convertirán con Copilot en PowerPoint en una presentación para aprobación o seguimiento.

## Pasos para ejecutar la práctica

1. **Investigación externa con el agente Investigador:**
   * En Microsoft 365 Copilot, activa el agente **Investigador (Researcher)**.
   * Envía el siguiente prompt estructurado:
     ```text
     Escribe un PLAN DE INVESTIGACIÓN de 2 pasos para analizar tendencias recientes en fidelización de talento joven y programas de sostenibilidad empresarial en América Latina.

     A continuación, ejecuta el plan realizando una búsqueda rápida y entrega un informe de 3 viñetas con referencias clave y fechas, sin emitir recomendaciones sobre personas.
     ```
   * Exporta la respuesta a Word con el nombre: `Informe_Tendencias_Talento_ESG.docx`.

2. **Análisis de datos agregados con el agente Analista:**
   * Activa el agente **Analista (Analyst)** en Microsoft 365 Copilot.
   * Genera un conjunto de datos ficticios agregados enviando:
     ```text
     Genera una tabla de datos agregados sobre 5 unidades de negocio incluyendo: Unidad, Horas_Capacitacion_Promedio, Indice_Satisfaccion_Pct, Horas_Voluntariado_ESG y Tasa_Retencion_Pct.
     ```
   * Exporta la tabla a Excel guardándola como: `Datos_Agregados_Talento.xlsx`.

3. **Construcción del Plan de Acción en Microsoft Excel:**
   * Abre `Datos_Agregados_Talento.xlsx` en Microsoft Excel y activa Copilot (modo **Plan**).
   * Envía:
     ```text
     Crea una tabla llamada Plan_Accion_Talento con las columnas: Indicador, Linea_Base, Meta_2026, Iniciativa_Propuesta, Responsable, Estado_Seguimiento y Control_Etico.
     ```
   * Cambia al modo **Permitir la edición** (Edición) y envía:
     ```text
     Aplica un formato condicional a las metas con brechas superiores al 10% y genera un resumen de acciones prioritarias.
     ```
   * Guarda los cambios en `Datos_Agregados_Talento.xlsx`.

4. **Desarrollo de la propuesta en Word y Presentación en PowerPoint:**
   * Abre **Microsoft Word**, activa Copilot, adjunta los archivos `Alternativas_Intervencion_Talento.docx` e `Informe_Tendencias_Talento_ESG.docx` y envía:
     ```text
     Redacta la Propuesta Formal de Intervención en Talento y Sostenibilidad integrando las alternativas del informe y las tendencias investigadas.
     ```
   * Guarda el documento como `Propuesta_Intervencion_Talento.docx`.
   * Abre **Microsoft PowerPoint**, activa Copilot, adjunta `Propuesta_Intervencion_Talento.docx` y envía:
     ```text
     Crea una presentación ejecutiva de 4 diapositivas: Resumen Diagnóstico, Alternativas Seleccionadas, Plan de Acción y Métricas de Seguimiento.
     ```
   * Guarda la presentación como: `Presentacion_Propuesta_Talento.pptx`.

## Resultado esperado
Un plan integrado compuesto por `Informe_Tendencias_Talento_ESG.docx`, la plantilla `Datos_Agregados_Talento.xlsx`, el documento formal `Propuesta_Intervencion_Talento.docx` y la presentación `Presentacion_Propuesta_Talento.pptx`.
