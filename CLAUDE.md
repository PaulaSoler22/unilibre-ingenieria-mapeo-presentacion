# CLAUDE.md — Simuladores para Ingeniería · Universidad Libre

> Documento de trabajo de **esta** presentación (no la plantilla). Sirve para preparar la
> reunión: aquí está la respuesta honesta a cualquier pregunta sobre cobertura, aunque el deck
> no la muestre.

## Qué es esta presentación

Pieza **comercial de prospección** — la Universidad Libre **no es cliente** actual de
Simuladores de Negocios Colombia — para directores de programa y decano de la **Facultad de
Ingeniería**: Ingeniería Industrial (SNIES 54334) e Ingeniería de Sistemas (SNIES 11584).

Se aparta de la plantilla estándar en un punto importante: el mapeo no se hizo solo contra el
catálogo CompanyGame, sino también contra **SimVenture, SimAgile y SimProject** — simuladores
especializados que no son del catálogo CompanyGame y que este deck asume que Simuladores de
Negocios Colombia también representa. **Confirmar esto antes de la reunión** si no está ya
validado comercialmente: el `README.md` y el pie de página del deck ya no dicen "distribuidor
autorizado CompanyGame" en exclusiva por esta razón.

## Fuente de los datos

`Universidad Libre - Ing_Industrial y Sistemas (revisado).xlsx` (en esta misma carpeta),
recibido el 4-sep-2026. Hojas: Resumen Ejecutivo, Ing. Industrial, Ing. de Sistemas,
Priorización, Desarrollos Propios, Recomendaciones, Catálogo CompanyGame.

Existe una versión previa sin "(revisado)" en Descargas
(`Analisis_Simuladores_Universidad_Libre_Ing_Industrial_y_Sistemas.xlsx`) — **no se usó**; toda
cifra de este deck sale de la versión "(revisado)".

## Las cifras completas — incluida la cobertura que el deck no muestra

El deck dice «20 asignaturas con simulador» y nunca el total analizado. Aquí está el
denominador, por si lo preguntan en la reunión:

| | Ing. Industrial | Ing. de Sistemas | Total |
|---|---|---|
| Asignaturas en la malla | 53 | 53 | **106** |
| Créditos | 144 | 144 | 288 |

**Catálogo CompanyGame** (hoja Resumen Ejecutivo, columna "Grado de ajuste"):

| | Ing. Industrial | Ing. de Sistemas | Total |
|---|---|---|
| Encaje perfecto | 7 | 4 | 11 |
| Encaje parcial | 3 | 5 | 8 |
| No encaja | 37 | 38 | 75 |
| Por definir (electivas sin contenido) | 6 | 6 | 12 |

**SimVenture / SimAgile / SimProject** (calificación "Alta" en su propia columna):

| | Ing. Industrial | Ing. de Sistemas | Total |
|---|---|---|
| SimVenture Alta | 1 | 1 | 2 |
| SimAgile Alta | 1 | 1 | 2 |
| SimProject Alta | 1 | 2 | 3 |

**Oportunidad de desarrollo propio** (Alta + Media, hoja Resumen Ejecutivo): 53 asignaturas en
total (13 Ind.-Alta + 6 Sist.-Alta + 18 Ind.-Media + 16 Sist.-Media) — es decir, **la mitad del
total de asignaturas de la Facultad** se clasificó como oportunidad de desarrollo propio de
algún grado. El deck solo presenta los tres desarrollos que el cliente interno confirmó
priorizar (ver abajo); el resto (DP-05 a DP-09, y DP-10 que es otra línea de producto) no se
menciona, siguiendo el mismo criterio editorial de no exponer todo el diagnóstico.

## Metodología: cómo se llegó a 20 / 15 / 5 / 11

El deck no usa un solo campo del Excel como fuente de "asignatura con simulador": se construyó
cruzando, fila por fila de las hojas "Ing. Industrial" e "Ing. de Sistemas" (columnas
SimVenture / SimAgile / SimProject / Simulador CompanyGame que encaja / Nivel CG / Grado de
ajuste), el siguiente criterio:

- **Perfecto** (verde, "de aplicación directa"): `Grado de ajuste = Encaje perfecto`, o bien
  ninguno de los tres simuladores especializados calificó "Alta" y el Grado de ajuste es
  "No encaja" pero SimVenture, SimAgile o SimProject sí calificó **Alta** en su columna propia.
- **Parcial** (ámbar, "como apoyo al curso"): `Grado de ajuste = Encaje parcial`, **siempre que
  la columna "Simulador recomendado" nombre un simulador real** (ver salvedad siguiente).
- Todo lo demás (Baja / No evaluable / No encaja sin ningún Alta) no entra al deck.

Con esto: Industrial 9 perfecto + 2 parcial = 11 · Sistemas 6 perfecto + 3 parcial = 9 ·
Total 20 (15 perfecto + 5 parcial). Simuladores distintos: 9 en Industrial, 7 en Sistemas,
**11 en total en toda la Facultad** (8 del catálogo CompanyGame + SimVenture + SimAgile +
SimProject): ContaTrainer, Business21, Kapital, MarketGame/GlobalMARKET, InnovaTech,
ESGManagement/ESGProject, Businessglobal/Business Strategy, Global2030, SimVenture, SimAgile,
SimProject.

**Nota:** una suma ingenua de las cifras por categoría de la hoja Resumen Ejecutivo (11+8
CompanyGame + 2+2+3 SimVenture/SimAgile/SimProject) da 26, no 20 — la diferencia son
asignaturas que califican por más de un criterio a la vez (p. ej. Gerencia Estratégica: encaje
perfecto de catálogo **y** SimVenture Alta) y que en el deck cuentan una sola vez.

## Salvedades del Excel — para no improvisar si preguntan

- **Tres filas con "Grado de ajuste = Encaje parcial" que en realidad no tienen simulador
  hoy.** SIMULACIÓN DE PROCESOS (Industrial, sem. VIII), SEGURIDAD DE LA INFORMACIÓN (Sistemas,
  sem. VII) y SISTEMAS INTEGRADOS DE GESTIÓN (Sistemas, sem. VIII) están marcadas "Encaje
  parcial" en la columna de grado, pero su columna "Simulador recomendado" dice literalmente
  "Desarrollo propio (…)" y la columna CompanyGame está vacía ("—"). Se excluyeron de las fichas
  (no son "lo que ya se puede hacer hoy") y en cambio alimentan el slide de Desarrollos propios:
  SIMULACIÓN DE PROCESOS → línea de DP-01 (Planeación y Control de Operaciones); SEGURIDAD DE LA
  INFORMACIÓN → línea de DP-05 (no incluido entre los tres priorizados); SISTEMAS INTEGRADOS DE
  GESTIÓN → línea de DP-03 (sí incluido).
- **Inconsistencia entre columnas para dos asignaturas.** En GERENCIA ESTRATÉGICA (ambos
  programas) y MERCADEO (Industrial), la columna "Simulador CompanyGame que encaja" nombra un
  producto (Business Strategy; Coffee Time) que no coincide con los dos niveles que trae
  "Nivel CG" (p. ej. "N5 / N6-7"), mientras que la columna "Simulador recomendado" sí nombra dos
  productos consistentes con esos dos niveles (Businessglobal N5 / Business Strategy N6-7;
  MarketGame N1-2 / GlobalMARKET N6-7). El deck usa la redacción de "Simulador recomendado" en
  estos dos casos para no mostrar un nivel que no corresponde al producto.
- **Valor suelto en una celda.** En Ing. Industrial, la fila DISEÑO EN INGENIERÍA tiene "169" en
  la columna "Simulador CompanyGame que encaja" — no es un simulador, parece un residuo de
  captura. Como el Grado de ajuste de esa fila es "No encaja", el valor nunca iba a mostrarse,
  pero convendría corregirlo en el Excel fuente.
- Las columnas SimVenture/SimAgile/SimProject solo usan tres niveles (Alta / Baja / No
  evaluable) — no existe una calificación "Media" para estos tres productos, a diferencia del
  catálogo CompanyGame que sí tiene "Encaje parcial".
- La columna "Simulador recomendado" a veces nombra un simulador (típicamente SimVenture) como
  alternativa aunque su propia columna de calificación diga "Baja" para esa fila — el deck
  conserva esas alternativas como texto secundario ("o SimVenture") en la ficha, porque son
  literales del Excel, pero no las cuenta para las cifras de "simuladores distintos".
- Ninguna asignatura quedó "por definir" dentro del conjunto de 20 (las 12 electivas/optativas
  "por definir" del catálogo CompanyGame no entraron al deck en ningún caso).

## Los tres desarrollos propios del slide "Lo que viene"

Confirmados directamente por el cliente interno (no son los de mayor prioridad académica de la
hoja "Desarrollos Propios" — esos son DP-01 y DP-03 en Prioridad 1; DP-02 está en Prioridad 3
por solaparse con el catálogo):

- **DP-01 · Planeación y Control de Operaciones** (Ing. Industrial, Prioridad 1).
- **DP-03 · Implementación y Auditoría de Sistemas Integrados de Gestión** (los dos programas,
  Prioridad 1).
- **DP-02 · Transformación Digital y Arquitectura Empresarial** (los dos programas, Prioridad 3
  — la familia Business Transformation del catálogo, TRANSFORMA/Global2030, ya cubre buena
  parte; el desarrollo propio se evalúa solo si el programa exige algo más específico).

**DP-04 (Cadena de Suministro) no es uno de los tres.** Ya existe como producto:
**GlobalChain**. El deck lo presenta aparte, como algo que ya se puede ofrecer hoy, no como un
desarrollo pendiente.

Quedan fuera del deck, por decisión editorial (no exponer todo el diagnóstico): DP-05
(Seguridad de la Información), DP-06 (Control Estadístico de Calidad), DP-07 (Dilemas Éticos),
DP-08 (SG-SST), DP-09 (Diseño de Instalaciones) y DP-10 (laboratorios virtuales — línea de
producto distinta, no es un simulador de gestión).

## Slides añadidos o eliminados respecto a la plantilla

- **Añadido** — "Simuladores más allá del catálogo CompanyGame" (`slideOtrosSimuladores`),
  después de la cartelera: contexto breve de SimVenture, SimAgile y SimProject. No existe en la
  plantilla porque ninguna universidad anterior mezclaba productos de fuera del catálogo
  CompanyGame.
- **Añadido** — "Lo que viene: desarrollos propios en evaluación" (`slideDesarrollosPropios`),
  antes de Evidencia de aprendizaje: los tres desarrollos confirmados + nota de GlobalChain.
- **Eliminado** — el slide de "Asignaturas transversales". Solo Cátedra de Sostenibilidad se
  repite en los dos programas con encaje perfecto (una asignatura, no varias), así que no
  justifica un slide propio con cadena de valor de tres eslabones. Ese hallazgo se cuenta en el
  acordeón del slide 3 ("Lo que ya se puede hacer hoy").
- Slides fijos sin tocar: Portada, Cartelera, Los tres modelos de uso docente, Cierre.
- Slide "Evidencia de aprendizaje": se dejaron solo los simuladores que aparecen en el mapeo
  (8 de CompanyGame) y se añadieron tres filas nuevas para SimVenture, SimAgile y SimProject —
  no estaban en la tabla original de la plantilla porque es una tabla del catálogo CompanyGame.

## Tono con el docente

Se mantuvo el criterio de la plantilla: el simulador se integra al curso que el docente ya
dicta, nunca al revés. Las etiquetas son "de aplicación directa" / "como apoyo al curso", sin
lenguaje de esfuerzo o carga.

## Repositorio público

⚠️ Si esta carpeta se sube a un repositorio público, revisar que este archivo no filtre nada
que no deba salir de la casa (cifras de cobertura real, cifras de desarrollo propio no
priorizadas, o el hecho de que la Universidad Libre aún no es cliente).

## Datos fijos del distribuidor

- Plataforma: https://plataforma.companygame.net/
- **Comercial** (ventas): ventas@simuladoresdenegocios.co · WhatsApp 318 975 6987
- **Fidelización** (acompañamiento): fidelizacion@simuladoresdenegocios.co · WhatsApp 301 790 3086
- El cierre muestra los dos bloques, comercial primero.
- Distribuidor: Simuladores de Negocios Colombia (Grupo Edutec)
