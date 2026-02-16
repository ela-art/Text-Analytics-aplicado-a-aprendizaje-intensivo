Text Analytics aplicado a aprendizaje intensivo

Ela Ruiz González

🔎 Overview

Proyecto de análisis exploratorio aplicado a texto no estructurado generado durante un bootcamp intensivo.

El objetivo es transformar entradas de diario en métricas cuantificables y evaluar si la carga formativa presenta relación observable con indicadores emocionales.

🎯 Objetivo

Analizar si la intensidad asociada a estudio y exámenes muestra relación con patrones emocionales medibles derivados del texto.

📁 Dataset

16 registros diarios

14 variables estructuradas

0 duplicados

Tipado consistente (datetime64, int64)

Nulos residuales controlados

Variables clave

Conteo de palabras

Keywords emocionales (ansiedad, frustración, miedo, cansancio, confianza, felicidad)

Keywords de actividad (estudio, examen)

Totales positivos/negativos

Índice emocional neto

Ratios normalizados por longitud de texto

⚙️ Metodología

Limpieza y normalización del texto

Extracción manual de keywords emocionales

Feature engineering (totales, ratios e índice neto)

Agregación temporal (diaria y mensual)

Análisis exploratorio y evaluación visual

Enfoque estrictamente exploratorio debido al tamaño muestral reducido.

📈 Hallazgos

Predominio de emociones asociadas a carga cognitiva (ansiedad, cansancio, frustración).

Emociones positivas presentes de forma puntual.

No se observa correlación lineal fuerte entre intensidad diaria y estado emocional neto.

La agregación mensual sugiere fases diferenciadas dentro del proceso formativo.

⚠️ Limitaciones

Tamaño muestral reducido (N=16)

Diccionario emocional basado en matching literal

No se aplicaron técnicas avanzadas de NLP ni modelos inferenciales

💡 Valor profesional

Pipeline completo: texto → features → métricas → visualización

Diseño de indicadores normalizados

Análisis crítico de correlación vs causalidad

Aplicación práctica de text analytics sobre datos reales

🚀 Aplicabilidad a negocio

El framework puede aplicarse en formación, RRHH o producto digital para:

Detectar señales tempranas de sobrecarga

Analizar feedback cualitativo a escala

Evaluar impacto emocional de programas formativos

Diseñar intervenciones basadas en datos

Ela Ruiz González
Data Analyst
Python · SQL · Pandas · Visualización · Text Analytics