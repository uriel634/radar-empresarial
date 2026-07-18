# CAPÍTULO 13 — ARQUITECTURA DE PROCESOS

## TOMO II · VESTRA OS™

---

## 13.1 El problema que resuelve este sistema

"Cada quien hace las cosas a su manera." El conocimiento operativo crítico de la empresa —cómo se cotiza correctamente, cómo se resuelve una queja de cliente, cómo se hace el corte de caja, cómo se surte un pedido sin errores— vive exclusivamente en la memoria de las personas, no en la empresa como entidad. Esto genera tres riesgos simultáneos que el diagnóstico (Cap. 9) identifica sistemáticamente: inconsistencia de calidad (el resultado depende de quién lo hizo), fragilidad ante rotación (cuando esa persona se va, se va el conocimiento con ella), e imposibilidad de delegar con confianza (el dueño no suelta el control porque no existe garantía escrita de que se haga bien sin él).

## 13.2 Principio rector: documentar solo lo crítico, no todo

Un error frecuente de iniciativas fallidas de documentación de procesos en PyME es el intento de documentar absolutamente todo, lo cual produce un manual de 200 páginas que nadie lee ni actualiza nunca. VESTRA aplica el principio inverso: se documentan, en la Instalación de 90 días, únicamente los **3 a 5 procesos críticos** de la empresa — definidos con el criterio siguiente:

> Un proceso es crítico si (a) su ejecución incorrecta genera daño directo y visible al cliente o a la operación, y/o (b) actualmente depende de una sola persona (frecuentemente el dueño) cuya ausencia detendría o degradaría gravemente ese proceso.

El resto de los procesos de la empresa —igual de reales, pero de menor riesgo— quedan fuera del alcance de la Instalación inicial y se documentan de forma progresiva por el propio cliente, usando la misma metodología, como parte de la disciplina continua sostenida en la Membresía (Servicio 3, Cap. 5).

## 13.3 Metodología de identificación de procesos críticos

Ejercicio conducido en taller con el equipo directivo (ver Tomo IV, Semana 5), usando la Matriz de Criticidad de Procesos:

```
                    ALTO IMPACTO EN CLIENTE/OPERACIÓN
                              │
      ZONA DE DOCUMENTAR      │      ZONA DE DOCUMENTAR
      SEGUNDO (importante,    │      PRIMERO (crítico,
      pero con respaldo)      │      urgente)
                              │
   BAJA ──────────────────────────────────────── ALTA
DEPENDENCIA                   │              DEPENDENCIA
DE 1 PERSONA                  │              DE 1 PERSONA
                              │
      ZONA DE NO PRIORIZAR    │      ZONA DE DOCUMENTAR
      (bajo riesgo actual)    │      TERCERO (dependencia alta,
                              │      pero impacto menor)
                    BAJO IMPACTO EN CLIENTE/OPERACIÓN
```

Cada proceso candidato (generado por lluvia de ideas con el equipo, típicamente 15–25 procesos identificados en la primera ronda) se ubica en esta matriz, y se seleccionan los 3–5 que caen en el cuadrante superior derecho para la documentación formal de la Instalación.

## 13.4 El formato SOP VESTRA

VESTRA documenta procesos en un formato estandarizado — Procedimiento Operativo Estándar (SOP) — diseñado deliberadamente para ser usado en el piso de operación, no archivado. Estructura obligatoria (plantilla completa en Anexos):

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
SOP: [Nombre del proceso]
VERSIÓN: [Número] · ÚLTIMA ACTUALIZACIÓN: [Fecha]
DUEÑO DEL PROCESO: [Persona responsable de mantenerlo actualizado]
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

OBJETIVO
[Una frase: qué logra este proceso cuando se ejecuta bien]

DISPARADOR
[Qué evento inicia este proceso — ej. "llega un correo de cotización"]

ENTRADAS NECESARIAS
[Qué información/materiales se necesitan antes de empezar]

PASOS (numerados, verbo en infinitivo, uno por línea)
1. [Acción específica]
2. [Acción específica]
   ...

PUNTOS DE VERIFICACIÓN (checkpoints de calidad dentro del proceso)
☐ [Qué se revisa antes de continuar al siguiente paso]

RESULTADO ESPERADO
[Cómo se ve el proceso terminado correctamente]

ERRORES COMUNES Y CÓMO EVITARLOS
[Lista de los 2-4 errores más frecuentes observados históricamente]

TIEMPO ESTÁNDAR
[Cuánto debería tomar en condiciones normales]
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

## 13.5 Metodología de captura del proceso real

El error más común al documentar procesos es que el consultor (o el propio dueño) escriba el proceso "como debería ser" en teoría, en lugar del proceso "como realmente se ejecuta" hoy — lo cual produce un SOP que nadie sigue porque no coincide con la realidad operativa. VESTRA exige el siguiente protocolo de captura:

1. **Observación directa (shadowing):** El consultor observa a la persona que actualmente ejecuta el proceso, en tiempo real, sin interrumpir, tomando nota de cada paso exactamente como ocurre.
2. **Entrevista de "piensa en voz alta":** Se le pide al ejecutor que repita el proceso explicando en voz alta cada decisión que toma ("aquí reviso esto porque...") — esto captura el conocimiento tácito que la sola observación no revela.
3. **Borrador y validación cruzada:** El SOP borrador se revisa con al menos dos personas distintas que ejecutan o han ejecutado ese proceso, para detectar variaciones no documentadas y llegar a la versión que representa la mejor práctica real, no solo la más común.
4. **Prueba piloto:** Una persona que NO participó en la documentación intenta seguir el SOP escrito, sin ayuda adicional, para validar que está completo y comprensible sin conocimiento previo tácito.

## 13.6 Los cinco procesos más frecuentemente críticos por industria

Referencia de trabajo para el consultor (nunca sustituye el ejercicio 13.3 específico con cada cliente):

| Industria | Procesos típicamente críticos |
|---|---|
| Distribución/Comercialización | Cotización y aprobación de precio especial · Surtido y verificación de pedido · Gestión de devoluciones · Cobranza a clientes con crédito · Onboarding de cliente nuevo |
| Manufactura ligera | Control de calidad en línea · Programación de producción · Mantenimiento preventivo de maquinaria · Gestión de merma/desperdicio · Recepción y control de materia prima |
| Servicios profesionales | Onboarding de cliente nuevo · Entrega y revisión de trabajo antes de enviar al cliente · Cotización de proyectos no estándar · Gestión de expedientes/documentación · Facturación y cobranza |
| Construcción | Cotización de obra · Control de avance de obra vs. presupuesto · Gestión de subcontratistas · Control de calidad en entregables por etapa · Cierre y entrega de obra |
| Retail especializado | Recepción y exhibición de mercancía · Atención y cierre de venta en piso · Gestión de inventario y reposición · Manejo de devoluciones/garantías · Apertura y cierre de caja |

## 13.7 Comunicación y adopción del proceso documentado

Un SOP perfectamente escrito que nadie conoce o usa no tiene ningún valor. VESTRA instala un protocolo mínimo de adopción como parte obligatoria de la Instalación (ver Tomo IV, Semana 6):

1. **Sesión de socialización** con todo el equipo que ejecuta o se ve afectado por el proceso — nunca se distribuye el SOP solo por correo o grupo de WhatsApp sin una sesión donde se explique y se resuelvan dudas en vivo.
2. **Ubicación física/digital accesible en el momento de ejecución** — el SOP debe estar disponible exactamente donde y cuando se necesita (impreso en el punto de trabajo, o accesible en el celular/tablet usado en piso), no enterrado en una carpeta de la computadora del dueño.
3. **Incorporación al proceso de inducción de personal nuevo** (ver Tomo VI para el equivalente interno de VESTRA) — todo colaborador nuevo que ejecute ese proceso debe aprenderlo primero del SOP, con supervisión, no solo por transmisión oral de un compañero.
4. **Revisión programada de vigencia** — cada proceso documentado se revisa como mínimo en cada Reunión Mensual de Revisión rotativa (Cap. 11.6, Bloque 3) para confirmar que sigue reflejando la mejor práctica real y no se ha vuelto obsoleto por cambios en la operación.

## 13.8 Errores comunes en la Arquitectura de Procesos

- **Documentar el proceso ideal en lugar del proceso real observado** — ver 13.5, la causa raíz más común de SOPs que se abandonan.
- **Sobre-documentar procesos de bajo riesgo** por comodidad (son más fáciles de escribir que los verdaderamente críticos y complejos), desviando el tiempo limitado de la Instalación de donde más impacto tiene.
- **Tratar la documentación como un evento único** en lugar de una disciplina continua — un proceso documentado y nunca actualizado se vuelve obsoleto en 6–12 meses conforme la operación evoluciona.
- **No asignar un Dueño del Proceso** responsable de mantenerlo vigente — sin este rol nombrado (ver formato 13.4), la actualización nunca ocurre porque no es responsabilidad explícita de nadie.
- **Confundir documentar con automatizar.** Documentar el proceso es siempre el paso previo; decidir qué automatizar o qué sistema/software adoptar (Tomo VII, Capítulo de Automatización) viene después, nunca antes, porque automatizar un proceso mal diseñado solo produce el mismo error más rápido.
