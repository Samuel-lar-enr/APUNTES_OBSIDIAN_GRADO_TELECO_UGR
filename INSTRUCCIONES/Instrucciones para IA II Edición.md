# Instrucciones generales para IA – Creación de apuntes para Obsidian (ciencias y técnicas)

## 0. Filosofía de trabajo

> **Cada concepto debe explicarse como si el estudiante lo viera por primera vez, desglosando cada paso, mostrando explícitamente las conexiones con otros temas y sin dar nada por supuesto. La claridad y la profundidad son prioritarias sobre la brevedad.**

---

## 1. Reglas de formato críticas (para que funcione en Obsidian)

### 1.1. Matemáticas y símbolos
- Usa **siempre** `$ ... $` para expresiones matemáticas inline.
- Usa **siempre** `$$ ... $$` para ecuaciones en bloque centradas.
- **Nunca** uses comillas invertidas alrededor de los delimitadores `$` (es decir, evita `` `$` `` o `` $` ``). Eso rompe el renderizado en Obsidian.
- Para vectores, usa `$\vec{v}$` (o `$\mathbf{v}$` si prefieres negrita).
- Para unidades, escribe dentro del math: `$\text{m/s}$`.

### 1.2. Estructura de títulos
- Usa `# Título principal` (solo uno por nota).
- Usa `## Sección` y `### Subsección` para jerarquizar.
- No uses títulos con formato raro (ej. `# 1. Introducción` es correcto; evita `#1` sin espacio).

### 1.3. Enlaces internos
- Usa `[[#Nombre de la sección]]` para enlazar dentro de la misma nota.
- Para enlazar a otra nota, usa `[[Nombre de la nota]]` o `[[Nombre de la nota#Sección]]`.
- Asegúrate de que el texto después de `#` coincida exactamente con el título de la sección.

### 1.4. Callouts [MODIFICADO: añadido `[!NonExample]`]
Usa la sintaxis de Obsidian:
```markdown
> [!Definition]
> [!Theorem]
> [!Example]
> [!Algorithm]
> [!Important]
> [!Note]
> [!Tip]
> [!Warning]
> [!Connection]
> [!Summary]
> [!NonExample]   [NUEVO]
```
**Nota:** No dejes espacios después de `>` y antes de `[!`; el contenido debe ir en la línea siguiente con una sangría o inmediatamente debajo.

---

## 2. Estructura obligatoria de cada apunte (plantilla general)

```markdown
# [Título del tema]

> [!NOTE] Prerrequisitos
> - Concepto A ([[#Enlace o nota externa]])
> - Concepto B
> - Habilidad C (ej. manejo de integrales, álgebra matricial, etc.)

## Índice [MODIFICADO: énfasis en enlaces funcionales]
1. [[#1. Motivación y contexto]]
2. [[#2. Conceptos fundamentales]]
   2.1. [[#2.1. Definición principal]]
   2.2. [[#2.2. Propiedades clave]]
3. [[#3. Procedimientos/Algoritmos]]
4. [[#4. Ejemplos resueltos]]
5. [[#5. Conexiones con otros temas]]
6. [[#6. Resumen de fórmulas (tabla)]]
7. [[#7. Mapeo de ejercicios (si los hay)]]
8. [[#8. Errores comunes y consejos]]
9. [[#9. Síntesis]]
10. [[#10. Anexos]] [NUEVO]

> [!Important] Verificación de enlaces
> Asegúrate de que los títulos del índice coincidan exactamente con los títulos de las secciones.

## 1. Motivación y contexto
[Explicar por qué este tema es útil, qué problema resuelve, aplicaciones reales.]

## 2. Conceptos fundamentales
### 2.1. Definición principal
> [!Definition] Nombre
> Definición formal.
**Desglose de la definición**: explicar cada símbolo o término nuevo.

### 2.2. Propiedades clave
- Propiedad 1 (con justificación breve).
- Propiedad 2 (con ejemplo o contraejemplo si procede).

## 3. Procedimientos / Algoritmos
> [!Algorithm] Pasos para hacer [algo]
> 1. Primer paso.
> 2. Segundo paso.
> 3. ... (hasta completar)

## 4. Ejemplos resueltos
> [!Example] Ejemplo 1: [título]
> **Enunciado**: ...
> **Datos**: (si aplica, incluir valores numéricos, constantes, masas molares, etc.)
> **Solución** (paso a paso):
> - Paso 1: ...
> - Paso 2: ...
> - Resultado final.

(Incluir al menos dos ejemplos, uno muy sencillo y otro más complejo.)

## 5. Conexiones con otros temas
> [!Connection] 
> - Esto se relaciona con [[Tema anterior#Sección]] porque ...
> - Este concepto es la base de [[Tema posterior#Sección]].

## 6. Resumen de fórmulas (tabla)
| Concepto | Expresión | Condiciones / Notas |
|----------|-----------|----------------------|

## 7. Mapeo de ejercicios (si se proporciona una lista)
| Nº | Enunciado breve | Sección del apunte donde se resuelve o explica |

## 8. Errores comunes y consejos
> [!Warning] Error común 1
> Descripción y cómo evitarlo.
> [!Tip] Consejo práctico
> ...

## 9. Síntesis
> [!Summary]
> Resumen de las ideas más importantes del tema en un párrafo.

## 10. Anexos [NUEVO]
- Tablas de constantes y conversiones.
- Diagramas de flujo.
- Material complementario.
```

---

## 3. Contenido obligatorio por cada ley, teorema o procedimiento [MODIFICADO: añadido `[!NonExample]`]

- **Motivación** (¿por qué necesitamos esto?).
- **Desglose de la fórmula o enunciado** (explica cada símbolo).
- **Deducción paso a paso** (si es posible, muestra de dónde viene la fórmula, no la des por supuesta).
- **Algoritmo paso a paso** (si aplica).
- **Al menos un ejemplo resuelto completo** (todos los pasos, sin saltos).
- **Intuición geométrica o física** (descripción en palabras, reglas nemotécnicas).
- **Conexiones explícitas** con otros temas (usar `> [!Connection]`).
- **Errores comunes** (usar `> [!Warning]`).
- **Non‑example** (usar `> [!NonExample]`): qué no es, o cuándo no se aplica. [NUEVO]

---

## 4. Requisitos adicionales para tu estilo de aprendizaje

- **Desglose fino**: No des por supuesto ningún paso algebraico, integral o manipulación simbólica. Muestra sustituciones, cambios de variable, etc.
- **Conexiones visibles**: Usa frases como “Esto se relaciona con X porque...”, “Observa la analogía con Y...”.
- **Autocontenido**: El apunte debe poder leerse sin buscar fuera. Si mencionas un concepto de otro tema, resúmelo brevemente o enlázalo.
- **Preguntas implícitas**: Cuando expliques una ley, incluye “¿Qué pasaría si...?” o “¿Por qué no puede ser de otra forma?”.
- **Resumen ejecutivo por sección**: Al final de cada sección larga, añade un pequeño párrafo de síntesis.

---

## 5. Reglas específicas para evitar omisiones comunes [MODIFICADO: añadidas secciones 5.9 y 5.10]

### 5.1. Ejemplos: nunca dejes un desarrollo pendiente
- **Prohibido** escribir frases como “ver desarrollo completo en el Apunte A” o “se omite por brevedad”. Si el ejemplo es largo, se incluye igualmente, aunque ocupe espacio.
- **Regla de oro**: cada ejemplo mencionado debe estar completamente resuelto dentro del apunte, con todos los pasos intermedios.
- **Incluye siempre una sección “Datos”** en los ejemplos numéricos, con todos los valores necesarios (constantes físicas, masas atómicas, etc.). No asumas que el estudiante los sabe de memoria.

### 5.2. Deducción de fórmulas (muy importante)
- **No limites a enunciar una fórmula**. Siempre que sea posible, **muestra de dónde viene**:
  - Parte de una ley fundamental.
  - Realiza las sustituciones algebraicas paso a paso.
  - Explica cada manipulación (multiplicar, dividir, tomar logaritmos, integrar, etc.).
- **Después de deducir la fórmula, recuadra el resultado final** y ponlo en un `> [!Tip]` o en un recuadro destacado.

### 5.3. Procedimientos con múltiples pasos
- Si el procedimiento tiene varios pasos, numéralos y explica **por qué** se hace cada uno.
- Incluye al menos un ejemplo completo con números, paso a paso.

### 5.4. Tablas de casos o condiciones
- Cuando una ley o fórmula tenga variantes según condiciones (ej. medio ácido/básico, dominio del parámetro, etc.), **incluye una tabla** que resuma los casos y la condición de aplicación.
- Añade una nota que explique cómo elegir el caso correcto.

### 5.5. Verificación de cobertura del material fuente
- Antes de entregar, la IA debe comparar su índice con el índice del PDF o material fuente. Cada sección principal del PDF debe tener una correspondencia en el apunte.
- Si el PDF tiene un ejemplo numerado, debe aparecer en el apunte con el mismo número y resuelto por completo.

### 5.6. Autosuficiencia de los preliminares
- Los preliminares (integrales, identidades, reglas de derivación, propiedades de logaritmos, etc.) deben incluirse en el mismo apunte, no dejar como “se espera que el alumno los sepa”. Si son muy extensos, se puede hacer un resumen con las fórmulas esenciales.

### 5.7. Tablas de datos auxiliares [MODIFICADO: formato estandarizado]
- Cuando los ejemplos requieran valores numéricos externos (masas atómicas, constantes físicas, densidades, etc.), **proporciónalos en una tabla** al inicio del tema o dentro del ejemplo. No asumas que el estudiante los buscará.
- **Formato estándar de tablas de constantes:**
```markdown
| Constante | Símbolo | Valor | Unidades |
|-----------|---------|-------|----------|
| Constante de los gases | $R$ | $8.314$ | J/(mol·K) |
```

### 5.8. Árboles de decisión o diagramas de flujo
- Para elegir entre diferentes métodos o aproximaciones, **incluye un diagrama de flujo o una tabla de condiciones** (ej. “si se cumple A, usar método X; si no, método Y”).
- Esto ayuda a que el estudiante no memorice ciegamente, sino que aprenda a decidir.

### 5.9. Discrepancias con soluciones oficiales [NUEVO]
- Si un ejemplo o problema resuelto en el apunte no coincide con la solución proporcionada en el material fuente (boletín, libro, etc.), el apunte debe indicarlo explícitamente mediante una nota `> [!Warning]`, **pero debe ofrecer un desarrollo autocontenido que justifique el resultado obtenido**.
- Si los datos del enunciado son inconsistentes o ambiguos, se debe explicar la ambigüedad y, si es posible, presentar la solución para la interpretación más razonable.
- **Queda prohibido** presentar un ejemplo que termine con "los datos no cuadran" sin ofrecer una solución alternativa y verificable.
- Si la discrepancia persiste, el ejemplo debe ser **sustituido por uno equivalente** con datos consistentes que permita una resolución completa.

### 5.10. Ejemplos lineales y autocontenidos (prohibición de autocorrecciones)
- **Prohibido** incluir en el apunte el proceso de ensayo-error o las dudas del redactor. El apunte debe presentar la solución **correcta y limpia desde el principio**.
- Si un ejemplo es complejo y requiere varias etapas, estas deben presentarse de forma **lineal y ordenada**, sin interrupciones ni notas que digan "esto no funciona" o "mejor redefinimos".
- Si se detecta que un ejemplo no es autoconsistente, se debe reescribir desde cero, no parchear con notas aclaratorias.

### 5.11. Enlaces externos a fuentes y recursos complementarios

Cuando el material fuente (PDF, libro, artículo, etc.) incluya enlaces externos, referencias web o códigos QR, la IA debe incorporarlos al apunte en una sección específica de "Enlaces externos". Esto permite que el estudiante acceda directamente a los recursos originales sin tener que buscar el material fuente.

#### Reglas para incluir enlaces externos

1. **Detección**: La IA debe revisar el material fuente en busca de:
   - URLs completas (http:// o https://)
   - Referencias a sitios web (ej. "ver https://...")
   - Códigos QR que apunten a recursos externos
   - Nombres de plugins o herramientas mencionados con sus repositorios

2. **Formato obligatorio**: Los enlaces externos deben escribirse usando **sintaxis Markdown estándar**, no wikilinks. La sintaxis correcta es:
   ```markdown
   [Texto descriptivo](https://url-del-recurso)
   ```

   > [!Warning] Diferencia crítica entre enlaces internos y externos
   > - **Enlaces internos** (a otras notas de la bóveda): usan `[[Nombre de la nota]]` o `[[Nombre#Sección]]`.
   > - **Enlaces externos** (a sitios web, documentación, repositorios): usan `[Texto](https://url)`.
   > - **Nunca** uses wikilinks `[[https://...]]` para URLs externas, ya que Obsidian los trataría como enlaces internos y podría crear notas vacías.

3. **Estructura de la sección**: Al final del apunte (después de la sección 10. Anexos), añadir una sección con el siguiente formato:

```markdown
## 11. Enlaces externos [NUEVO]

> [!Note] Recursos complementarios
> Esta sección recopila los enlaces externos proporcionados en el material fuente original.

### Documentación oficial
- [Nombre del recurso](https://url-del-recurso) — Breve descripción.

### Referencias bibliográficas
- [Título del artículo o libro](https://doi.org/...) — Breve descripción.

### Recursos adicionales
- [Título del recurso](https://url) — Breve descripción.
```

4. **Descripción obligatoria**: Cada enlace debe ir acompañado de una **breve descripción** (una línea) que explique qué contiene o para qué sirve. Esto ayuda al estudiante a decidir si le interesa visitarlo.

5. **Verificación de enlaces**: Antes de entregar el apunte, la IA debe verificar que:
   - [ ] Todos los enlaces externos usan sintaxis Markdown `[texto](url)`.
   - [ ] Ningún enlace externo usa wikilinks `[[ ]]`.
   - [ ] Cada enlace tiene una descripción asociada.
   - [ ] Los enlaces están agrupados por categorías (documentación, herramientas, referencias, etc.).

4. **Si no hay enlaces externos en el material fuente**: La sección debe omitirse.
   
---

## 6. Verificación de calidad (autochequeo para la IA) [MODIFICADO: añadidas dos comprobaciones]

Antes de entregar el apunte, la IA debe verificar:
- [ ] ¿He explicado cada símbolo de cada fórmula importante?
- [ ] ¿He incluido al menos dos ejemplos resueltos paso a paso?
- [ ] ¿He indicado explícitamente al menos dos conexiones con otros temas?
- [ ] ¿He evitado usar `` `$` `` o `` $` `` ?
- [ ] ¿El índice está al principio y los enlaces son funcionales?
- [ ] ¿Hay una tabla de resumen de fórmulas?
- [ ] ¿Hay un apartado de errores comunes?
- [ ] ¿El formato math es consistente?
- [ ] **¿He resuelto completamente todos los ejemplos sin dejar referencias externas?**
- [ ] **¿He deducido las fórmulas clave mostrando los pasos algebraicos (no solo enunciadas)?**
- [ ] **¿En los ejemplos numéricos he incluido una sección “Datos” con todos los valores necesarios?**
- [ ] **¿He proporcionado tablas auxiliares (casos, condiciones, constantes) cuando son relevantes?**
- [ ] **¿He verificado que los resultados numéricos de los ejemplos coinciden con los del material fuente (cuando existen)?** [NUEVO]
- [ ] **Si no coinciden, ¿he incluido una nota explicativa y he ofrecido una solución alternativa autocontenida?** [NUEVO]
- [ ] **¿He incluido al menos un `[!NonExample]` para conceptos clave?** [NUEVO]
- [ ] **¿He evitado incluir procesos de ensayo-error en los ejemplos?** [NUEVO]

---

## 7. Instrucción final para la IA [MODIFICADO: añadidas referencias a las nuevas reglas]

> **Siempre que se te pida crear apuntes para Obsidian sobre cualquier tema científico o técnico, aplica estas instrucciones al pie de la letra. Prioriza la claridad, el desglose y las conexiones sobre la concisión. No omitas desarrollos de ejemplos ni dejes “tarea para el alumno”. Siempre que sea posible, muestra de dónde viene cada fórmula, incluye los datos numéricos necesarios y proporciona tablas auxiliares. Si algo no está claro en el material fuente, pide aclaración o haz una suposición razonable y menciónala en una nota.**
>
> **Recuerda las reglas específicas sobre discrepancias con soluciones oficiales (5.9) y la prohibición de autocorrecciones en ejemplos (5.10). El objetivo es que el apunte sea autocontenido, consistente y pueda entenderse sin consultar ninguna otra fuente.**

---

## Resumen de mejoras

| Sección | Mejora                                                    | Justificación                                                                                         |
| ------- | --------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| 1.4     | Añadido `[!NonExample]` a la lista de callouts            | Los non‑examples son una herramienta didáctica muy útil que debe estar disponible desde el principio. |
| 2       | Énfasis en la verificación de enlaces del índice          | Evita enlaces rotos en el apunte final.                                                               |
| 3       | Añadido `[!NonExample]` como contenido obligatorio        | Refuerza la importancia de los contraejemplos.                                                        |
| 5.7     | Estandarización del formato de tablas de constantes       | Facilita la consulta rápida de datos.                                                                 |
| 5.9     | Regla para manejar discrepancias con soluciones oficiales | Evita iteraciones infinitas de corrección (como ocurrió con el péndulo físico).                       |
| 5.10    | Prohibición de autocorrecciones en ejemplos               | Evita ejemplos caóticos (como ocurrió con el ciclo del Tema 12).                                      |
| 6       | Añadidas comprobaciones de verificación                   | Refuerza la calidad del producto final.                                                               |

---

## Conclusión

Las instrucciones actuales son **excelentes y han demostrado su eficacia**. Las mejoras propuestas son refinamientos que:

1. **Previenen problemas específicos** que surgieron durante la creación de los temas 9-12.
2. **Estandarizan** aspectos como tablas de constantes y ejemplos numéricos.
3. **Refuerzan** la autocontención y consistencia de los apuntes.
4. **Incorporan** la experiencia práctica de 13 temas de trabajo.

Con estas mejoras, las instrucciones quedarán aún más robustas y reducirán la necesidad de iteraciones correctivas en el futuro.