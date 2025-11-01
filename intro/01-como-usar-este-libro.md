# Cómo usar este libro

## Este no es un libro para aprender desde cero

Este libro nació porque muchas personas que trabajan como QA —incluso con años de experiencia— me han dicho lo mismo:  
_"sé hacer pruebas, pero no sé por qué las hago así"_.

Y eso es un síntoma claro de una deuda de fundamentos.

Durante años vi a testers repetir lo que les enseñaron otros testers, copiar estrategias, o depender del instinto para decidir qué probar.  
Y aunque eso puede funcionar, **no alcanza**.  
El testing profesional requiere pensamiento crítico, capacidad de abstracción y un entendimiento profundo del software que se está probando.

Por eso este libro no es un curso para principiantes.  
Está escrito para **quienes ya trabajan en QA, pero quieren dejar de “probar cosas” y empezar a pensar como ingenieros de software.**

---

## Cómo está pensado el recorrido

No hay teoría vacía ni ejercicios artificiales.  
Cada capítulo está estructurado como una **ruta de aprendizaje práctico**, donde cada concepto tiene un propósito claro:

1. **Idea principal**  
   Empiezo por el _por qué_ — el principio técnico que sustenta la práctica.  
   Si no entendés por qué algo es importante, no tiene sentido automatizarlo.

2. **Caso real o ejemplo con código**  
   Todos los ejemplos que aparecen acá son reales o basados en situaciones que encontré en proyectos con equipos de desarrollo.  
   No busco demostrar “cómo se hace”, sino **cómo pensar un test como una pieza de software**.

3. **Ejercicio guiado**  
   Cada capítulo te invita a crear o analizar algo.  
   Puede ser un test unitario, un test exploratorio, una matriz de equivalencias o una automatización con Playwright o Postman.  
   Si no lo ejecutás, no vas a incorporar la lógica que hay detrás.

4. **Reflexión técnica**  
   Al final de cada sección te propongo detenerte y pensar:
   - ¿Qué parte de este proceso podría automatizar?
   - ¿Qué errores estoy dejando pasar?
   - ¿Qué suposiciones tengo sobre el comportamiento del sistema?  
     Este punto es clave. Ser QA no es escribir tests: es **cuestionar los supuestos del software**.

---

## Cómo leerlo según tu perfil

### Si estás trabajando actualmente como QA manual

Leé este libro **como un puente hacia el pensamiento técnico.**  
No busques memorizar los términos. En su lugar, conectá cada concepto con algo que hayas vivido:  
un bug que no encontraste a tiempo, un ticket mal especificado, o un conflicto con el equipo de desarrollo.  
Cada ejemplo te va a mostrar cómo podrías haber razonado de forma más sistemática.

### Si estás transitando hacia QA Automation o QA Engineer

Usá este libro como un **mapa conceptual de ingeniería de testing**.  
Antes de escribir scripts, aprendé a diseñar buenos casos de prueba.  
Antes de medir cobertura, aprendé qué significa que una prueba tenga valor.  
Y antes de automatizar todo, aprendé qué **no** deberías automatizar.

### Si sos developer y querés mejorar tu testing

Este libro también te sirve.  
Gran parte de las prácticas vienen de la ingeniería de software:  
_design by contract, property-based testing, TDD, mocks, refactorización de tests_.  
Lo único que cambia es el punto de vista: el QA mira el sistema desde fuera, el Dev desde adentro.  
Ambos piensan con la misma lógica.

---

## Cómo avanzar

Podés leerlo de forma lineal o saltar entre capítulos.  
Sin embargo, si estás siguiendo mi curso express o mentoreo, esta es la secuencia que recomiendo:

1. **Parte I** — Para entender el propósito del testing y cambiar tu mentalidad.
2. **Parte II** — Para dominar las técnicas formales y sistemáticas (equivalencias, fronteras, especificaciones).
3. **Parte III** — Para integrar automatización con criterio.
4. **Parte IV** — Para aprender a diseñar estrategias de QA que se integren con el ciclo de desarrollo.
5. **Parte V** — Para proyectarte como QA Engineer completo, ético y actualizado.

Cada parte está pensada como un paso hacia la autonomía profesional.

---

## Cómo aprovechar los recursos

Todo el contenido está organizado en carpetas dentro del proyecto:

- `/diagramas/` → Diagramas Mermaid de cada concepto clave (pueden abrirse y editarse).
- `/ejercicios/` → Actividades prácticas con código y ejemplos reales.
- `/apendices/` → Glosario, plantillas de reportes y soluciones.
- `/recursos/` → Referencias y bibliografía complementaria.

Si estás usando GitBook, Docusaurus o VitePress, este libro ya está estructurado para funcionar como **documentación navegable**.  
Podés leerlo, modificarlo o integrarlo con tus propios ejemplos.

---

## Cómo evaluar tu progreso

En cada capítulo vas a encontrar tres preguntas para ti mismo:

1. ¿Qué entendía por intuición y ahora puedo explicar con fundamentos?
2. ¿Qué podría mejorar en mi práctica actual usando lo que aprendí hoy?
3. ¿Qué conceptos me generaron dudas que necesito investigar más?

Responderlas te permite medir tu progreso real, no en cantidad de páginas, sino en **criterio profesional adquirido**.

---

## En resumen

No uses este libro como una receta.  
Usalo como una herramienta para **reconstruir tu forma de pensar las pruebas**.

Mi objetivo como software engineer y formador es que al terminarlo no digas  
_"sé probar mejor"_,  
sino **"entiendo por qué mi trabajo tiene impacto técnico en el software"**.

---

_— Josué Oroya_  
_Software Engineer & Founder at AikoDev_  
_Córdoba, 2025_
