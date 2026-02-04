# Manifiesto del Equipo de Desarrollo de IA

> **La IA es nuestra aliada, no nuestro sustituto**  
> *Experimentamos con responsabilidad, experiencia y colaboración.*

---

## Índice
- [Principios Fundamentales](#principios-fundamentales)
	- [Responsabilidad](#-responsabilidad)
	- [Revisión de Código Competente](#-revisión-de-código-competente)
- [Documentación y Transparencia](#documentación-y-transparencia)
	- [Agents.md como base](#-agentsmd-como-base)
- [Enfoque y Alcance](#enfoque-y-alcance)
	- [Relevancia de la Tarea](#-relevancia-de-la-tarea)
- [Requisitos y Reproducibilidad](#requisitos-y-reproducibilidad)
	- [Tareas Claras y Reproducibles](#-tareas-claras-y-reproducibles)
- [Prompting y Estandarización](#prompting-y-estandarización)
	- [Prompts como Activos de Equipo](#-prompts-como-activos-de-equipo)
- [Interacción directa y anti-Sycophancy](#interacción-directa-y-anti-sycophancy)
- [Colaboración y Compartir](#colaboración-y-compartir)
- [Nuestro Objetivo](#nuestro-objetivo)

---

## Principios Fundamentales

### ✅ Responsabilidad
- Quien abre una **Pull Request (PR)** es **responsable y propietario del desarrollo**.
- Debe comprender cada parte del código y las decisiones de implementación.
- La IA es una herramienta de apoyo: **asiste, pero no decide**.

### 🔍 Revisión de Código Competente
- El revisor es responsable de la calidad del código según su experiencia técnica.
- La revisión sigue los estándares establecidos: **la competencia en el lenguaje y la tecnología sigue siendo esencial**.

---

## Documentación y Transparencia

### 📚 Agents.md como base
- El primer paso del proyecto es completar **`Agents.md`**, adaptándolo a:
	- especificaciones del proyecto
	- mejores prácticas internas
	- directrices de producto y framework
- **`Agents.md` es un documento vivo** y debe actualizarse constantemente con:
	- particularidades del proyecto
	- limitaciones y obligaciones clave
	- reglas operativas compartidas
- **¿Solicitudes repetidas en el chat? Añádelas a `Agents.md`.**

---

## Enfoque y Alcance

### 🎯 Relevancia de la Tarea
- Cada acción debe permanecer **dentro del alcance de la tarea/bug y sus requisitos**.
- Si la IA sugiere mejoras útiles pero **no relevantes para la tarea actual**:
	- **repórtalas** y/o
	- **crea una tarea/issue/US dedicada** para su evaluación posterior.

---

## Requisitos y Reproducibilidad

### 🛠 Tareas Claras y Reproducibles
- **Trabaja en tareas atómicas**, con intervenciones limitadas y contenidas (especialmente en las primeras fases experimentales).
- Si el trabajo es mayor (feature o cambio complejo), **utiliza el modo _Plan_** para dividirlo en tareas más claras y manejables.
- **Cada tarea/issue debe tener requisitos claros, explícitos y documentados.**
- **Cada bug debe documentarse con detalles técnicos para su reproducción**, incluyendo:
	- contexto
	- pasos para reproducir
	- entorno
	- logs o evidencias útiles

---

## Prompting, Modelos y Estandarización

### 🔁 Prompts y Modelos como Activos de Equipo
- Los prompts y modelos son **parte integral del trabajo**, no actividades individuales o improvisadas.
- La actividad del equipo incluye **la evaluación consciente de los modelos de IA más adecuados** según:
	- tipo de tarea (análisis, codificación, refactorización, depuración, documentación, etc.)
	- lenguaje o tecnología utilizada
	- complejidad y criticidad del trabajo
- Los prompts más efectivos y **las elecciones de modelo más apropiadas** deben ser:
	- **compartidas**
	- **discutidas**
	- **refinadas** dentro del equipo
- El objetivo es **estandarizar prompts y modelos para las solicitudes más comunes**, para así:
	- obtener resultados de calidad en **pocos pasos**
	- mejorar la **eficiencia operativa**
	- **reducir el consumo de recursos** (tiempo, tokens, iteraciones innecesarias)
- Los prompts o elecciones de modelo repetidos o particularmente efectivos deben ser:
	- **documentados** (por ejemplo, en la sección de Discussions de GitHub)
	- **mantenidos y evolucionados** como **mejores prácticas de equipo**
---

## Interacción directa y anti-Sycophancy

- **Nada de "amabilidades"**: la IA es una herramienta, no un interlocutor social. Evita "por favor", "puedes" o expresiones dubitativas. La cortesía innecesaria consume tokens y, peor aún, activa el sesgo de complacencia (sycophancy): el modelo tenderá a darte la razón para complacerte, incluso validando lógicas erróneas.

- **Órdenes, no diálogos**: sustituye el razonamiento conversacional por instrucciones directas ('escribe', 'resuelve', ...). Dar demasiados "porqués" personales antes de la solución lleva a la IA a reflejar tus prejuicios en lugar de analizar el código objetivamente.

- **Friction by Design**: si una IA siempre está de acuerdo contigo, sospecha. Un prompt eficaz debe forzar al modelo a ser crítico, no a actuar como un "Yes-Man".

---

## Colaboración y Compartir
- Participa activamente en la discusión y colaboración del equipo.
- Comparte experiencias, prompts, sugerencias y lecciones aprendidas.
- La IA es una aliada, pero **el verdadero valor reside en la experiencia humana y el intercambio continuo**.

---

## Nuestro Objetivo
> Experimentar con la IA de manera **responsable, transparente y colaborativa**, manteniendo el control humano sobre las decisiones y garantizando calidad, seguridad y alineación con los estándares del equipo.