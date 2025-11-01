# Enfoque práctico-teórico

## La enseñanza del testing no puede seguir siendo teórica

En la mayoría de los programas de QA, los fundamentos se enseñan desconectados de la práctica real.  
Se habla de “casos de prueba”, “particiones”, “valores límite” o “automatización”, pero todo sucede en abstracto, sin contexto de código, sin herramientas reales y sin los problemas que un tester enfrenta cuando trabaja junto a desarrolladores.

En la industria, eso genera un vacío: testers que **conocen el vocabulario del testing**, pero no entienden cómo aplicarlo en un entorno de desarrollo moderno.  
Y también desarrolladores que **saben programar tests**, pero sin mentalidad de QA.

Mi enfoque parte de un principio sencillo:

> “El testing es una práctica de ingeniería, no un trámite de validación.”

Este libro enseña testing como lo haría un software engineer: **desde la comprensión del sistema, la lectura del código, la inferencia de comportamientos y el diseño de escenarios que rompan suposiciones**.

---

## Un método nacido en proyectos reales

La metodología que uso para enseñar QA viene de años trabajando con equipos que integran _frontend, backend y data pipelines_; ambientes donde las pruebas no son opcionales, sino esenciales para mantener el producto estable.

El enfoque combina tres pilares:

1. **Pensamiento de ingeniería** — aprender a razonar sobre causas, dependencias y efectos.  
   Antes de automatizar algo, entender qué se está validando y por qué.  
   El tester deja de ser ejecutor y pasa a ser **un diseñador de experimentos sobre el software**.

2. **Práctica dirigida con feedback inmediato** — cada concepto se prueba en código.  
   No se trata de leer sobre testing, sino de verlo en acción con herramientas como:

   - **Playwright** para tests de interfaz.
   - **Postman y Newman** para APIs.
   - **SQL** para verificar integridad de datos.
   - **GitHub Actions o Jenkins** para pipelines CI/CD.
   - **TypeScript y Python** para entender la lógica de los tests como software real.

3. **Razonamiento progresivo** — cada capítulo te lleva de la intuición al método:  
   primero explorás un problema, luego lo sistematizás, y finalmente lo automatizás.  
   Así se cierra el ciclo entre “saber detectar fallas” y “saber diseñar software resistente”.

---

## El marco de aprendizaje que usamos

He estructurado este libro (y mis cursos) en tres niveles que se retroalimentan:

| Nivel           | Propósito                                                                  | Resultado esperado                                 |
| --------------- | -------------------------------------------------------------------------- | -------------------------------------------------- |
| **Conceptual**  | Comprender los principios del testing como disciplina de ingeniería.       | Razonar sobre calidad, riesgo y diseño de pruebas. |
| **Práctico**    | Aplicar las técnicas en contextos reales de desarrollo.                    | Crear, ejecutar y automatizar tests relevantes.    |
| **Estratégico** | Integrar el testing dentro del ciclo de desarrollo (Scrum, CI/CD, DevOps). | Diseñar una estrategia de QA moderna y sostenible. |

El objetivo no es que “sepas usar herramientas”, sino que **entiendas la relación entre teoría, práctica y entrega continua**.

---

## Cómo se combina la teoría con la práctica

Cada tema teórico se enseña de forma **iterativa**.  
No leés primero y aplicás después: **aprendés mientras aplicás.**

El proceso es más o menos así:

1. **Introducción conceptual** — entendemos el principio.  
   Ejemplo: “¿Qué es una clase de equivalencia y por qué reduce la cantidad de pruebas sin perder cobertura?”

2. **Exploración práctica** — probamos ese principio con código real.  
   Por ejemplo, usando un método simple (`substringsBetween()`) o una API real.

3. **Generalización del modelo** — analizamos el patrón detrás del caso.  
   Qué hace que ese ejemplo sea aplicable a cualquier otro problema.

4. **Automatización o análisis de impacto** — integramos el conocimiento al entorno de desarrollo (scripts, pipelines, reportes).

Este modelo no es lineal; está diseñado para que puedas volver atrás, refinar tu comprensión y mejorar tus tests como lo haría un desarrollador al refactorizar código.

---

## El testing como forma de pensar

Uno de los errores más comunes al enseñar QA es presentar el testing como una secuencia de tareas.  
Para mí, el testing es un **modelo mental**: una forma de razonar sobre sistemas complejos, detectar ambigüedades y desafiar las suposiciones implícitas en el software.

En mis cursos y mentorías suelo decir:

> “Un buen tester no busca bugs; busca los puntos donde el sistema asume que no habrá problemas.”

Por eso este libro pone tanto énfasis en desarrollar esa mentalidad.  
No se trata solo de técnicas, sino de **entrenar la capacidad de pensar como un ingeniero de calidad.**

---

## La integración con el entorno moderno

Cada capítulo tiene ejemplos que se conectan con las herramientas y entornos que un QA moderno realmente usa:

- **Repositorios Git con pipelines CI/CD.**  
  Cómo se ejecutan los tests automáticamente al hacer un commit.

- **Bases de datos reales y queries SQL.**  
  Cómo validar integridad, relaciones y límites de datos.

- **Pruebas en frontend y backend.**  
  Cómo observar comportamientos a nivel API, UI y dominio.

- **Integración con frameworks de testing.**  
  Ejemplos en Playwright, Pytest, JUnit y Jest, explicando los fundamentos comunes.

El objetivo es que, al terminar el libro, entiendas cómo encaja tu trabajo de QA dentro del **flujo completo de desarrollo y entrega de software.**

---

## Enseñar con propósito

Como formador, no busco que memorices herramientas ni frameworks, sino que entiendas su función dentro del sistema.  
Cada técnica que vas a ver tiene un propósito detrás:

- No se automatiza por moda, sino por eficiencia.
- No se miden coberturas por ego, sino por riesgo.
- No se testea para encontrar errores, sino para **aumentar la confiabilidad del producto.**

Este enfoque te prepara para trabajar con equipos técnicos, hablar el mismo lenguaje que los developers y aportar valor desde el conocimiento, no desde la ejecución repetitiva.

---

## En síntesis

Este libro une teoría e ingeniería.  
Su meta no es enseñarte a testear más, sino **a pensar mejor**.  
A mirar el código, los datos, los entornos y las decisiones con ojos de alguien que entiende cómo todo encaja en la arquitectura del software.

Si aplicás lo que está acá, no solo vas a escribir mejores pruebas:  
vas a construir sistemas más confiables, equipos más eficientes y una mentalidad más sólida como QA Engineer.

---

_— Anderson Josue Oroya_  
_Software Engineer_  
_Buenos Aires, 2025_
