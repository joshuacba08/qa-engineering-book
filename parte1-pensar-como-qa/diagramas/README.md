# Diagramas del libro QA Engineering: Fundamentos Profesionales del Testing Moderno

Este directorio contiene los diagramas visuales que acompañan los capítulos del libro.  
Cada uno representa una idea conceptual que suelo explicar en mis clases para que los testers entiendan **cómo pensar el testing** más allá de la ejecución.

Los diagramas están en formato `.mmd` (Mermaid) y `.md` (Markdown plano).  
Pido disculpas si parece que los diagramas se ven aburridos o sin vida. Tuve que escribirlos sin caracteres especiales, acentos ni estilos complejos, para asegurar compatibilidad con renderizadores como el editor de Markdown que uso: **Typora**, o el renderizador de Mermaid que tiene **GitHub**.

---

## 1. `mapa-riesgo-software.mmd`

### Propósito

Visualiza los **tipos de riesgo** que puede tener un sistema de software y cómo cada tipo se relaciona con una familia de pruebas.  
Es el primer diagrama que uso cuando introduzco el concepto de _testing como gestión del riesgo_.

### Cómo leerlo

- El nodo principal es el sistema en desarrollo.
- A partir de ahí se ramifican las áreas de riesgo: funcional, técnico, integración, performance y seguridad.
- Cada una se asocia con un tipo de test que ayuda a reducirla.

### Cuándo usarlo

Durante la fase de **estrategia de pruebas** o cuando explico por qué un equipo necesita más de un tipo de QA (manual, automatizado, de performance, de seguridad, etc.).

---

## 2. `tabla-tipos-errores.md`

### Propósito

Sirve como **referencia teórica** para vincular tipos de errores con tipos de prueba.  
Funciona como una tabla de decisión general para todo el libro.

### Cómo leerla

Cada fila describe un tipo de error típico:

- qué significa,
- un ejemplo práctico,
- y el tipo de prueba más adecuado para detectarlo.

### Cuándo usarla

En mis cursos la uso en clase 1 o 2 para que los alumnos completen la tabla con ejemplos propios de sus proyectos.  
Les enseña a **pensar el testing como prevención**, no solo como detección.

---

## 3. `flujo-decision-tree.mmd`

### Propósito

Muestra cómo un sistema toma decisiones a partir de validaciones secuenciales.  
Representa el razonamiento lógico detrás del _diseño de casos de prueba_.

### Cómo leerlo

1. **Entrada del dato** (lo que recibe el sistema).
2. **Validaciones**: formato, rango, reglas de negocio.
3. **Acciones**: mostrar error, rechazar o procesar.

Cada nodo con forma de rombo representa una **condición**, y cada camino (Sí / No) corresponde a **un caso de prueba** que deberías diseñar.

### Cuándo usarlo

Ideal para enseñar a derivar casos a partir de requisitos o lógica condicional, especialmente en el **Capítulo 2** (Diseño de tests) y el **Capítulo 4** (Testing estructural).

---

## Consejos para trabajar con los diagramas

> Nota  
> Estos diagramas no reemplazan el texto del libro, lo complementan.  
> Cada uno puede copiarse dentro de los capítulos para reforzar el concepto correspondiente.

- No uses acentos, ñ o paréntesis dentro de los nodos si estás renderizando en Typora.
- Si un diagrama falla, probalo en [https://mermaid-js.github.io/mermaid-live-editor](https://mermaid-js.github.io/mermaid-live-editor) para verificar su sintaxis.
- Podés extenderlos o modificarlos: los `.mmd` son solo texto.
- Si eres formador y trabajas con tus alumnos en GitBook, estos archivos se pueden **incrustar directamente** en los capítulos.
- No dudes en contactarme si necesitas ayuda para adaptar los diagramas a tu curso o proyecto.
- Agradecería mucho que puedas mencionar mi autoría si los usas en presentaciones o materiales públicos.

---

## Objetivo pedagógico

Como formador, uso estos diagramas para que el alumno:

1. Pueda **visualizar el razonamiento del tester profesional**.
2. Comprenda que cada tipo de prueba **reduce un riesgo distinto**.
3. Entienda que el diseño de tests es un proceso **lógico y comunicable**, no un acto aislado.

---

**Autor:** Josue Oroya  
**Academia:** AikoDev  
**Versión:** 1.0  
**Última actualización:** 2025-11-01
