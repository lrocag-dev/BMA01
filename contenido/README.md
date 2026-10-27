# BMA01 – Cálculo Diferencial (2026-2) · Presentaciones por sesión

Presentaciones Beamer (16:9) para cada sesión de 2 horas del dosificado `Dosificado_BMA01-2026-2.pdf`.
Cada archivo incluye: objetivos y plan de la sesión, teoría con ejemplos resueltos, gráficas (TikZ/PGFPlots),
ejercicios propuestos y resumen.

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
