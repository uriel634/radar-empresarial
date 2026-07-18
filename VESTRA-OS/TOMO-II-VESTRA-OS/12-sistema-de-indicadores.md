# CAPÍTULO 12 — SISTEMA DE INDICADORES

## TOMO II · VESTRA OS™

---

## 12.1 El problema que resuelve este sistema

"No sé si el negocio va bien o mal hasta que veo el banco." Esta frase, recogida literalmente en decenas de diagnósticos (Cap. 9), describe una empresa que opera con el equivalente administrativo de manejar de noche sin faros: solo se entera de que hay un problema cuando ya está encima de él. El Sistema de Indicadores VESTRA instala los "faros" — métricas que anticipan el resultado financiero en lugar de solo confirmarlo semanas o meses después.

## 12.2 Principio rector: indicadores líderes sobre indicadores rezagados

Un **indicador rezagado** (lagging indicator) mide un resultado que ya ocurrió: ingreso del mes, utilidad neta, cartera vencida. Es útil para confirmar tendencia, pero para cuando aparece el problema en un indicador rezagado, ya es demasiado tarde para corregirlo en ese periodo — el daño ya está hecho.

Un **indicador líder** (leading indicator) mide una acción o condición que predice el resultado antes de que ocurra: número de cotizaciones enviadas esta semana predice el ingreso de dentro de 30 días; tiempo de respuesta a un cliente predice la tasa de retención del trimestre. Un indicador líder es accionable en tiempo real — se puede corregir el rumbo mientras el trimestre todavía está en curso.

VESTRA exige que **cada área del negocio tenga al menos un indicador líder identificado**, no solo indicadores rezagados. La revisión semanal (RSD, Cap. 11.3) se enfoca deliberadamente en los líderes; la revisión mensual (RMR) incorpora los rezagados para confirmar tendencia completa.

## 12.3 Metodología de diseño de indicadores por área

Para cada área funcional de la empresa cliente, el consultor VESTRA aplica el siguiente proceso de cuatro pasos (nunca se copian indicadores genéricos de una lista sin pasar por este proceso con el equipo del área):

1. **Definir el resultado que el área debe producir** ("¿qué existe en el mundo gracias a que esta área funciona bien?").
2. **Identificar el indicador rezagado que mejor mide ese resultado** (usualmente 1, máximo 2).
3. **Retroceder causalmente para encontrar el indicador líder** ("¿qué acción, si se hace consistentemente esta semana, produce ese resultado dentro de 4-8 semanas?").
4. **Asignar un responsable único, una meta numérica y una frecuencia de captura** a cada indicador seleccionado.

## 12.4 Catálogo de indicadores por área (referencia estándar)

Esta tabla es el punto de partida de trabajo del consultor — nunca el resultado final sin pasar por el proceso 12.3 con el cliente específico, porque los indicadores correctos dependen del modelo de negocio real de cada empresa.

| Área | Indicador líder típico | Indicador rezagado típico |
|---|---|---|
| **Comercial/Ventas** | Nuevas conversaciones/cotizaciones generadas por semana; tasa de respuesta a leads en <2 horas | Ingreso mensual; tasa de cierre del pipeline |
| **Operaciones/Producción** | % de órdenes iniciadas a tiempo; incidencias de calidad detectadas antes de entrega | Tiempo total de ciclo de producción/entrega; costo por unidad producida |
| **Servicio al cliente/Postventa** | Tiempo promedio de primera respuesta; % de tickets resueltos en el primer contacto | NPS trimestral; tasa de retención/cancelación |
| **Finanzas/Cobranza** | % de facturas enviadas el mismo día del servicio; llamadas de seguimiento a cartera por vencer | Días promedio de cuentas por cobrar (DSO); cartera vencida total |
| **Recursos Humanos/Talento** | Vacantes cubiertas dentro del plazo objetivo; entrevistas de salida realizadas | Rotación de personal trimestral; ausentismo mensual |
| **Dirección General** | Cumplimiento de agenda de RSD/RMR (Cap. 11); Rocas en semáforo verde | Margen neto mensual; Métrica Norte (Cap. 10.2.5) |

## 12.5 El Dashboard VESTRA — estructura y jerarquía visual

El dashboard no es una hoja de Excel con cuarenta columnas — es, deliberadamente, un artefacto visual diseñado para que el equipo directivo entienda el estado del negocio en menos de 30 segundos de revisión. VESTRA instala el dashboard con tres niveles de jerarquía visual (plantilla completa en Anexos, disponible en formato Excel/Google Sheets para clientes en H1, migrando a plataforma propia en H2/H3, ver Tomo VII):

**Nivel 1 — Vista de Semáforo (la que se abre primero):** Cada indicador clave con un solo color: verde (en meta), amarillo (en riesgo, dentro de 10% de la meta), rojo (fuera de meta). Sin números todavía — solo temperatura visual, para la revisión de 10 segundos.

**Nivel 2 — Vista de Tendencia:** Cada indicador con su histórico de las últimas 8–12 semanas en formato de gráfico de línea simple, para distinguir una desviación puntual de una tendencia sostenida.

**Nivel 3 — Vista de Detalle:** Los datos numéricos completos, fuente de captura, fórmula de cálculo y responsable — para cuando alguien necesita auditar o entender el "por qué" detrás del semáforo.

## 12.6 Protocolo de captura de datos

El indicador más elegante del mundo es inútil si los datos que lo alimentan no son confiables o consistentes. VESTRA exige, como parte no negociable de la instalación, que cada indicador tenga documentado:

```
INDICADOR: [Nombre]
FÓRMULA: [Cálculo exacto, sin ambigüedad]
FUENTE DE DATOS: [De dónde sale el dato — sistema, reporte, conteo manual]
RESPONSABLE DE CAPTURA: [Una persona nombrada]
FRECUENCIA DE CAPTURA: [Diaria/semanal/mensual]
DÍA Y HORA LÍMITE DE CAPTURA: [Ej. "todos los viernes antes de las 3pm"]
META: [Número objetivo]
UMBRAL DE ALERTA (AMARILLO): [A partir de qué desviación se marca amarillo]
```

La regla de oro instalada en cada cliente: **un indicador sin responsable de captura nombrado deja de medirse en la semana tres, sin excepción** — este patrón se ha observado con tal consistencia en la práctica de campo de VESTRA que se trata como ley operativa, no como posibilidad.

## 12.7 La Métrica Norte y su relación con el tablero completo

Como se definió en el Capítulo 10.2.5, la Métrica Norte es el único número que mejor resume si la empresa avanza. En el dashboard, la Métrica Norte ocupa siempre la posición visual más prominente (arriba a la izquierda, de mayor tamaño que cualquier otro indicador) — es la primera cifra que cualquier miembro del equipo directivo ve al abrir el tablero, en cualquier reunión de cualquier nivel (Cap. 11.2).

Ejemplos reales (anonimizados) de Métrica Norte instalada por industria:

| Industria del cliente | Métrica Norte seleccionada | Razonamiento |
|---|---|---|
| Distribuidora de materiales de construcción | % de pedidos entregados completos y a tiempo | Correlaciona directamente con retención de clientes B2B recurrentes, mejor que el ingreso mensual (que puede subir por un solo pedido grande y ocultar deterioro de servicio) |
| Despacho de servicios profesionales (contable/legal) | Horas facturables por consultor por semana | Predice tanto ingreso como riesgo de burnout del equipo — dos variables críticas en un negocio basado en tiempo experto |
| Clínica privada (salud) | Tasa de reagendamiento de pacientes recurrentes | Mide lealtad y calidad percibida mejor que el número bruto de consultas, que puede inflarse con pacientes de una sola visita |
| Manufactura ligera | % de órdenes sin retrabajo/reproceso | Indicador de calidad que predice tanto costo como satisfacción del cliente final |

## 12.8 Cadencia de revisión y su vínculo con el Modelo de Dirección

El Sistema de Indicadores no existe de forma aislada — está diseñado desde su origen para alimentar exactamente los tres niveles de reunión del Capítulo 11:

| Nivel de reunión | Qué se revisa del dashboard |
|---|---|
| RSD (semanal) | Solo Nivel 1 (Semáforo) de indicadores líderes, foco exclusivo en rojos/amarillos |
| RMR (mensual) | Nivel 1 + Nivel 2 (Tendencia) del tablero completo, líderes y rezagados |
| STP (trimestral) | Nivel 2 + Nivel 3 (Detalle), con análisis de correlación entre indicadores y resultado de Rocas |

## 12.9 Errores comunes al instalar el Sistema de Indicadores

- **Medir demasiado.** Un dashboard con 40 indicadores no se revisa nunca completo — VESTRA limita a un máximo de 8–12 indicadores por área y 5–7 en el nivel de Dirección General, priorizando implacablemente.
- **Indicadores de vanidad.** Métricas que se ven bien pero no predicen ni informan ninguna decisión real (ej. "seguidores en redes sociales" para una empresa cuyo negocio no depende de redes) — cada indicador debe pasar la prueba: "si este número cambia, ¿qué decisión distinta tomaríamos?"
- **Falta de definición operacional de la fórmula.** Dos personas capturando "ventas del mes" con criterios distintos (con o sin IVA, con o sin devoluciones) generan un dato que parece confiable pero no lo es — de ahí la obligatoriedad del protocolo 12.6.
- **El dashboard vive en la cabeza del dueño, no es visible para el equipo.** Si los responsables de área no ven su propio indicador de forma regular y accesible, no pueden gestionarlo — el dashboard debe ser visible (físicamente en un monitor, o digitalmente accesible) para todo el equipo relevante, no un documento privado del dueño.
