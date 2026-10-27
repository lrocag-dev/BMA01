# BMA01 – Cálculo Diferencial (2026-2) · Presentaciones por sesión

Presentaciones Beamer (16:9) para cada sesión de 2 horas del dosificado `Dosificado_BMA01-2026-2.pdf`.
Cada archivo incluye: objetivos y plan de la sesión, teoría con ejemplos resueltos, gráficas (TikZ/PGFPlots),
ejercicios propuestos y resumen, además de la estructura didáctica descrita más abajo.

- `bma01.sty`: estilo común (colores, cajas Definición/Teorema/Ejemplo/Observación/Ejercicios, macros como `\sen`, `\ent{x}`, `\sgn`).
- `compilar.sh`: compila todas las sesiones (o las indicadas) y avisa de errores o desbordes.
  Uso: `./compilar.sh` o `./compilar.sh S06-1_derivada_tangente_normal.tex`

| Semana | Sesión 1 | Sesión 2 |
|---|---|---|
| 1 | `S01-1_funciones_generalidades` | `S01-2_funciones_por_partes` |
| 2 | `S02-1_monotonas_periodicas_inyectivas` | `S02-2_hiperbolicas_modelamiento` |
| 3 | `S03-1_limite_punto_acumulacion` | `S03-2_aritmetica_limites_laterales` |
| 4 | `S04-1_asintotas_verticales` | `S04-2_asintotas_horizontales_oblicuas` |
| 5 | `S05-1_continuidad` | `S05-2_supremo_bolzano_weierstrass` |
| 6 | `S06-1_derivada_tangente_normal` | `S06-2_reglas_derivacion_laterales` |
| 7 | `S07-1_rolle_valor_medio` | `S07-2_regla_cadena_implicita` |
| 8 | Examen parcial | |
| 9 | `S09-1_optimizacion` | `S09-2_aproximacion_lineal` |
| 10 | `S10-1_derivadas_inversas` | `S10-2_tasas_cambio_esbozo` |
| 11 | `S11-1_concavidad_inflexion` | `S11-2_regla_lhospital` |
| 12 | `S12-1_lhospital_ejemplos` | `S12-2_polinomio_taylor` |
| 13 | `S13-1_residuo_taylor` | `S13-2_curvas_parametricas` |
| 14 | `S14-1_parametricas_ejemplos` | `S14-2_coordenadas_polares` |
| 15 | `S15-1_graficas_polares_especiales` (semana con feriado: una sola sesión) | |

Requisitos: TeX Live con `beamer`, `pgfplots`, `tcolorbox`, `babel-spanish`, `stmaryrd`.

## Estructura didáctica de cada sesión (README raíz)

Cada presentación incorpora, además del contenido, cuatro frames y ajustes de plan que aplican el modelo de aprendizaje activo:

| Elemento | Dónde aparece | Estrategia del modelo |
|---|---|---|
| Competencia del sílabo | Frame de objetivos | Coherencia con el sílabo |
| Aula invertida: lectura y tarea previa + verificación de 5 min en pares | 2.º frame | Aula invertida, trabajo colaborativo |
| Actividad colaborativa (ABP, estudio de casos, investigación, experiencia con GeoGebra/Python/CAS, miniproyecto, enseñanza entre pares) con roles, producto y retroalimentación | Antes de los ejercicios propuestos | ABP, casos, investigación, experiencia, colaborativo |
| Metacognición (2 preguntas comunes + 1 específica) y uso responsable de la IA (contrastar, verificar, declarar) | Antes del resumen | Metacognición, IA con responsabilidad intelectual |
| Evaluación: práctica del miércoles, cobertura, criterios de la rúbrica común, declaración de IA y portafolio | Último frame | Evaluación sumativa, rúbricas, portafolio, autoevaluación |

El plan de 2 horas reserva los últimos minutos para la actividad colaborativa y el cierre metacognitivo, y los primeros 5 para la verificación de la lectura previa.

## Calendario de evaluación (dosificado 2026-2)

Sistema G: `PF = (EP + EF + PP)/3`; `PP` es el promedio de las 4 mejores prácticas calificadas.

| Semana | Práctica (miércoles) | Cobertura |
|---|---|---|
| 1 | Prueba de entrada (diagnóstica) | Conocimientos previos |
| 2 | PD1 | Semanas 1 y 2 |
| 3 | PD2 | Semana 3 |
| 4 | PC1 | Semanas 1, 2 y 3 |
| 5 | PD3 | Semanas 4 y 5 |
| 6 | PD4 | Semana 6 |
| 7 | PC2 | Semanas 4, 5 y 6 |
| 8 | **Examen Parcial** | Semanas 1 a 6 |
| 9 | PD5 | Semanas 7 y 9 |
| 10 | PD6 | Semana 10 |
| 11 | PC3 | Semanas 7, 9 y 10 |
| 12 | PD7 | Semanas 11 y 12 |
| 13 | PD8 | Semana 13 |
| 14 | PC4 | Semanas 11, 12 y 13 |
| 15 | PD9 (feriado del mi 9/12: se nivela en la sesión) | Semana 14 |
| 16 | **Examen Final** | Semanas 9 a 14 |
| 17 | **Examen Sustitutorio** | Todo el curso |

**Supuestos a confirmar.** (1) PD = práctica dirigida (en equipo, formativa) y PC = práctica calificada (individual). (2) El sílabo habla de cinco prácticas calificadas y el dosificado solo muestra cuatro PC; la quinta está por definir. (3) El portafolio es evidencia formativa y no modifica el cálculo de PF.

**Rúbrica común:** corrección y rigor matemático; justificación y notación; modelamiento e interpretación; comunicación y trazabilidad (incluye la declaración de uso de IA).

Los fuentes de estas secciones están en `bma01.sty` (entornos `previa`, `activa`, `metacog`, `iabox`, `evalbox` y macros `\metacomun`, `\criterios`, `\declaracionia`).
