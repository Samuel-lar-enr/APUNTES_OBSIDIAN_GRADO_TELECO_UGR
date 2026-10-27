# TEMA 1: Introducción a la informática y conceptos básicos — Secciones expandidas

> [!Note] Instrucciones de uso
> Este documento contiene **únicamente las secciones expandidas** de las que en la revisión anterior marqué como "falta desglose". El resto del apunte permanece exactamente igual. Cada sección aquí presente **sustituye** a la sección correspondiente del apunte original.

---

## 2.1. Definición de informática (página 4) — EXPANDIDA

> [!Note] Contenido literal de la página 4
> **El estudio del tratamiento automático de la información mediante computadores.**
>
> **REPRESENTAR**
> **ORGANIZAR**
> **PROCESAR**
>
> La informática estudia cómo representar, organizar y procesar información de forma automática.
>
> **1 / 19**

> [!Note] Nota pedagógica de la página 4
> "La informática estudia el tratamiento automático de la información mediante computadores. Representar consiste en codificar la información; organizar, en estructurarla y almacenarla; procesar, en aplicar operaciones para obtener resultados. La siguiente diapositiva introduce el computador como máquina que permite realizar estas tareas. Se mantiene una explicación general, sin el ejemplo de una compra."

> [!Definition] Informática
> La informática es el **estudio del tratamiento automático de la información mediante computadores**. Incluye:
> - **Representar**: codificar la información.
> - **Organizar**: estructurarla y almacenarla.
> - **Procesar**: aplicar operaciones para obtener resultados.

**Desglose exhaustivo de cada término**:

**1. "Estudio"**: no es solo una técnica, es una **disciplina científica** con fundamentos teóricos y prácticos. Estudia cómo se puede manipular información de forma sistemática.

**2. "Tratamiento"**: conjunto de operaciones que se aplican a la información. No es una sola operación, sino un **proceso completo** que va desde que entra el dato hasta que sale el resultado.

**3. "Automático"**: las operaciones se realizan **sin intervención humana continua**. El humano programa la máquina una vez y esta ejecuta las operaciones repetidamente sin necesidad de que alguien esté pulsando botones. Esto es lo que diferencia un computador de una calculadora manual.

**4. "Información"**: cualquier dato que pueda ser **codificado**: números, texto, imágenes, sonido, vídeo, señales de sensores, etc. La información es la materia prima del tratamiento.

**5. "Mediante computadores"**: la herramienta principal es el computador, pero la informática también estudia los **algoritmos** y **métodos** que se pueden ejecutar en ellos.

**Desglose de las tres actividades**:

| Actividad | Definición | Ejemplo | Pregunta que responde |
|-----------|------------|---------|----------------------|
| **Representar** | Codificar la información en un formato que el computador pueda manejar. | Convertir la letra 'A' a `01000001` (ASCII). | ¿Cómo se codifica? |
| **Organizar** | Estructurar y almacenar la información para poder acceder a ella. | Guardar los datos en una base de datos, en un array, en un archivo. | ¿Dónde y cómo se guarda? |
| **Procesar** | Aplicar operaciones para obtener resultados. | Sumar dos números, ordenar una lista, buscar un patrón. | ¿Qué operaciones se hacen? |

**¿Por qué se distingue entre representar, organizar y procesar?**

Porque son **fases distintas** y cada una tiene sus propios problemas y soluciones:

- **Representar**: ¿qué código uso? ¿cuántos bits necesito? ¿es eficiente?
- **Organizar**: ¿uso un array, una lista, un árbol? ¿cómo accedo rápido?
- **Procesar**: ¿qué algoritmo uso? ¿cuántos pasos necesita? ¿es correcto?

Si confundes representar con procesar, no entenderás por qué un mismo patrón de bits (`01000001`) puede significar cosas distintas según el código (ASCII = 'A'; entero = 65; instrucción máquina = sumar).

> [!NonExample] Qué no es la informática
> La informática **no** es solo "usar ordenadores" ni "programar". Es una disciplina científica que estudia:
> - La representación de la información.
> - La arquitectura de las máquinas que la procesan.
> - Los algoritmos y programas que la transforman.
> - La comunicación entre sistemas.
>
> Tampoco es sinónimo de "tecnología" en general: la informática se centra en el procesamiento automático de información, no en la fabricación de hardware ni en las telecomunicaciones por sí mismas.

> [!Important] Pregunta implícita
> ¿Por qué es importante distinguir "representar", "organizar" y "procesar"? Porque son tres fases distintas del tratamiento de la información. Si confundes representar con procesar, no entenderás por qué un mismo patrón de bits puede significar cosas distintas según el código.
>
> ¿Qué pasaría si no se organizara la información? No se podría acceder a ella de forma eficiente. Imagina una biblioteca sin estanterías ni catálogo: todos los libros amontonados. Encontrar uno sería imposible. La organización es lo que permite el acceso rápido.

**Intuición**: La informática es como una fábrica de transformación de información:
- **Representar** = preparar la materia prima (codificar).
- **Organizar** = almacenarla en el almacén (estructurar).
- **Procesar** = fabricar el producto (aplicar operaciones).
- **Computador** = la fábrica completa.

> [!Summary] Resumen ejecutivo de 2.1
> La informática estudia el tratamiento automático de la información: representar (codificar), organizar (estructurar y almacenar) y procesar (aplicar operaciones). No es solo "usar ordenadores", sino una disciplina científica con fundamentos teóricos y prácticos. Cada actividad tiene sus propios problemas y soluciones.

---

## 2.2. El computador como máquina programable (página 5) — EXPANDIDA

> [!Note] Contenido literal de la página 5
> [Imagen de un computador de sobremesa con monitor, torre abierta, teclado, ratón y lupa]
>
> **RECIBE datos**
> **PROCESA con instrucciones**
> **ALMACENA datos y resultados**
> **PROPORCIONA resultados**
>
> **2 / 19**

> [!Note] Nota pedagógica de la página 5
> "Informática: tratamiento automático de la información. Un computador es una máquina electrónica programable que recibe, procesa, almacena y proporciona datos. Ejemplo oral: recibe unidades y precio, calcula el importe, lo guarda y lo muestra. La ilustración anticipa componentes, sin explicarlos todavía."

> [!Definition] Computador
> Un computador es una **máquina electrónica programable** que:
> - **Recibe** datos (entrada).
> - **Procesa** con instrucciones (CPU).
> - **Almacena** datos y resultados (memoria y almacenamiento).
> - **Proporciona** resultados (salida).

**Desglose exhaustivo de cada operación**:

**1. "Recibe datos"** (Entrada):
- El computador necesita **materia prima**: datos del exterior.
- Los datos pueden venir de un teclado, un ratón, un sensor, un archivo, la red, etc.
- Sin datos, el computador no tiene nada que procesar.
- **Pregunta que responde**: ¿qué información entra?

**2. "Procesa con instrucciones"** (CPU):
- El computador **transforma** los datos siguiendo un conjunto de instrucciones (el programa).
- Las instrucciones le dicen qué operaciones hacer: sumar, comparar, mover, saltar, etc.
- El procesamiento es lo que convierte datos de entrada en resultados.
- **Pregunta que responde**: ¿qué se hace con los datos?

**3. "Almacena datos y resultados"** (Memoria y almacenamiento):
- El computador necesita **guardar** tanto los datos de entrada como los resultados intermedios y finales.
- Hay dos tipos de almacenamiento: **memoria principal** (RAM, volátil, rápida) y **almacenamiento** (disco, persistente, lento).
- Sin almacenamiento, no se podrían hacer cálculos con múltiples pasos.
- **Pregunta que responde**: ¿dónde se guarda?

**4. "Proporciona resultados"** (Salida):
- El computador **comunica** los resultados al exterior.
- Los resultados pueden ir a una pantalla, una impresora, un actuador, un archivo, la red, etc.
- Sin salida, el procesamiento no tendría utilidad visible.
- **Pregunta que responde**: ¿qué información sale?

**Desglose de los adjetivos**:

- **"Electrónica"**: funciona con circuitos digitales que manejan dos estados (0 y 1). No es mecánico ni analógico (aunque pueda tener componentes analógicos en la entrada/salida).
- **"Programable"**: puede ejecutar **distintas tareas** según las instrucciones que se le den. No está limitado a una sola función. Esta es la característica clave que distingue un computador de una calculadora.

**Ejemplo completo con el hilo conductor del material**:

| Fase | Operación | Ejemplo: calcular importe de compra |
|------|-----------|-------------------------------------|
| Recibe | Entrada de datos | Unidades = 5; Precio = 3 € |
| Procesa | Aplicar instrucciones | Multiplicar 5 × 3 = 15 |
| Almacena | Guardar datos y resultados | Guardar 15 en memoria |
| Proporciona | Salida de resultados | Mostrar 15 € en pantalla |

> [!Example] Ejemplo oral del material
> Recibe unidades y precio, calcula el importe, lo guarda y lo muestra.
> - **Recibe**: unidades = 5, precio = 3.
> - **Procesa**: 5 × 3 = 15.
> - **Almacena**: guarda 15.
> - **Proporciona**: muestra 15.

> [!NonExample] Qué no es un computador
> - Una calculadora básica **no** es un computador de propósito general: no es programable (no puede ejecutar programas arbitrarios).
> - Un microondas con panel digital **no** es un computador de propósito general, aunque contenga un microcontrolador.
> - Un disco duro **no** es un computador: solo almacena.
> - Un router **no** es un computador de propósito general, aunque tenga procesador y memoria.
> - Una FPGA **no** es un computador de propósito general: es un dispositivo reprogramable a nivel de hardware.

> [!Important] Pregunta implícita
> ¿Qué pasaría si un computador no fuera programable? Entonces sería una máquina de propósito fijo, como una calculadora. La programabilidad es lo que permite ejecutar distintas tareas sin cambiar el hardware.
>
> ¿Por qué no puede ser de otra forma? Porque las cuatro operaciones (recibir, procesar, almacenar, proporcionar) son **necesarias y suficientes** para cualquier tarea de tratamiento de información. Si falta alguna, el computador no puede completar el ciclo.

**Intuición**: El computador es como un chef que:
- **Recibe** ingredientes (datos).
- **Procesa** siguiendo una receta (instrucciones).
- **Almacena** en la nevera (memoria).
- **Proporciona** el plato terminado (resultados).
Si no tuviera receta (programa), no podría cocinar nada.

> [!Summary] Resumen ejecutivo de 2.2
> Un computador es una máquina electrónica programable que recibe datos, los procesa con instrucciones, los almacena y proporciona resultados. Las cuatro operaciones son necesarias y suficientes. La programabilidad es lo que lo distingue de una calculadora. No todo dispositivo electrónico es un computador: debe ser programable y de propósito general.

---

## 2.4. Bits y estados: dos caminos de ida y vuelta (página 8) — EXPANDIDA

> [!Note] Contenido literal de la página 8
> **Bits y estados: dos caminos de ida y vuelta**
> Cada cubito representa un estado posible.
>
> [Tabla con cubos: 1 bit → 2 estados; 2 bits → 4 estados; 3 bits → 8 estados; 4 bits → 16 estados; 5 bits → 32 estados; 6 bits → 64 estados]
>
> **n bits → 2^n estados**
> **N estados → ⌈log₂(N)⌉ bits**
>
> [Gráfico de log₂(estados) vs Número de estados, con línea que llega a 64]
>
> **5 / 19**

> [!Note] Nota pedagógica de la página 8
> "Cada cubito representa una combinación, no un bit. Para 1–6 bits se muestran 2,4,8,16,32,64 estados. Ida: con n bits hay 2^n estados. Vuelta: para N estados y código de longitud fija hacen falta techo(log2 N) bits. El gráfico muestra log2 N; si no es entero, se redondea hacia arriba. Ejemplo:64 estados →6 bits;10 estados→4 bits. El caso de tres bits se puede enumerar oralmente:000–111."

> [!Definition] Relación bits ↔ estados
> - **Ida**: $n$ bits → $2^n$ estados.
> - **Vuelta**: $N$ estados → $\lceil \log_2 N \rceil$ bits (redondeo hacia arriba).

**Desglose exhaustivo**:

**1. ¿Qué es un "estado"?**
Un estado es una **combinación posible** de bits. Por ejemplo, con 2 bits, los estados posibles son 00, 01, 10 y 11. Cada uno es un estado distinto.

**2. ¿Por qué cada cubito representa una combinación y no un bit?**
Porque la tabla muestra **cuántos estados** se pueden formar con $n$ bits. Cada cubito es un estado, no un bit. Para 3 bits hay 8 cubitos, que son las 8 combinaciones.

**3. Camino de ida: $n$ bits → $2^n$ estados**
- 1 bit → 2 estados: 0, 1.
- 2 bits → 4 estados: 00, 01, 10, 11.
- 3 bits → 8 estados: 000, 001, 010, 011, 100, 101, 110, 111.
- 4 bits → 16 estados.
- 5 bits → 32 estados.
- 6 bits → 64 estados.

La fórmula es:
$$N_{\text{estados}} = 2^n$$

**4. Camino de vuelta: $N$ estados → $\lceil \log_2 N \rceil$ bits**
Si sabemos cuántos estados necesitamos, ¿cuántos bits hacen falta?
$$n_{\text{min}} = \lceil \log_2 N \rceil$$

**¿Por qué techo (redondeo hacia arriba)?**
Porque no puedes usar medio bit. Si $\log_2 N$ no es entero, necesitas el siguiente entero. Por ejemplo:
- $N = 64$: $\log_2 64 = 6$ → 6 bits exactos.
- $N = 10$: $\log_2 10 \approx 3{,}32$ → $\lceil 3{,}32 \rceil = 4$ bits.

**5. El gráfico logarítmico**
El gráfico muestra $\log_2(\text{estados})$ en el eje Y contra el número de estados en el eje X. La curva crece rápidamente al principio y luego se aplana. Esto refleja que **a más estados, más bits se necesitan, pero de forma logarítmica**: para 64 estados solo hacen falta 6 bits.

**6. Verificación con el caso de 3 bits**
Con 3 bits, los estados son: 000, 001, 010, 011, 100, 101, 110, 111. Son 8 estados. Y $2^3 = 8$. ✓

> [!Example] Ejemplo completo
> **¿Cuántos bits se necesitan para 100 estados?**
> $$n = \lceil \log_2 100 \rceil = \lceil 6{,}64 \rceil = 7\ \text{bits}$$
> Comprobación: $2^6 = 64 < 100$; $2^7 = 128 \geq 100$. ✓

> [!Important] Pregunta implícita
> ¿Qué pasa si $\log_2 N$ no es entero? Se redondea hacia arriba. No puedes usar medio bit. Por ejemplo, para 10 estados, $\log_2 10 \approx 3{,}32$, pero necesitas 4 bits porque con 3 solo tienes 8 estados.
>
> ¿Por qué no puede ser de otra forma? Porque con $n$ bits solo hay $2^n$ patrones posibles. Si $N > 2^n$, no hay suficientes patrones para distinguir todos los estados. Por eso se necesita $2^n \geq N$, y el menor $n$ entero que lo cumple es $\lceil \log_2 N \rceil$.

**Intuición del gráfico logarítmico**: Imagina que cada bit es un interruptor. Con 1 interruptor tienes 2 posiciones. Con 2, 4. Con 3, 8. El crecimiento es **exponencial** en el número de estados, pero **logarítmico** en el número de bits. Es como doblar una hoja de papel: cada doblez duplica el grosor, pero el número de dobleces crece muy lentamente.

> [!NonExample] Confusión frecuente
> No confundir "número de bits" con "número de estados". 6 bits **no** son 6 estados; son $2^6 = 64$ estados. La tabla muestra cubitos que representan **estados**, no bits.

> [!Summary] Resumen ejecutivo de 2.4
> $n$ bits → $2^n$ estados. $N$ estados → $\lceil \log_2 N \rceil$ bits (redondeo hacia arriba). El gráfico logarítmico muestra que a más estados, más bits se necesitan, pero de forma logarítmica. No confundir bits con estados.

---

## 2.9. Byte (página 13) — EXPANDIDA

> [!Note] Contenido literal de la página 13
> **0 1 0 0 0 1 1 1**
> **1 byte (B) = 8 bits (b)**
> **8 bits → 2⁸ = 256 combinaciones posibles**

> [!Note] Nota pedagógica de la página 13
> "Evitar confundir ocho bits con ocho combinaciones. Un byte contiene ocho bits y admite 256 patrones. No decir que un byte equivale siempre a un carácter."

> [!Definition] Byte
> Un **byte** (B) es un grupo de **8 bits** (b).
> $$1\ \text{B} = 8\ \text{b}$$
> Admite $2^8 = 256$ combinaciones.

**Desglose exhaustivo**:

**1. ¿Qué es un byte?**
Un byte es una **agrupación de 8 bits**. Es la unidad básica de información en la mayoría de los computadores. El byte es importante porque:
- Es la unidad mínima direccionable en memoria (cada posición de memoria tiene 1 byte).
- Es la unidad básica de almacenamiento (los archivos se miden en bytes).
- Es la unidad de codificación de caracteres en ASCII (aunque ASCII use 7 bits, se guarda en 1 byte).

**2. ¿Por qué 8 bits?**
Por razones históricas y prácticas:
- 8 bits permiten representar 256 valores, suficiente para todos los caracteres del inglés (mayúsculas, minúsculas, dígitos, signos de puntuación).
- 8 es una potencia de 2, lo que facilita las operaciones.
- Los primeros computadores comerciales (IBM System/360, 1964) adoptaron el byte de 8 bits, y se convirtió en estándar.

**3. ¿Cuántas combinaciones admite un byte?**
$$2^8 = 256\ \text{combinaciones}$$

Ejemplos de combinaciones: `00000000`, `00000001`, `00000010`, ..., `11111111`. Son 256 patrones distintos.

**4. ¿Qué se puede representar con un byte?**
- Un carácter ASCII (aunque ASCII use 7 bits, se guarda en 1 byte).
- Un número entero de 0 a 255 (sin signo) o de -128 a 127 (con signo).
- Un color en una paleta de 256 colores.
- Una instrucción máquina (en algunos procesadores).
- Parte de un número mayor (en procesadores de 32 o 64 bits).

**5. El patrón `01000111`**
El patrón `01000111` es un byte. Representa:
- En ASCII: el carácter 'G' (código 71 en decimal).
- En binario sin signo: 71.
- En binario con signo: 71 (positivo).

Su interpretación **depende del código y de la operación**.

> [!Warning] No confundir bits con combinaciones
> 8 bits **no** son 8 combinaciones. 8 bits → $2^8 = 256$ combinaciones. Es un error común decir "un byte tiene 8 combinaciones" cuando en realidad tiene 256.

> [!NonExample] Un byte no es siempre un carácter
> Depende del código usado:
> - ASCII: 7 bits por carácter (guardado en 1 byte).
> - UTF-8: longitud variable (1 a 4 bytes por carácter).
> - UTF-16: 2 o 4 bytes por carácter.
> - UTF-32: 4 bytes por carácter.
>
> Por eso **no** se puede decir que "un byte equivale siempre a un carácter".

> [!Important] Pregunta implícita
> ¿Por qué no se usa un byte de 7 bits si ASCII solo necesita 7? Porque 8 es potencia de 2 y facilita las operaciones. Además, el byte de 8 bits se convirtió en estándar de facto. Usar 7 bits desperdiciaría 1 bit por carácter, pero complicaría el direccionamiento.
>
> ¿Qué pasaría si usáramos 4 bits en lugar de 8? Solo tendríamos $2^4 = 16$ combinaciones, insuficientes para representar todos los caracteres del inglés.

**Intuición**: Un byte es como una caja de 8 compartimentos. Cada compartimento puede estar vacío (0) o lleno (1). Con 8 compartimentos, puedes formar 256 patrones distintos. Es como una cerradura de 8 ruedas, cada una con 2 posiciones.

> [!Summary] Resumen ejecutivo de 2.9
> Un byte son 8 bits. Admite $2^8 = 256$ combinaciones. Es la unidad básica de información y almacenamiento. No confundir bits con combinaciones. Un byte no es siempre un carácter (depende del código).

---

## 2.11. Prefijos decimales y binarios (página 15) — EXPANDIDA

> [!Note] Contenido literal de la página 15
> **Prefijos decimales del SI y prefijos binarios normalizados por la IEC.**
>
> | DECIMAL (SI) | FACTOR | BINARIO (IEC) | FACTOR |
> |---|---|---|---|
> | kilo (k) | 10³ | kibi (Ki) | 2¹⁰ |
> | mega (M) | 10⁶ | mebi (Mi) | 2²⁰ |
> | giga (G) | 10⁹ | gibi (Gi) | 2³⁰ |
> | tera (T) | 10¹² | tebi (Ti) | 2⁴⁰ |
> | peta (P) | 10¹⁵ | pebi (Pi) | 2⁵⁰ |
> | exa (E) | 10¹⁸ | exbi (Ei) | 2⁶⁰ |
>
> **b = bit** | **B = byte** | **1 B = 8 b** | **1 kb = 1 000 b** | **1 KiB = 1 024 B** | **1 MB = 10⁶ B**

> [!Note] Nota pedagógica de la página 15
> "Los prefijos decimales pertenecen al Sistema Internacional de Unidades (SI): kilo, mega y giga corresponden a potencias de diez. Los prefijos binarios normalizados por la Comisión Electrotécnica Internacional (IEC), como kibi, mebi y gibi, corresponden a potencias de dos. Debe distinguirse entre el prefijo y la unidad: b significa bit y B significa byte. Un byte contiene ocho bits. Por ejemplo, 1 MB = 10^6 bytes, mientras que 1 MiB = 2^20 bytes. Fuentes oficiales: BIPM, https://www.bipm.org/en/measurement-units/si-prefixes ; NIST, https://physics.nist.gov/cuu/Units/binary.html ."

> [!Definition] Prefijos decimales (SI) y binarios (IEC)
> Decimales: potencias de 10. Binarios: potencias de 2.

**Desglose exhaustivo**:

**1. ¿Por qué existen dos sistemas de prefijos?**
- **Sistema decimal (SI)**: es el sistema internacional estándar para todas las unidades científicas. Usa potencias de 10 porque es el sistema natural para los humanos (tenemos 10 dedos).
- **Sistema binario (IEC)**: es el sistema natural para los computadores, que trabajan en base 2. Usa potencias de 2 porque es como funcionan internamente.

**2. ¿Cuándo se usa cada uno?**
- **SI (decimal)**: se usa para **capacidad de almacenamiento** (discos duros, SSD, pendrives) y **tasas de transferencia** (Mb/s, MB/s). Los fabricantes usan potencias de 10 porque los números son más "bonitos" (500 GB = 500 × 10⁹ B).
- **IEC (binario)**: se usa para **memoria RAM** y **tamaño de archivos** en algunos sistemas operativos. Los sistemas operativos usan potencias de 2 porque es más natural para la memoria.

**3. La confusión clásica**
Un disco duro de "500 GB" (decimal) tiene 500 × 10⁹ = 500 000 000 000 bytes. Pero si lo mides en GiB (binario), tiene:
$$\frac{500 \times 10^9}{2^{30}} = \frac{500 \times 10^9}{1\,073\,741\,824} \approx 465{,}66\ \text{GiB}$$
Por eso un disco de "500 GB" aparece como "465 GB" en algunos sistemas operativos. **No es que falte espacio; es que se usan prefijos distintos.**

**4. Diferencia entre b y B**
- **b** = bit (minúscula).
- **B** = byte (mayúscula).
- $1\ \text{B} = 8\ \text{b}$.
- $1\ \text{kb} = 1\,000\ \text{bits}$.
- $1\ \text{kB} = 1\,000\ \text{bytes}$.
- $1\ \text{KiB} = 1\,024\ \text{bytes}$.

**5. Tabla completa con equivalencias**

| Prefijo | Símbolo | Factor | Equivalencia |
|---------|---------|--------|--------------|
| kilo | k | $10^3$ | 1 000 |
| mega | M | $10^6$ | 1 000 000 |
| giga | G | $10^9$ | 1 000 000 000 |
| tera | T | $10^{12}$ | 1 000 000 000 000 |
| peta | P | $10^{15}$ | 1 000 000 000 000 000 |
| exa | E | $10^{18}$ | 1 000 000 000 000 000 000 |
| kibi | Ki | $2^{10}$ | 1 024 |
| mebi | Mi | $2^{20}$ | 1 048 576 |
| gibi | Gi | $2^{30}$ | 1 073 741 824 |
| tebi | Ti | $2^{40}$ | 1 099 511 627 776 |
| pebi | Pi | $2^{50}$ | 1 125 899 906 842 624 |
| exbi | Ei | $2^{60}$ | 1 152 921 504 606 846 976 |

> [!Warning] No confundir prefijo con unidad
> - **b** = bit, **B** = byte.
> - $1\ \text{MB} = 10^6$ bytes (decimal).
> - $1\ \text{MiB} = 2^{20}$ bytes (binario).
> - $1\ \text{MB} \neq 1\ \text{MiB}$.

> [!Important] Pregunta implícita
> ¿Por qué existen dos sistemas? Porque los fabricantes de discos usan potencias de 10 (más "generosas" para el marketing) mientras que los sistemas operativos usan potencias de 2 (más naturales para la memoria). Por eso un disco de "500 GB" aparece como "465 GiB" en el sistema.
>
> ¿Qué pasaría si todos usaran el mismo sistema? No habría confusión, pero habría que elegir entre perder precisión (usar decimal para memoria) o usar números menos redondos (usar binario para discos).

**Intuición**: Un prefijo decimal es como contar de 10 en 10 (como los dedos); un prefijo binario es como contar de 2 en 2 (como los bits). Son dos formas de agrupar cantidades. Es como medir en metros (decimal) o en pies (binario): ambos miden longitud, pero con unidades distintas.

> [!Connection]
> Estos prefijos se usan constantemente en temas de memoria, almacenamiento y redes. Por ejemplo, la capacidad de un disco duro se suele expresar en GB decimales, mientras que la RAM se expresa en GiB binarios.

> [!Summary] Resumen ejecutivo de 2.11
> Los prefijos decimales (SI) usan potencias de 10; los binarios (IEC), potencias de 2. No confundir b (bit) con B (byte), ni MB (decimal) con MiB (binario). La confusión entre ambos sistemas explica por qué un disco de "500 GB" aparece como "465 GiB".

---

## 2.14. Tiempo de descarga de 1 GB a 100 Mb/s (página 18) — EXPANDIDA

> [!Note] Contenido literal de la página 18
> Quieres descargar un archivo de 1 GB mediante una conexión de 100 Mb/s. Suponiendo una tasa constante y sin sobrecarga, ¿cuánto tiempo tardará la descarga?
> **ARCHIVO 1 GB**
> **CONEXIÓN 100 Mb/s**
> Usamos unidades decimales: 1 GB = 1 000 MB.
> **15 / 19**

> [!Note] Nota pedagógica de la página 18
> "Este es el segundo subproblema del ejercicio de la conexión de 100 megas. La comparación entre Mb/s y MB/s ya se ha resuelto. Ahora se plantea una pregunta distinta: cuánto tarda en descargarse un archivo de 1 GB a una tasa constante de 100 Mb/s. Se emplean prefijos decimales y se ignoran esperas, variaciones de tasa y sobrecargas. No se proporciona aún la resolución, que comienza convirtiendo el tamaño del archivo a megabits."

> [!Example] Planteamiento
> Archivo: 1 GB. Conexión: 100 Mb/s. ¿Tiempo?

**Desglose exhaustivo del planteamiento**:

**1. ¿Qué nos dan?**
- Tamaño del archivo: 1 GB (gigabyte decimal).
- Tasa de conexión: 100 Mb/s (megabits por segundo).
- Suposiciones: tasa constante, sin sobrecarga.

**2. ¿Qué nos piden?**
- El tiempo que tarda en descargarse el archivo.

**3. ¿Qué unidades tenemos?**
- Archivo: GB (bytes).
- Conexión: Mb/s (bits por segundo).

**4. ¿Cuál es el problema?**
Las unidades **no coinciden**: el archivo está en bytes y la conexión en bits. Antes de dividir, hay que convertirlas a las mismas unidades.

**5. ¿Qué estrategia seguir?**
Convertir el tamaño del archivo a megabits (Mb) para que coincida con la tasa (Mb/s). Luego aplicar $t = D / R$.

**6. ¿Qué pasa si no convertimos?**
Si dividimos directamente 1 GB / 100 Mb/s, obtendríamos un número sin sentido porque las unidades no coinciden. Es como dividir metros entre segundos y esperar un tiempo: falta la conversión.

> [!Important] Pregunta implícita
> ¿Por qué no podemos dividir directamente? Porque 1 GB son bytes y 100 Mb/s son bits por segundo. Las unidades no son compatibles. Hay que convertir GB a Mb primero.
>
> ¿Qué pasaría si la conexión fuera de 100 MB/s en lugar de 100 Mb/s? Entonces el tiempo sería mucho menor: 1 GB / 100 MB/s = 10 s. Pero como es 100 Mb/s (bits), el tiempo es 80 s. La diferencia entre b y B es crucial.

**Intuición**: Es como si tuvieras un depósito de agua de 1 000 litros (GB) y una tubería que vierte 100 mililitros por segundo (Mb/s). No puedes dividir litros entre mililitros sin convertir primero. Una vez convertido, el tiempo es simplemente cuántas veces cabe la tasa en el total.

> [!Summary] Resumen ejecutivo de 2.14
> Para calcular el tiempo de descarga, hay que convertir el tamaño del archivo y la tasa a las mismas unidades (bits o bytes). El archivo está en GB (bytes) y la conexión en Mb/s (bits). Hay que convertir GB a Mb antes de dividir.

---

## 2.15. Conversión a megabits (página 19) — EXPANDIDA

> [!Note] Contenido literal de la página 19
> **1 GB = 1 000 MB**
> **1 000 MB × 8 = 8 000 Mb**
> Ya tenemos Mb en el archivo y Mb/s en la conexión.

> [!Note] Nota pedagógica de la página 19
> "1 GB decimal = 10^9 bytes = 8·10^9 bits = 8000 Mb. Pedir al alumnado que justifique cada conversión; no dividir directamente 1 entre 100."

> [!Example] Conversión
> $$1\ \text{GB} = 1\,000\ \text{MB} = 10^9\ \text{B} = 8 \times 10^9\ \text{b} = 8\,000\ \text{Mb}$$

**Desglose exhaustivo paso a paso**:

**Paso 1: Convertir GB a MB (decimal)**
$$1\ \text{GB} = 1\,000\ \text{MB}$$
**Justificación**: El prefijo G (giga) decimal significa $10^9$. El prefijo M (mega) decimal significa $10^6$. Por tanto:
$$1\ \text{GB} = 10^9\ \text{B} = 10^3 \times 10^6\ \text{B} = 1\,000\ \text{MB}$$

**Paso 2: Convertir MB a bytes**
$$1\,000\ \text{MB} = 1\,000 \times 10^6\ \text{B} = 10^9\ \text{B}$$
**Justificación**: 1 MB = $10^6$ bytes. Por tanto, 1 000 MB = $1\,000 \times 10^6 = 10^9$ bytes.

**Paso 3: Convertir bytes a bits**
$$10^9\ \text{B} \times 8 = 8 \times 10^9\ \text{b}$$
**Justificación**: $1\ \text{B} = 8\ \text{b}$. Por tanto, $10^9$ bytes son $8 \times 10^9$ bits.

**Paso 4: Convertir bits a megabits**
$$8 \times 10^9\ \text{b} = 8\,000 \times 10^6\ \text{b} = 8\,000\ \text{Mb}$$
**Justificación**: $1\ \text{Mb} = 10^6$ bits. Por tanto, $8 \times 10^9$ bits son $8\,000$ megabits.

**Resumen de la cadena de conversiones**:
$$1\ \text{GB} \xrightarrow{\times 1\,000} 1\,000\ \text{MB} \xrightarrow{\times 10^6} 10^9\ \text{B} \xrightarrow{\times 8} 8 \times 10^9\ \text{b} \xrightarrow{/ 10^6} 8\,000\ \text{Mb}$$

**Verificación**:
- $1\ \text{GB} = 10^9$ bytes.
- $10^9$ bytes × 8 = $8 \times 10^9$ bits.
- $8 \times 10^9$ bits / $10^6$ = 8 000 Mb. ✓

> [!Warning] No dividir directamente
> No dividir 1 entre 100. Hay que convertir primero el tamaño del archivo a megabits. Si divides 1 GB / 100 Mb/s sin convertir, obtienes 0,01, que no tiene sentido.

> [!Important] Pregunta implícita
> ¿Por qué no convertimos la tasa a MB/s en lugar de convertir el archivo a Mb? También se puede: 100 Mb/s = 12,5 MB/s. Entonces 1 GB = 1 000 MB. $t = 1\,000 / 12{,}5 = 80$ s. El resultado es el mismo. Ambas estrategias son válidas; solo hay que ser consistente.
>
> ¿Qué pasaría si usáramos prefijos binarios? Si 1 GB fuera 1 GiB = $2^{30}$ bytes = 1 073 741 824 bytes, entonces el tiempo sería ligeramente mayor. Pero el enunciado dice "unidades decimales: 1 GB = 1 000 MB", así que usamos decimal.

**Intuición**: Convertir unidades es como traducir un idioma a otro antes de hacer una operación. No puedes sumar peras y manzanas sin convertirlas a la misma fruta. Aquí convertimos bytes a bits para que coincidan con la tasa en bits/s.

> [!Summary] Resumen ejecutivo de 2.15
> La conversión de 1 GB a Mb se hace en 4 pasos: GB → MB (×1 000), MB → B (×$10^6$), B → b (×8), b → Mb (÷$10^6$). Resultado: 8 000 Mb. No dividir directamente 1 entre 100.

---

## 2.17. Triángulo D = R × t (página 20) — EXPANDIDA

> [!Note] Contenido literal de la página 20
> **Cantidad, tasa y tiempo**
> Como espacio = velocidad × tiempo, aquí: datos = tasa × tiempo.
> [Triángulo: D (datos) arriba; R (tasa) y t (tiempo) abajo]
> $$D = Rt$$
> $$R = \frac{D}{t}$$
> $$t = \frac{D}{R}$$
> $$t = 8\ 000\ \text{Mb}/(100\ \text{Mb/s}) = 80\ \text{s}$$

> [!Note] Nota pedagógica de la página 20
> "Triángulo para despejar D=R×t. No sustituye convertir unidades previamente. Tapar D:Rx t; tapar R:D/t; tapar t:D/R. D:cantidad de datos; R:tasa; t:tiempo.1GB=8000Mb,80s=1min20s a tasa constante de100Mb/s."

> [!Example] Resolución
> $$t = \frac{D}{R} = \frac{8\,000\ \text{Mb}}{100\ \text{Mb/s}} = 80\ \text{s} = 1\ \text{min}\ 20\ \text{s}$$

**Desglose exhaustivo del triángulo**:

**1. ¿Qué es el triángulo D = R × t?**
Es una **regla nemotécnica** para recordar las tres fórmulas relacionadas:
- $D = R \times t$ (datos = tasa × tiempo)
- $R = D / t$ (tasa = datos / tiempo)
- $t = D / R$ (tiempo = datos / tasa)

**2. ¿Cómo se usa?**
Dibuja un triángulo con D arriba y R y t abajo (R a la izquierda, t a la derecha):
```
        D
       ---
      R | t
```
- **Tapar D**: queda R × t → $D = R \times t$.
- **Tapar R**: queda D / t → $R = D / t$.
- **Tapar t**: queda D / R → $t = D / R$.

**3. ¿Por qué funciona?**
Porque la relación es **proporcional**: $D$ es directamente proporcional a $R$ y a $t$. Si aumentas la tasa, aumentan los datos (en el mismo tiempo). Si aumentas el tiempo, aumentan los datos (a la misma tasa). Es la misma relación que espacio = velocidad × tiempo.

**4. Aplicación al problema**:
- $D = 8\,000\ \text{Mb}$ (datos).
- $R = 100\ \text{Mb/s}$ (tasa).
- $t = ?$ (tiempo).
- Tapamos $t$: $t = D / R = 8\,000 / 100 = 80\ \text{s}$.

**5. Conversión a minutos y segundos**:
$$80\ \text{s} = 1\ \text{min}\ 20\ \text{s}$$

**6. Analogía con espacio = velocidad × tiempo**:
- Espacio = velocidad × tiempo.
- Datos = tasa × tiempo.
- Es la misma relación física: una cantidad que se acumula a un ritmo constante durante un tiempo.

> [!Warning] No sustituye convertir unidades previamente
> El triángulo te dice **qué operación** hacer, pero **no** convierte unidades. Primero hay que asegurarse de que $D$ y $R$ están en las mismas unidades (ambos en bits o ambos en bytes). Si $D$ está en Mb y $R$ en Mb/s, ya coinciden.

> [!Important] Pregunta implícita
> ¿Qué pasaría si la tasa no fuera constante? El triángulo solo funciona si $R$ es constante. Si la tasa varía, habría que integrar: $D = \int R(t) \, dt$. Pero en este ejercicio se supone tasa constante.
>
> ¿Por qué no puede ser de otra forma? Porque la relación $D = R \times t$ es una **definición**: la tasa es la cantidad de datos por unidad de tiempo. Si multiplicas la tasa por el tiempo, obtienes la cantidad total de datos.

**Intuición**: Es como llenar una piscina con una manguera. La cantidad de agua (D) es igual al caudal (R) multiplicado por el tiempo (t). Si el caudal es 100 litros/s y el tiempo es 80 s, la cantidad es 8 000 litros. Aquí, en lugar de agua, son megabits.

> [!Summary] Resumen ejecutivo de 2.17
> El triángulo D = R × t permite despejar cualquiera de las tres variables. Tapar la incógnita y hacer la operación indicada. No sustituye la conversión de unidades. Aplicado al problema: $t = 8\,000 / 100 = 80$ s = 1 min 20 s.

---

## 2.20. La CPU trabaja con grupos de bits (página 24) — EXPANDIDA

> [!Note] Contenido literal de la página 24
> **CPU**
> **Central Processing Unit**
> registro / palabra: **1001 1111**
> [Imagen de placa base con etiquetas]

> [!Note] Nota pedagógica de la página 24
> "La CPU o unidad central de procesamiento ejecuta las instrucciones de los programas. En el dibujo aparece un registro, un pequeño almacenamiento interno que mantiene temporalmente un grupo de bits. El patrón 1001 1111 ocupa ocho posiciones binarias. Por sí solo no indica si representa un número, un carácter u otra información: su interpretación depende del código y de la operación. En este modelo utilizaremos grupos de ocho bits para poder seguir visualmente los movimientos de datos. Un procesador real dispone de varios registros y de más elementos de los que muestra esta primera figura."

> [!Definition] CPU
> La **CPU** ejecuta las instrucciones. El **registro** mantiene temporalmente un grupo de bits.

**Desglose exhaustivo**:

**1. ¿Qué es la CPU?**
La **CPU** (Central Processing Unit) es el **cerebro del computador**. Su función es **ejecutar las instrucciones** de los programas. Sin CPU, el computador no puede procesar nada.

**2. ¿Qué es un registro?**
Un **registro** es un **pequeño almacenamiento interno** dentro de la CPU. Su función es **mantener temporalmente** un grupo de bits mientras se está ejecutando una operación. Los registros son **muy rápidos** (más que la memoria RAM) pero **muy pequeños** (típicamente 8, 16, 32 o 64 bits).

**3. ¿Por qué se necesitan registros?**
Porque la CPU necesita tener los datos **a mano** para operar con ellos. Si tuviera que ir a la memoria RAM cada vez que necesita un dato, sería mucho más lento. Los registros actúan como **memoria de trabajo inmediata**.

**4. El patrón `1001 1111`**
Este patrón ocupa **8 posiciones binarias** (8 bits). Cada posición es un bit: 1, 0, 0, 1, 1, 1, 1, 1.

**5. ¿Qué significa `1001 1111`?**
**Por sí solo, nada**. Su interpretación depende del **código** y de la **operación**:
- En ASCII: `1001 1111` no es un carácter imprimible estándar (es el código 159, que en ASCII extendido es 'Ÿ').
- En binario sin signo: 159.
- En binario con signo (complemento a dos): -97.
- Como instrucción máquina: depende del procesador.
- Como color RGB: podría ser un componente de color.

**6. ¿Por qué usamos 8 bits en este modelo?**
Porque 8 bits es **manejable visualmente**: caben en una fila y se pueden seguir los movimientos de datos sin perderse. Es una **simplificación didáctica**, no una afirmación sobre todos los computadores.

**7. ¿Qué hay en un procesador real?**
Un procesador real tiene:
- **Varios registros** (no uno solo).
- **Más elementos** (caché, unidades de ejecución, etc.).
- **Anchuras mayores** (32 o 64 bits, o incluso 128 bits en algunos casos).

> [!Important] Valor vs interpretación
> El patrón `1001 1111` no indica por sí solo qué representa. Su significado depende del **código** (ASCII, binario, coma flotante) y de la **operación** (suma, comparación, movimiento). Esta es una idea fundamental: **los bits son solo bits; el significado se lo da el contexto**.

> [!Important] Pregunta implícita
> ¿Por qué no se interpreta siempre de la misma forma? Porque el computador no sabe qué tipo de dato está manejando. El programador (o el compilador) es quien decide si un patrón de bits es un número, un carácter o una instrucción. El hardware solo ve bits.
>
> ¿Qué pasaría si el patrón tuviera 16 bits? Entonces habría $2^{16} = 65\,536$ combinaciones posibles. Más bits = más combinaciones = más información representable.

**Intuición**: Un registro es como una **bandeja de entrada** en un escritorio. La CPU es el oficinista. La bandeja mantiene temporalmente los documentos (bits) que el oficinista está usando en este momento. Cuando termina, los guarda en el archivador (memoria) o los pasa a otra bandeja (otro registro).

> [!NonExample] El registro no es memoria principal
> Un registro **no** es lo mismo que la memoria RAM. Los registros están **dentro** de la CPU y son **muy rápidos** pero **muy pequeños**. La RAM está **fuera** de la CPU y es **más lenta** pero **mucho más grande**.

> [!Summary] Resumen ejecutivo de 2.20
> La CPU ejecuta instrucciones. Los registros son pequeños almacenamientos internos que mantienen temporalmente grupos de bits. El patrón `1001 1111` ocupa 8 bits y su significado depende del código y la operación. En este modelo usamos 8 bits por simplicidad didáctica.

---

## 2.21. Ocho bits forman la palabra de nuestro modelo (página 25) — EXPANDIDA

> [!Note] Contenido literal de la página 25
> **2 / 18**
> **L1.2 · UNIDADES FUNCIONALES**
> **Ocho bits forman la palabra de nuestro modelo**
> **CPU**
> **Central Processing Unit**
> registro / palabra: **8 bits**
> [Imagen de placa base]

> [!Note] Nota pedagógica de la página 25
> "La figura sustituye el contenido concreto del registro por su anchura: 8 bits. Así distinguimos dos ideas: el valor almacenado puede cambiar, mientras que la capacidad del registro permanece fija. La palabra de máquina es un grupo de bits que el procesador maneja como unidad natural en determinadas operaciones; aquí adoptamos una palabra de ocho bits. Es una simplificación del ejemplo, no una afirmación sobre todos los computadores. En otros procesadores son habituales palabras y registros de 32 o 64 bits, y pueden coexistir registros de distintas anchuras."

> [!Definition] Palabra
> Grupo de bits que el procesador maneja como unidad natural. En este modelo: 8 bits.

**Desglose exhaustivo**:

**1. ¿Qué es la "palabra"?**
La **palabra** (word) es el **grupo de bits** que el procesador maneja como **unidad natural** en determinadas operaciones. Es como la "unidad de trabajo" del procesador.

**2. ¿Por qué se llama "palabra"?**
El término viene de los primeros computadores, donde la unidad de datos procesada simultáneamente se llamaba "word" (palabra). Es análogo a una "palabra" en lenguaje: la unidad mínima que tiene significado completo.

**3. Diferencia entre "valor" y "capacidad"**
- **Valor**: el contenido concreto del registro en un momento dado. Puede cambiar: `1001 1111`, `0000 0000`, `1111 1111`, etc.
- **Capacidad**: la anchura del registro. Es **fija**: 8 bits. No cambia.

**Ejemplo**:
- Valor: `1001 1111` (hoy), `0000 0000` (mañana).
- Capacidad: 8 bits (siempre).

**4. ¿Por qué se distingue?**
Porque el **valor** es lo que se procesa, pero la **capacidad** es lo que determina cuántas combinaciones se pueden representar. Un registro de 8 bits siempre tendrá 256 combinaciones posibles, independientemente del valor que tenga en un momento dado.

**5. La palabra en este modelo: 8 bits**
En este tema adoptamos una palabra de **8 bits** por simplicidad didáctica. Esto significa que el procesador maneja grupos de 8 bits como unidad natural.

**6. ¿Qué pasa en procesadores reales?**
En procesadores reales son habituales:
- Palabras de **32 bits** (4 bytes).
- Palabras de **64 bits** (8 bytes).
- Pueden coexistir registros de distintas anchuras (por ejemplo, registros de 8, 16, 32 y 64 bits en el mismo procesador).

**7. ¿Por qué no todos los procesadores tienen la misma anchura?**
Porque la anchura determina:
- **Cuánta información** se puede procesar de una vez.
- **Cuánta memoria** se puede direccionar.
- **La complejidad** del hardware.
Un procesador de 64 bits puede direccionar mucha más memoria que uno de 32 bits, pero es más complejo y consume más.

> [!Important] Valor vs capacidad
> El **valor** almacenado en un registro puede cambiar. La **capacidad** (anchura) del registro permanece fija. En este modelo, 8 bits.

> [!Important] Pregunta implícita
> ¿Por qué no se usa una palabra de 1 bit? Porque sería muy ineficiente: cada operación manejaría solo 1 bit, y se necesitarían muchas operaciones para hacer cálculos simples. Una palabra más ancha permite procesar más información de una vez.
>
> ¿Qué pasaría si la palabra fuera de 16 bits? Habría $2^{16} = 65\,536$ combinaciones por palabra. Más capacidad, pero también más hardware.

**Intuición**: La palabra es como el **tamaño de la cuchara** con la que comes. Una cuchara pequeña (8 bits) te obliga a dar muchas cucharadas para comer lo mismo que con una cuchara grande (64 bits). Pero una cuchara grande es más difícil de manejar (más hardware).

> [!NonExample] La palabra no es la memoria total
> La **palabra** es la unidad de procesamiento, no la capacidad total de memoria. Un computador con palabras de 8 bits puede tener gigabytes de memoria. La palabra es **cuánto se procesa de una vez**, no **cuánto se almacena**.

> [!Summary] Resumen ejecutivo de 2.21
> La palabra es el grupo de bits que el procesador maneja como unidad natural. En este modelo: 8 bits. Se distingue entre valor (cambia) y capacidad (fija). En procesadores reales son comunes 32 o 64 bits.

---

## 2.22. La memoria guarda datos e instrucciones (página 26) — EXPANDIDA

> [!Note] Contenido literal de la página 26
> **L1.2 · UNIDADES FUNCIONALES**
> **La memoria guarda datos e instrucciones**
> **CPU** | **Memoria**
> registro / palabra: 8 bits | RAM / ROM / Cache
> [Esquema con filas de 8 bits]
> **Aquí cargaremos datos e instrucciones**
> **3 / 18**

> [!Note] Nota pedagógica de la página 26
> "Incorporamos la memoria, donde se almacenan los datos y las instrucciones que necesita el programa. Cada fila del dibujo representa una posición de ocho bits en este modelo. Para acceder a una posición hay que identificarla mediante una dirección. La figura reúne las etiquetas RAM, ROM y caché para recordar distintos tipos de memoria, pero no son intercambiables: la RAM suele almacenar el programa y los datos en uso; la ROM o memoria no volátil puede contener firmware; la caché conserva copias de información para reducir tiempos de acceso. La secuencia posterior utiliza una memoria abstracta de lectura y escritura."

> [!Definition] Memoria
> Guarda datos e instrucciones. Cada posición se identifica por una dirección.

**Desglose exhaustivo**:

**1. ¿Qué guarda la memoria?**
La memoria guarda **dos cosas**:
- **Datos**: los valores con los que trabaja el programa (números, texto, etc.).
- **Instrucciones**: las órdenes que el programa debe ejecutar.

**2. ¿Por qué guarda instrucciones?**
Porque el programa **es** una secuencia de instrucciones. El procesador necesita leerlas para saber qué hacer. Sin instrucciones en memoria, el procesador no tendría nada que ejecutar.

**3. ¿Cómo se accede a la memoria?**
Cada posición de memoria tiene una **dirección**. Para acceder a un dato o instrucción, el procesador proporciona la dirección y la memoria devuelve el contenido.

**4. Tipos de memoria**:

| Tipo | Característica | Uso típico |
|------|----------------|------------|
| **RAM** | Volátil (se pierde al apagar). Rápida. | Programa y datos en uso. |
| **ROM** | No volátil (se conserva al apagar). | Firmware, BIOS. |
| **Caché** | Volátil. Muy rápida. Pequeña. | Copias de datos de uso frecuente. |

**5. ¿Por qué no son intercambiables?**
Porque tienen **funciones distintas**:
- **RAM**: almacena lo que se está usando ahora. Si se apaga, se pierde.
- **ROM**: almacena lo que debe persistir (instrucciones de arranque). No se pierde.
- **Caché**: almacena copias temporales para acelerar el acceso. No es la fuente principal.

**6. En este modelo: memoria abstracta**
La secuencia posterior utiliza una **memoria abstracta de lectura y escritura**. No nos importa si es RAM, ROM o caché; solo nos importa que podemos leer y escribir en ella.

**7. Cada fila es una posición de 8 bits**
En el esquema, cada fila representa una **posición de memoria** que contiene 8 bits. Esto es coherente con la palabra de 8 bits del modelo.

> [!Important] Pregunta implícita
> ¿Por qué la memoria guarda tanto datos como instrucciones? Porque el programa y los datos están mezclados en la misma memoria. El procesador no distingue entre ellos a nivel de hardware; es el programador quien decide qué es cada cosa.
>
> ¿Qué pasaría si la memoria solo guardara datos? El procesador no tendría instrucciones que ejecutar. El programa no podría funcionar.

**Intuición**: La memoria es como una **biblioteca**. Cada libro (dato o instrucción) tiene una **signatura** (dirección). Para encontrar un libro, buscas por su signatura. La biblioteca puede tener libros de consulta (RAM) y libros de archivo (ROM).

> [!NonExample] Memoria no es almacenamiento
> La **memoria** (RAM) es volátil y rápida. El **almacenamiento** (disco) es persistente y lento. No confundir.

> [!Summary] Resumen ejecutivo de 2.22
> La memoria guarda datos e instrucciones. Cada posición tiene una dirección. Los tipos principales son RAM (volátil), ROM (no volátil) y caché (rápida). En este modelo usamos una memoria abstracta de lectura/escritura.

---

## 2.24. Microcontrolador (MCU) (página 28) — EXPANDIDA

> [!Note] Contenido literal de la página 28
> **5 / 18**

> [!Note] Nota pedagógica de la página 28
> "La figura muestra un microcontrolador, MCU: un circuito integrado que reúne un núcleo de procesamiento, memoria y, habitualmente, periféricos de entrada/salida y temporizadores. La idea central es la integración de funciones en un mismo chip. Resulta apropiado para controlar dispositivos y sistemas empotrados. El esquema conserva los elementos ya conocidos, pero los encierra en una unidad mayor. No debe interpretarse como que cualquier CPU acompañada de memoria constituye por sí sola un microcontrolador, ni como que todos los microcontroladores tengan caché. Los periféricos habituales no se dibujan en esta vista simplificada."

> [!Definition] Microcontrolador (MCU)
> Circuito integrado que reúne **núcleo de procesamiento**, **memoria** y, habitualmente, **periféricos de E/S** y **temporizadores**.

**Desglose exhaustivo**:

**1. ¿Qué es un microcontrolador?**
Un **microcontrolador** (MCU, Microcontroller Unit) es un **circuito integrado** que reúne en un solo chip:
- Un **núcleo de procesamiento** (CPU).
- **Memoria** (RAM y ROM/flash).
- **Periféricos de entrada/salida** (puertos serie, paralelo, ADC, DAC, etc.).
- **Temporizadores** (para generar retardos, PWM, etc.).

**2. ¿Qué significa "circuito integrado"?**
Un **circuito integrado** (chip) es un conjunto de componentes electrónicos fabricados sobre un sustrato de silicio. Todo el microcontrolador está en **un solo chip**, no en varios.

**3. ¿Qué es un "sistema empotrado"?**
Un **sistema empotrado** (embedded system) es un sistema computacional que forma parte de un dispositivo mayor y está dedicado a una función específica. Ejemplos: el controlador de un motor, el sistema de un microondas, el ABS de un coche.

**4. ¿Por qué es apropiado para sistemas empotrados?**
Porque:
- **Integra todo en un chip**: menor tamaño, menor coste.
- **Bajo consumo**: ideal para dispositivos alimentados por batería.
- **Fiabilidad**: menos conexiones externas, menos fallos.
- **Coste reducido**: producción en masa.

**5. ¿Qué diferencia hay con una CPU de PC?**
Una CPU de PC es un **procesador de altas prestaciones** que necesita chips externos para memoria y periféricos. Un MCU lo tiene todo integrado.

**6. ¿Todos los MCU tienen caché?**
**No**. Algunos MCU muy simples no tienen caché. La caché es un elemento que se añade en MCU más avanzados.

**7. ¿Los periféricos se dibujan?**
**No** en la vista simplificada del PDF. Los periféricos habituales (temporizadores, puertos serie, ADC, etc.) no se dibujan, pero están ahí.

> [!Warning] No confundir MCU con CPU + memoria
> No debe interpretarse como que **cualquier CPU acompañada de memoria** constituye por sí sola un microcontrolador. Un MCU integra **todo** en un solo chip, incluyendo periféricos.
>
> Tampoco todos los microcontroladores tienen caché. Los periféricos habituales no se dibujan en la vista simplificada del PDF.

> [!Important] Pregunta implícita
> ¿Qué ventaja tiene integrar todo en un chip? Menor tamaño, menor consumo, menor coste y mayor fiabilidad (menos conexiones externas). Por eso los microcontroladores dominan en sistemas empotrados.
>
> ¿Qué pasaría si no estuvieran integrados? Habría que conectar CPU, memoria y periféricos con cables externos, lo que aumentaría el tamaño, el coste y la probabilidad de fallos.

**Intuición**: Un microcontrolador es como una **navaja suiza**: tiene todas las herramientas en un solo objeto. Una CPU de PC es como un **taller**: cada herramienta está en su sitio, pero necesitas ir a buscarla.

> [!NonExample] Qué no es un microcontrolador
> - Una CPU de PC **no** es un microcontrolador: es un procesador de altas prestaciones que necesita chips externos para memoria y periféricos.
> - Un Arduino **sí** es una placa con un microcontrolador, pero la placa en sí no es el microcontrolador.
> - Una FPGA **no** es un microcontrolador: es un dispositivo reprogramable a nivel de hardware.

> [!Summary] Resumen ejecutivo de 2.24
> Un microcontrolador es un circuito integrado que reúne CPU, memoria y periféricos en un solo chip. Se usa en sistemas empotrados. No confundir con CPU + memoria externa. No todos tienen caché.

---

## 2.26-2.30. Secuencia completa de una operación (páginas 30-34) — EXPANDIDA

### 2.26. Paso 1: Seleccionar el dato en memoria (página 30) — EXPANDIDA

> [!Note] Contenido literal de la página 30
> **L1.2 · UNIDADES FUNCIONALES**
> **1 · Seleccionar el dato en memoria**
> **CPU** | **Memoria**
> **ALU** | **CU** | RAM / ROM / Cache
> registro / palabra: 8 bits | `1110 0110`
> [Flecha 1 de CU a Memoria]

> [!Note] Nota pedagógica de la página 30
> "La unidad de control inicia la lectura seleccionando la posición de memoria que contiene 1110 0110. La flecha 1 representa la solicitud de acceso a esa posición. Conceptualmente, la dirección indica dónde está el dato y la señal de lectura indica qué se quiere hacer. El contenido todavía permanece en memoria: pedir una lectura no equivale a haber recibido el valor. En las diapositivas posteriores distinguiremos el papel del bus de direcciones y del bus de datos, que aquí se representan de forma simplificada."

> [!Example] Paso 1
> La CU selecciona la posición que contiene `1110 0110`. Pedir lectura ≠ recibir valor.

**Desglose exhaustivo del paso 1**:

**1. ¿Quién inicia la operación?**
La **unidad de control (CU)**. Es la que decide que hay que leer un dato de memoria.

**2. ¿Qué hace exactamente?**
Selecciona la **posición de memoria** que contiene el dato `1110 0110`. Para ello, proporciona la **dirección** de esa posición.

**3. ¿Qué representa la flecha 1?**
La flecha 1 representa la **solicitud de acceso** a esa posición. Es la orden de lectura.

**4. ¿Qué significa "dirección" y "señal de lectura"?**
- **Dirección**: indica **dónde** está el dato. Es como el número de portal.
- **Señal de lectura**: indica **qué se quiere hacer**. Es como decir "quiero leer".

**5. ¿El dato ya está en la CPU?**
**No**. El contenido todavía permanece en memoria. Pedir una lectura **no** equivale a haber recibido el valor. Es como pedir un libro en la biblioteca: has hecho la solicitud, pero aún no lo tienes.

**6. ¿Qué falta?**
Falta que la memoria devuelva el dato. Eso ocurre en el paso 2.

> [!Important] Pregunta implícita
> ¿Por qué no se recibe el dato inmediatamente? Porque la memoria tiene un **tiempo de acceso**. No es instantánea. Primero se envía la dirección, luego la memoria busca, y finalmente devuelve el dato.

**Intuición**: Es como pedir un libro en una biblioteca. Primero vas al mostrador y pides el libro por su signatura (dirección). El bibliotecario anota la solicitud. El libro aún no lo tienes; tienes que esperar a que te lo traigan.

---

### 2.27. Paso 2: Llevar el dato a un registro (página 31) — EXPANDIDA

> [!Note] Contenido literal de la página 31
> **2 · Llevar el dato a un registro**
> **CPU** | **Memoria**
> **ALU** | **CU** | RAM / ROM / Cache
> registro / palabra: `1110 0110`
> [Flecha 1 de CU a Memoria; Flecha 2 de Memoria a Registro]

> [!Note] Nota pedagógica de la página 31
> "La memoria devuelve el contenido de la posición seleccionada. La flecha 2 muestra el traslado de 1110 0110 hacia un registro del procesador. El registro actúa como almacenamiento temporal para que el dato pueda participar en la operación. Una lectura normal copia el contenido: no borra ni vacía la posición de memoria de origen. Al terminar este paso, el mismo patrón puede estar presente en memoria y en el registro. La anchura de ocho bits del ejemplo permite ver el dato completo sin ocultar el significado de cada transferencia."

> [!Example] Paso 2
> La memoria devuelve `1110 0110` al registro. **La lectura copia; no borra.**

**Desglose exhaustivo del paso 2**:

**1. ¿Qué hace la memoria?**
La memoria **devuelve** el contenido de la posición seleccionada. Es decir, envía el dato `1110 0110` de vuelta a la CPU.

**2. ¿A dónde va el dato?**
A un **registro** del procesador. La flecha 2 muestra el traslado de `1110 0110` desde la memoria hasta el registro.

**3. ¿Para qué sirve el registro?**
El registro actúa como **almacenamiento temporal** para que el dato pueda participar en la operación. Es como una bandeja donde se pone el dato mientras se procesa.

**4. ¿La lectura borra el dato original?**
**No**. Una lectura normal **copia** el contenido: no borra ni vacía la posición de memoria de origen. Al terminar este paso, el mismo patrón puede estar presente en **memoria y en el registro**.

**5. ¿Por qué es importante que no borre?**
Porque el dato original puede ser necesario más adelante. Si la lectura borrara, perderíamos la información. La memoria es **no destructiva** en lectura.

**6. ¿Qué pasaría si la lectura borrara?**
Tendríamos que volver a escribir el dato original si lo necesitáramos. Sería ineficiente y propenso a errores.

> [!Important] Pregunta implícita
> ¿Por qué no se procesa directamente desde memoria? Porque la memoria es más lenta que los registros. Copiar el dato a un registro permite que la ALU lo procese rápidamente.

**Intuición**: Es como fotocopiar un documento. El original permanece en el archivador (memoria) y la copia va a tu mesa (registro). Puedes trabajar con la copia sin destruir el original.

> [!NonExample] Lectura no es borrado
> El dato original permanece en memoria. La lectura solo copia.

---

### 2.28. Paso 3: Enviar el operando a la ALU (página 32) — EXPANDIDA

> [!Note] Contenido literal de la página 32
> **3 · Enviar el operando a la ALU**
> **CPU** | **Memoria**
> **ALU** | **CU** | RAM / ROM / Cache
> registro / palabra: `1110 0110`
> [Flecha 1, 2, 3]

> [!Note] Nota pedagógica de la página 32
> "El contenido del registro se proporciona a la ALU mediante el recorrido marcado con 3. Ese contenido es el operando sobre el que se actuará. La unidad de control determina la operación que debe realizarse; la ALU no decide por sí misma qué instrucción ejecutar. En este ejemplo basta un operando porque se invertirá cada bit. Otras operaciones, como la suma, necesitan dos operandos. El dibujo muestra un único registro para mantener la secuencia sencilla, aunque un procesador real dispone de más registros y caminos internos."

> [!Example] Paso 3
> El registro envía `1110 0110` a la ALU. La CU decide la operación.

**Desglose exhaustivo del paso 3**:

**1. ¿Qué se envía a la ALU?**
El **contenido del registro**, es decir, `1110 0110`. Este es el **operando** sobre el que se actuará.

**2. ¿Qué es un "operando"?**
Un **operando** es el dato sobre el que se realiza una operación. En este caso, el operando es `1110 0110`.

**3. ¿Quién decide la operación?**
La **unidad de control (CU)**. La ALU **no** decide por sí misma qué instrucción ejecutar. La CU le dice a la ALU qué operación debe realizar (en este caso, invertir los bits).

**4. ¿Cuántos operandos se necesitan?**
En este ejemplo, **basta un operando** porque se invertirá cada bit. Otras operaciones, como la suma, necesitan **dos operandos**.

**5. ¿Por qué hay un solo registro en el dibujo?**
Para **mantener la secuencia sencilla**. Un procesador real dispone de **más registros** y **caminos internos** más complejos.

> [!Important] Pregunta implícita
> ¿Por qué la ALU no decide? Porque la ALU es solo un **ejecutor**. No tiene acceso a la instrucción completa ni al contexto del programa. La CU es la que interpreta la instrucción y coordina todo.

**Intuición**: La ALU es como una **calculadora**. Tú (la CU) decides qué operación hacer y le das los números (operandos). La calculadora solo ejecuta.

---

### 2.29. Paso 4: Operar y conservar el resultado (página 33) — EXPANDIDA

> [!Note] Contenido literal de la página 33
> **4 · Operar y conservar el resultado**
> **CPU** | **Memoria**
> **ALU** | **CU** | RAM / ROM / Cache
> registro / palabra: `0001 1001`
> [Flecha 1, 2, 3, 4]

> [!Note] Nota pedagógica de la página 33
> "La ALU aplica una negación bit a bit: cada 1 pasa a 0 y cada 0 pasa a 1. Por eso 1110 0110 se convierte en 0001 1001. El resultado queda en el registro mostrado. Los recorridos marcados con 4 relacionan el cálculo, el almacenamiento temporal del resultado y la coordinación con la unidad de control. No representan necesariamente operaciones simultáneas ni un número concreto de ciclos de reloj. Invertir todos los bits tampoco equivale, en general, a obtener el negativo aritmético de un número: aquí estamos describiendo una operación lógica."

> [!Example] Paso 4
> ALU: `1110 0110` → `0001 1001`. Resultado en registro.

**Desglose exhaustivo del paso 4**:

**1. ¿Qué operación realiza la ALU?**
Una **negación bit a bit**: cada 1 pasa a 0 y cada 0 pasa a 1.

**2. Aplicación paso a paso**:
```
Entrada:  1110 0110
Invertir: 0001 1001
```
- Bit 7: 1 → 0
- Bit 6: 1 → 0
- Bit 5: 1 → 0
- Bit 4: 0 → 1
- Bit 3: 0 → 1
- Bit 2: 1 → 0
- Bit 1: 1 → 0
- Bit 0: 0 → 1

**3. ¿Dónde queda el resultado?**
En el **registro** mostrado. El registro ahora contiene `0001 1001`.

**4. ¿Qué representan los recorridos marcados con 4?**
Relacionan:
- El **cálculo** (la operación de la ALU).
- El **almacenamiento temporal** del resultado (el registro).
- La **coordinación** con la unidad de control.

**5. ¿Son operaciones simultáneas?**
**No necesariamente**. No representan necesariamente operaciones simultáneas ni un número concreto de ciclos de reloj.

**6. ¿Invertir bits es lo mismo que cambiar el signo?**
**No**. Invertir todos los bits **no** equivale, en general, a obtener el negativo aritmético de un número. Aquí estamos describiendo una **operación lógica**, no aritmética.

> [!NonExample] Negación lógica ≠ negativo aritmético
> Invertir bits no es cambiar el signo. Para obtener el negativo aritmético se usa el complemento a dos (invertir bits y sumar 1), no solo invertir.

**Intuición**: Es como el juego del "negativo" en fotografía: cada color se invierte. El blanco se vuelve negro, el negro se vuelve blanco. Pero eso no significa que la foto sea "el negativo aritmético" de la original; es solo una inversión.

---

### 2.30. Pasos 5-6: Guardar el resultado en memoria (página 34) — EXPANDIDA

> [!Note] Contenido literal de la página 34
> **5-6 · Guardar el resultado en memoria**
> **CPU** | **Memoria**
> **ALU** | **CU** | RAM / ROM / Cache
> registro / palabra: `0001 1001` | `1110 0110` | `0001 1001`
> [Flechas 1, 2, 3, 4, 5, 6]

> [!Note] Nota pedagógica de la página 34
> "La unidad de control selecciona la posición de destino e inicia la escritura, representada por el paso 5. El paso 6 lleva el resultado 0001 1001 desde el registro a esa posición de memoria. Así se completa el recorrido leer–procesar–guardar. En la figura se usa una posición de destino distinta de la de origen, cuyo valor 1110 0110 se mantiene. La escritura sustituye el contenido anterior de la posición de destino. Como en la lectura, es útil separar la dirección y las señales que coordinan el acceso del dato que se transfiere."

> [!Example] Pasos 5-6
> La CU selecciona destino; el resultado `0001 1001` se escribe. Se completa leer–procesar–guardar.

**Desglose exhaustivo de los pasos 5-6**:

**Paso 5: Seleccionar la posición de destino**
- La **unidad de control** selecciona la posición de destino.
- **Inicia la escritura**, representada por el paso 5.
- La dirección de destino es **distinta** de la de origen.

**Paso 6: Escribir el resultado en memoria**
- El resultado `0001 1001` se lleva desde el **registro** a la **posición de destino** en memoria.
- **La escritura sustituye el contenido anterior** de la posición de destino.

**Resultado final**:
- La posición de origen conserva `1110 0110`.
- La posición de destino ahora contiene `0001 1001`.

**Se completa el recorrido leer–procesar–guardar**:
1. Leer: se leyó `1110 0110` de la posición de origen.
2. Procesar: se invirtieron los bits → `0001 1001`.
3. Guardar: se escribió `0001 1001` en la posición de destino.

> [!Warning] La escritura sustituye el contenido anterior
> La posición de destino tenía un valor anterior que se pierde. La posición de origen conserva `1110 0110`.

> [!Important] Pregunta implícita
> ¿Qué pasaría si se escribiera en la misma posición de origen? Entonces el valor original `1110 0110` se perdería y sería reemplazado por `0001 1001`. En la figura se usa una posición distinta para preservar el original.

**Intuición**: Es como escribir un documento nuevo basado en otro. El original queda intacto (si guardas en otro archivo) o se sobrescribe (si guardas en el mismo). La escritura en memoria es **destructiva** para la posición de destino.

---

## 2.31. Dos buses, dos funciones (página 35) — EXPANDIDA

> [!Note] Contenido literal de la página 35
> **L1.2 · UNIDADES FUNCIONALES**
> **Dos buses, dos funciones**
> **CPU** | **Memoria**
> **Bus de direcciones** → RAM / ROM / Cache
> **Bus de datos** ←
> registro / palabra: 8 bits
> [Imagen de placa base y cable]
> **12 / 18**

> [!Note] Nota pedagógica de la página 35
> "El bus de direcciones identifica la posición de memoria a la que se desea acceder; el bus de datos transporta el contenido leído o escrito. La pregunta que responde el primero es «¿dónde?», mientras que el segundo responde «¿qué valor?». En el modelo CPU–memoria, el procesador proporciona la dirección. Los datos pueden ir de memoria a CPU en una lectura o de CPU a memoria en una escritura. Las señales de control, como lectura y escritura, también son necesarias aunque no se desarrollan en esta figura. Las flechas de direcciones ilustran la selección de posiciones, no un cable independiente para cada fila."

> [!Definition] Buses
> - **Direcciones**: ¿dónde?
> - **Datos**: ¿qué valor?

**Desglose exhaustivo**:

**1. ¿Qué es un bus?**
Un **bus** es un **conjunto de líneas** que transportan información entre componentes. Es como una autopista de datos.

**2. ¿Cuántos buses hay?**
Dos principales:
- **Bus de direcciones**: identifica la posición de memoria.
- **Bus de datos**: transporta el contenido leído o escrito.

**3. ¿Qué pregunta responde cada uno?**
- **Direcciones**: «¿dónde?». Indica la posición.
- **Datos**: «¿qué valor?». Lleva el contenido.

**4. ¿Quién proporciona la dirección?**
En el modelo CPU–memoria, el **procesador** proporciona la dirección.

**5. ¿En qué dirección van los datos?**
- **Lectura**: de memoria a CPU.
- **Escritura**: de CPU a memoria.

**6. ¿Se necesitan señales de control?**
**Sí**. Las señales de control (lectura/escritura) también son necesarias, aunque no se desarrollan en esta figura.

**7. ¿Las flechas de direcciones son cables independientes?**
**No**. Las flechas de direcciones ilustran la **selección de posiciones**, no un cable independiente para cada fila. En la realidad, un bus de direcciones de $n$ líneas puede seleccionar $2^n$ posiciones.

> [!Important] Pregunta implícita
> ¿Por qué se necesitan dos buses separados? Porque una cosa es *dónde* está el dato (dirección) y otra *qué* dato es (contenido). Si usaran el mismo bus, no se podría saber si la señal es una dirección o un dato. Separarlos simplifica el diseño y evita ambigüedades.

**Intuición**: El bus de direcciones es como el **número de portal** en una calle; el bus de datos es como el **contenido del paquete** que se entrega. Primero necesitas saber a qué portal ir; luego, qué llevar.

> [!NonExample] El bus de datos no es el bus de direcciones
> No se debe confundir: el bus de direcciones **dice dónde**, el bus de datos **lleva qué**. Son físicamente distintos y cumplen funciones distintas.

> [!Summary] Resumen ejecutivo de 2.31
> El bus de direcciones indica dónde (¿qué posición?); el bus de datos lleva qué (¿qué valor?). El procesador proporciona la dirección. Los datos van de memoria a CPU (lectura) o de CPU a memoria (escritura). Las señales de control coordinan el acceso.

---

## 2.33. Dentro de la CPU: guardar, calcular y coordinar (páginas 38-39) — EXPANDIDA

> [!Note] Contenido literal de la página 38
> **L1.2 · UNIDADES FUNCIONALES**
> **Dentro de la CPU: guardar, calcular y coordinar**
> Registros, ALU y control colaboran siguiendo el ritmo del reloj.
> **REGISTROS** (Guardan valores temporales) ↔ **ALU** (Realiza operaciones aritméticas y lógicas) ← **CONTROL** (Interpreta y coordina)
> **RELOJ** [señal cuadrada]
> Un ciclo no equivale siempre a una instrucción.
> **15 / 18**

> [!Note] Nota pedagógica de la página 38
> "Los registros almacenan operandos, resultados y otros valores internos durante la ejecución. La ALU efectúa operaciones aritméticas y lógicas: por ejemplo, sumar dos operandos o invertir los bits de uno. La unidad de control interpreta las instrucciones y coordina las transferencias y operaciones; su acción alcanza a toda la CPU, aunque aquí solo se muestra una conexión representativa para no recargar la figura. El reloj proporciona una referencia temporal para coordinar cambios de estado. Su periodo T es el tiempo de un ciclo y su frecuencia es f=1/T. Una instrucción puede necesitar varios ciclos; también puede haber varias instrucciones solapadas. Por eso frecuencia de reloj e instrucciones por segundo no son la misma magnitud."

> [!Definition] Reloj
> Periodo $T$ = tiempo de un ciclo. Frecuencia $f = 1/T$.

**Desglose exhaustivo**:

**1. ¿Qué hace cada elemento?**

| Elemento | Función | Detalle |
|----------|---------|---------|
| **Registros** | Guardan valores temporales | Operandos, resultados, valores internos. |
| **ALU** | Realiza operaciones | Aritméticas (sumar) y lógicas (invertir). |
| **Control** | Interpreta y coordina | Decide qué se hace y cuándo. |
| **Reloj** | Marca el ritmo | Referencia temporal. |

**2. ¿Cómo colaboran?**
- Los **registros** guardan los datos.
- La **ALU** opera con ellos.
- La **unidad de control** coordina todo.
- El **reloj** marca el ritmo de los cambios.

**3. ¿Qué es el periodo y la frecuencia?**
- **Periodo ($T$)**: tiempo que dura un ciclo.
- **Frecuencia ($f$)**: número de ciclos por segundo. $f = 1/T$.

**4. ¿Un ciclo equivale a una instrucción?**
**No**. Una instrucción puede necesitar **varios ciclos**. También puede haber **varias instrucciones solapadas**.

**5. ¿Por qué frecuencia e instrucciones por segundo no son lo mismo?**
Porque una instrucción puede necesitar varios ciclos. Si una instrucción necesita 2 ciclos, la frecuencia de instrucciones es la mitad de la frecuencia de reloj.

> [!Warning] Un ciclo no equivale siempre a una instrucción
> Una instrucción puede necesitar varios ciclos. Por eso **frecuencia de reloj** e **instrucciones por segundo** no son la misma magnitud.

> [!Important] Pregunta implícita
> ¿Qué pasaría si un ciclo equivaliera siempre a una instrucción? Entonces frecuencia de reloj y frecuencia de instrucciones serían lo mismo. Pero en la realidad no es así.

**Intuición**: El reloj es como el **metrónomo** de un músico. Marca el ritmo, pero una pieza musical (instrucción) puede necesitar varios compases (ciclos).

---

## 2.34. Frecuencia de reloj y tiempo de ejecución (página 40) — EXPANDIDA

> [!Note] Contenido literal de la página 40
> **L1.2 · UNIDADES FUNCIONALES**
> **Frecuencia de reloj y tiempo de ejecución**
> Más GHz no garantizan menos tiempo para cualquier programa.
> **FRECUENCIA f** | **CPI MEDIO**
> Ciclos por segundo | Ciclos por instrucción
> 2 GHz = 2 × 10⁹ ciclos/s | Valor medio del programa
> **Tiempo de CPU = NI × CPI / f**
> NI: instrucciones ejecutadas. Para la misma tarea, menos tiempo es mejor.
> **17 / 18**

> [!Note] Nota pedagógica de la página 40
> "La frecuencia f cuenta ciclos por segundo: 1 Hz es un ciclo por segundo y 1 GHz son mil millones de ciclos por segundo. El CPI medio es el número de ciclos consumidos por instrucción, promediado sobre las instrucciones ejecutadas por un programa. Si NI es ese número de instrucciones, el total de ciclos es NI×CPI y el tiempo de CPU resulta NI×CPI/f. Por ejemplo, con NI=2×10^9, CPI=2 y f=2×10^9 ciclos/s, el tiempo es 2 segundos. El programa, el compilador, la arquitectura, los accesos a memoria y las dependencias pueden cambiar NI o CPI. En procesadores que solapan varias instrucciones, el CPI medio puede ser inferior a uno. El tiempo de CPU no incluye necesariamente toda la espera de disco, red o interacción humana."

> [!Theorem] Tiempo de CPU
> $$t = \frac{N_I \times \text{CPI}}{f}$$

**Desglose exhaustivo**:

**1. ¿Qué es la frecuencia ($f$)?**
Número de ciclos por segundo. Se mide en Hz.
- $1\ \text{Hz} = 1$ ciclo/s.
- $1\ \text{GHz} = 10^9$ ciclos/s.

**2. ¿Qué es el CPI?**
**Ciclos Por Instrucción**. Número medio de ciclos que consume cada instrucción. Es un **promedio** sobre las instrucciones ejecutadas por un programa.

**3. Deducción de la fórmula**:
- El número total de ciclos es: $N_c = N_I \times \text{CPI}$.
- La frecuencia es ciclos por segundo: $f = N_c / t$.
- Despejando $t$: $t = N_c / f = (N_I \times \text{CPI}) / f$.

**4. Desglose de variables**:
- $N_I$: instrucciones **ejecutadas** (no las que contiene el programa, sino las que realmente se ejecutan, incluyendo repeticiones de bucles).
- $\text{CPI}$: promedio. Puede ser distinto para cada instrucción; se usa el valor medio.
- $f$: frecuencia del reloj.

**5. Ejemplo del material**:
$$N_I = 2 \times 10^9,\ \text{CPI} = 2,\ f = 2 \times 10^9 \Rightarrow t = \frac{2 \times 10^9 \times 2}{2 \times 10^9} = 2\ \text{s}$$

**6. ¿Qué factores pueden cambiar $N_I$ o CPI?**
- El **programa** (algoritmo).
- El **compilador** (optimizaciones).
- La **arquitectura** (repertorio de instrucciones).
- Los **accesos a memoria** (caché).
- Las **dependencias** entre instrucciones.

**7. ¿El CPI puede ser inferior a 1?**
**Sí**, en procesadores que solapan varias instrucciones (superescalares). El CPI medio puede ser inferior a uno.

**8. ¿El tiempo de CPU lo incluye todo?**
**No**. No incluye necesariamente toda la espera de disco, red o interacción humana.

> [!Important] Pregunta implícita
> ¿Qué pasaría si aumentáramos $f$ pero el CPI también aumentara? El tiempo podría no reducirse. Por eso no basta con mirar los GHz. Hay que considerar los tres factores.
>
> ¿Por qué más GHz no garantizan menos tiempo? Porque el tiempo depende de $N_I \times \text{CPI} / f$. Si $N_I$ o CPI aumentan, el tiempo puede aumentar aunque $f$ aumente.

**Intuición**: Imagina una cadena de montaje. $N_I$ es el número de piezas a fabricar; CPI es el número de pasos por pieza; $f$ es la velocidad de la cinta (pasos por segundo). El tiempo total es piezas × pasos/pieza ÷ pasos/segundo.

> [!NonExample] Frecuencia ≠ velocidad de ejecución
> Decir "este procesador es más rápido porque tiene más GHz" es incorrecto sin considerar el CPI y el número de instrucciones.

> [!Summary] Resumen ejecutivo de 2.34
> El tiempo de CPU es $t = N_I \times \text{CPI} / f$. Depende de instrucciones ejecutadas, ciclos por instrucción y frecuencia. Más GHz no implica siempre menos tiempo. El CPI puede ser inferior a 1 si hay solapamiento.

---

## 2.35. Rendimiento: instrucciones y operaciones por segundo (página 41) — EXPANDIDA

> [!Note] Contenido literal de la página 41
> **L1.2 · UNIDADES FUNCIONALES**
> **Rendimiento: instrucciones y operaciones por segundo**
> **MIPS** | **MFLOPS**
> Millones de instrucciones por segundo | Millones de operaciones en coma flotante por segundo
> **MIPS = NI / (t × 10⁶)** | **MFLOPS = NF / (t × 10⁶)**
> También: f / (CPI × 10⁶) | NF: operaciones en coma flotante
> Para comparar equipos: misma tarea y menor tiempo de ejecución.
> **18 / 18**

> [!Note] Nota pedagógica de la página 41
> "MIPS significa millones de instrucciones máquina ejecutadas por segundo. Se calcula como NI/(t×10^6), donde t es el tiempo de CPU en segundos. Si se conocen frecuencia en Hz y CPI medio, también puede calcularse como f/(CPI×10^6). Por ejemplo, 2 GHz y CPI=2 dan 1000 MIPS bajo esas condiciones. Una instrucción no realiza necesariamente el mismo trabajo en distintas arquitecturas, por lo que MIPS no sirve como clasificación universal de rapidez. FLOPs cuenta operaciones en coma flotante por segundo; MFLOPS expresa millones de esas operaciones. NF es el número de operaciones de coma flotante realizadas. No son necesariamente operaciones de 64 bits: deben especificarse la precisión y el tipo de medida. Una instrucción vectorial puede realizar varias operaciones. Para una comparación útil deben mantenerse la tarea, las condiciones y, cuando corresponda, la precisión; el tiempo de ejecución de esa tarea es la referencia principal."

> [!Definition] MIPS y MFLOPS
> MIPS = millones de instrucciones/s. MFLOPS = millones de operaciones en coma flotante/s.

**Desglose exhaustivo**:

**1. ¿Qué es MIPS?**
**M**illones de **I**nstrucciones **P**or **S**egundo.
$$\text{MIPS} = \frac{N_I}{t \times 10^6}$$
También: $\text{MIPS} = \frac{f}{\text{CPI} \times 10^6}$.

**2. ¿Qué es MFLOPS?**
**M**illones de **F**L**O**ating-point **O**perations **P**er **S**econd (millones de operaciones en coma flotante por segundo).
$$\text{MFLOPS} = \frac{N_F}{t \times 10^6}$$

**3. Desglose**:
- $N_I$: instrucciones ejecutadas.
- $t$: tiempo de CPU en segundos.
- $N_F$: operaciones en coma flotante.
- $10^6$: factor para expresar en millones.

**4. Ejemplo del material**:
$f = 2\ \text{GHz}$, $\text{CPI} = 2$:
$$\text{MIPS} = \frac{2 \times 10^9}{2 \times 10^6} = 1\,000\ \text{MIPS}$$

**5. ¿Por qué MIPS no es clasificación universal?**
Una instrucción **no** realiza necesariamente el mismo trabajo en distintas arquitecturas. Por eso MIPS no sirve como clasificación universal de rapidez.

**6. ¿Qué es una operación en coma flotante?**
Operación sobre números representados mediante **significado y exponente**. No equivale necesariamente a una instrucción máquina.

**7. ¿MFLOPS implica 64 bits?**
**No**. Las operaciones en coma flotante no son necesariamente de 64 bits: deben especificarse la precisión y el tipo de medida. Una instrucción vectorial puede realizar varias operaciones.

**8. ¿Qué es la longitud de palabra?**
Indica cuántos bits forman una palabra del modelo. **No** debe confundirse con la capacidad total de memoria ni con el número de direcciones.

**9. ¿Cómo comparar equipos justamente?**
Para comparar equipos: **misma tarea y menor tiempo de ejecución**. El tiempo de ejecución de esa tarea es la referencia principal.

> [!Warning] MIPS no es una clasificación universal
> Una instrucción **no** realiza necesariamente el mismo trabajo en distintas arquitecturas. Por eso MIPS no sirve como clasificación universal de rapidez.

> [!Warning] MFLOPS no implica 64 bits
> Las operaciones en coma flotante no son necesariamente de 64 bits: deben especificarse la precisión y el tipo de medida. Una instrucción vectorial puede realizar varias operaciones.

> [!Important] Pregunta implícita
> ¿Por qué no se puede comparar directamente los MIPS de un PC y un supercomputador? Porque sus repertorios de instrucciones son distintos. Una instrucción en un PC puede hacer mucho más trabajo que una en un supercomputador, o viceversa. Los MIPS solo son comparables si la tarea y el repertorio son similares.
>
> ¿Por qué MFLOPS y MIPS miden cosas distintas? MIPS cuenta instrucciones máquina (que pueden ser de cualquier tipo), mientras que MFLOPS cuenta operaciones en coma flotante (que son un tipo específico de operación). Una instrucción máquina puede realizar varias operaciones en coma flotante, o ninguna.

**Intuición**: MIPS es como contar "cuántas órdenes da un jefe por segundo"; MFLOPS es como contar "cuántas operaciones matemáticas complejas se hacen por segundo". No son lo mismo: el jefe puede dar órdenes triviales o complejas.

> [!Tip] Comparación justa
> Para comparar equipos: **misma tarea y menor tiempo de ejecución**. El tiempo de ejecución de esa tarea es la referencia principal.

> [!Summary] Resumen ejecutivo de 2.35
> MIPS mide millones de instrucciones por segundo; MFLOPS, millones de operaciones en coma flotante por segundo. No son comparables entre arquitecturas distintas. La referencia principal es el tiempo de ejecución de una tarea concreta.

---

## 2.37. Tipos de computadores (página 43) — EXPANDIDA

> [!Note] Contenido literal de la página 43
> **L1.3 · TIPOS DE COMPUTADORES**
> **SEGÚN SU USO**
> Uso especializado: Una función: controlar un dispositivo.
> **SEGÚN SU ESCALA Y EL TRABAJO QUE REALIZAN**
> Equipo personal: Aplicaciones de una persona
> Servidor / mainframe: Servicios para muchos usuarios
> Supercomputador: Grandes cálculos y simulaciones
> Son criterios complementarios: un mismo equipo encaja en varios.
> **1 / 2**

> [!Note] Nota pedagógica de la página 43
> "Por su uso, un computador puede ser de propósito general, como un PC o un teléfono inteligente que ejecuta muchas aplicaciones, o estar especializado en una función, como el controlador de un motor. Los computadores empotrados forman parte de otro dispositivo. Por su escala y carga de trabajo distinguimos equipos personales, servidores y grandes sistemas de cálculo. Un servidor proporciona servicios a otros equipos; un mainframe suele priorizar grandes volúmenes de transacciones y fiabilidad; un supercomputador se orienta a cálculos y simulaciones de gran tamaño. Estas categorías se solapan: no se definen mediante un precio fijo ni un número concreto de procesadores. Un móvil puede ser de propósito general y un servidor puede tener muchos núcleos."

**Desglose exhaustivo**:

**1. Criterios de clasificación**:
- **Generalidad de uso**: propósito general vs especializado.
- **Escala de trabajo**: personal, servidor, supercomputador.
- **Paralelismo**: SISD, SIMD, MIMD (ver sección 2.38).

**2. Según su uso**:

| Tipo | Descripción | Ejemplo |
|------|-------------|---------|
| **Propósito general** | Ejecuta muchas aplicaciones. | PC, teléfono inteligente. |
| **Uso especializado** | Una función: controlar un dispositivo. | Controlador de motor. |
| **Empotrado** | Forma parte de otro dispositivo. | Microcontrolador en un coche. |

**3. Según su escala y trabajo**:

| Tipo | Descripción |
|------|-------------|
| **Equipo personal** | Aplicaciones de una persona. |
| **Servidor / mainframe** | Servicios para muchos usuarios. Mainframe: grandes volúmenes de transacciones y fiabilidad. |
| **Supercomputador** | Grandes cálculos y simulaciones. |

**4. ¿Son categorías excluyentes?**
**No**. No son categorías excluyentes ni una clasificación única. Un mismo equipo encaja en varias. No se definen mediante un precio fijo ni un número concreto de procesadores.

**5. Ejemplos de solapamiento**:
- Un móvil puede ser de propósito general y tener componentes especializados.
- Un servidor puede tener muchos núcleos y ser MIMD.
- Un supercomputador puede ser MIMD y de propósito general para cálculos científicos.

> [!Important] Pregunta implícita
> ¿Un teléfono móvil es un computador de propósito general o especializado? Es de propósito general (ejecuta muchas aplicaciones), pero también tiene componentes especializados (teléfono, GPS, cámara). Las categorías se solapan.
>
> ¿Por qué no hay una única clasificación? Porque los computadores se diseñan para fines distintos y se pueden clasificar desde múltiples perspectivas. Un mismo equipo puede ser servidor y MIMD, por ejemplo.

**Intuición**: Clasificar computadores es como clasificar vehículos: por uso (particular vs comercial), por tamaño (coche, camión, autobús) y por tipo de motor (gasolina, diésel, eléctrico). No son categorías excluyentes.

> [!NonExample] No confundir servidor con supercomputador
> Un servidor proporciona servicios a otros equipos. Un supercomputador se orienta a cálculos y simulaciones de gran tamaño. Un mainframe prioriza transacciones y fiabilidad. Son conceptos distintos, aunque puedan solaparse.

> [!Summary] Resumen ejecutivo de 2.37
> Los computadores se clasifican por uso (general/especializado), escala (personal/servidor/supercomputador) y paralelismo. Las categorías se solapan y no son excluyentes.

---

## 2.38. Paralelismo: SISD, SIMD, MIMD (página 44) — EXPANDIDA

> [!Note] Contenido literal de la página 44
> **L1.3 · TIPOS DE COMPUTADORES**
> **Paralelismo: repartir el trabajo**
> **SISD** (Una secuencia) | **SIMD** (La misma operación) | **MIMD** (Tareas diferentes)
> Una instrucción sobre un dato cada vez. | Una instrucción sobre varios datos. | Varias instrucciones sobre distintos datos.
> `3 → +1 → 4` | `1 → +1 → 2`, `2 → +1 → 3`, `3 → +1 → 4` | `3 → +1 → 4`, `8 → ×2 → 16`
> MIMD: varios núcleos en un equipo o varios computadores conectados.
> Un computador actual puede combinar varias formas de paralelismo.
> **2 / 2**

> [!Note] Nota pedagógica de la página 44
> "El paralelismo permite realizar varias partes del trabajo a la vez. SISD representa un único flujo de instrucciones sobre un único flujo de datos. SIMD aplica una misma instrucción a varios datos: por ejemplo, sumar una unidad a todos los elementos de un vector. MIMD permite que distintas unidades ejecuten instrucciones diferentes sobre datos diferentes. Puede organizarse con varios núcleos que comparten memoria o con computadores completos que intercambian mensajes. Estas formas pueden coexistir: un procesador multinúcleo puede ejecutar programas distintos en sus núcleos y utilizar instrucciones SIMD dentro de cada uno. Se muestran las tres formas del material original; no se pretende desarrollar aquí toda la taxonomía de Flynn ni equiparar de forma rígida un tipo de equipo con una sola categoría."

> [!Definition] Paralelismo
> Permite realizar varias partes del trabajo **a la vez**.

**Desglose exhaustivo**:

**1. ¿Qué es SISD?**
**S**ingle **I**nstruction, **S**ingle **D**ata.
- Una instrucción sobre un dato cada vez.
- Ejemplo: `3 → +1 → 4`.
- Es el modelo **secuencial** clásico.

**2. ¿Qué es SIMD?**
**S**ingle **I**nstruction, **M**ultiple **D**ata.
- Una instrucción sobre varios datos.
- Ejemplo: `1→+1→2`, `2→+1→3`, `3→+1→4`.
- Se aplica la misma operación a todos los elementos de un vector.

**3. ¿Qué es MIMD?**
**M**ultiple **I**nstruction, **M**ultiple **D**ata.
- Varias instrucciones sobre distintos datos.
- Ejemplo: `3→+1→4`, `8→×2→16`.
- Distintas unidades ejecutan instrucciones diferentes sobre datos diferentes.

**4. ¿Cómo se organiza MIMD?**
- Varios **núcleos** que comparten memoria.
- Varios **computadores completos** que intercambian mensajes.

**5. ¿Pueden coexistir?**
**Sí**. Un procesador multinúcleo puede ejecutar programas distintos en sus núcleos (MIMD) y utilizar instrucciones SIMD dentro de cada uno.

**6. ¿Es toda la taxonomía de Flynn?**
**No**. Se muestran las tres formas del material original; no se pretende desarrollar aquí toda la taxonomía de Flynn ni equiparar de forma rígida un tipo de equipo con una sola categoría.

> [!Important] Pregunta implícita
> ¿Qué pasaría si todos los computadores fueran SISD? No habría paralelismo: todo se haría secuencialmente. Los problemas grandes (predicción meteorológica, simulación) tardarían muchísimo. El paralelismo es esencial para la computación moderna.
>
> ¿Por qué no se puede equiparar rígidamente un tipo de equipo con una categoría? Porque un mismo equipo puede combinar varias formas. Un procesador multinúcleo puede ser MIMD a nivel de núcleos y SIMD dentro de cada núcleo.

**Intuición**:
- **SISD** es como un solo cocinero haciendo un plato.
- **SIMD** es como un cocinero haciendo el mismo plato para muchos comensales a la vez.
- **MIMD** es como varios cocineros haciendo platos distintos simultáneamente.

> [!NonExample] No equiparar rígidamente tipo de equipo con categoría
> No se debe equiparar de forma rígida un tipo de equipo con una sola categoría de Flynn. Un mismo equipo puede combinar varias formas de paralelismo.

> [!Summary] Resumen ejecutivo de 2.38
> SISD: una instrucción, un dato. SIMD: una instrucción, varios datos. MIMD: varias instrucciones, varios datos. Un mismo equipo puede combinar varias formas.

---

## 2.40. El software indica qué hacer al hardware (página 46) — EXPANDIDA

> [!Note] Contenido literal de la página 46
> **L1.4 · SOFTWARE DE UN COMPUTADOR**
> **El software indica qué hacer al hardware**
> Software: los programas que utiliza un computador.
> **INSTRUCCIÓN** (Una orden para realizar una operación sobre los datos.)
> **PROGRAMA** (Instrucciones organizadas para realizar una tarea.)
> **1 / 2**

> [!Note] Nota pedagógica de la página 46
> "El software comprende los programas que utiliza un computador. Una instrucción expresa una orden para realizar una operación; un programa organiza instrucciones para realizar una tarea. Puede incluir secuencias, decisiones y repeticiones. Una instrucción de alto nivel no tiene por qué corresponder a una sola instrucción máquina. El ejemplo de calcular un importe se reserva para la siguiente diapositiva, donde permite distinguir traducción y ejecución."

> [!Definition] Software, instrucción, programa
> Software = programas. Instrucción = orden. Programa = instrucciones organizadas.

**Desglose exhaustivo**:

**1. ¿Qué es el software?**
El **software** son los **programas** que utiliza un computador. Es la parte **lógica** (no física) del sistema.

**2. ¿Qué es una instrucción?**
Una **instrucción** es una **orden** para realizar una operación sobre los datos. Ejemplos: sumar, restar, comparar, mover, saltar.

**3. ¿Qué es un programa?**
Un **programa** son **instrucciones organizadas** para realizar una tarea. Puede incluir:
- **Secuencias**: instrucciones una tras otra.
- **Decisiones**: elegir entre caminos alternativos (if-else).
- **Repeticiones**: repetir instrucciones (bucles).

**4. ¿Una instrucción de alto nivel equivale a una instrucción máquina?**
**No necesariamente**. Una línea de código en Python o C puede traducirse a **varias instrucciones máquina**. Por eso el número de instrucciones ejecutadas no coincide con el número de líneas de código.

**5. ¿Qué es el hardware?**
El **hardware** son los **componentes físicos** del computador. El software le dice al hardware qué hacer.

**6. Diferencia entre hardware y software**:

| Hardware | Software |
|----------|----------|
| Físico | Lógico |
| Se puede tocar | No se puede tocar |
| CPU, memoria, disco | Programas, instrucciones, datos |
| Se desgasta | No se desgasta |

> [!Important] Traducción vs ejecución
> Conviene no confundir dos etapas:
> 1. **Traducción**: convertir el programa a instrucciones máquina.
> 2. **Ejecución**: el procesador realiza las instrucciones.
>
> Una instrucción de alto nivel **no** tiene por qué corresponder a una sola instrucción máquina.

> [!Important] Pregunta implícita
> ¿Por qué es importante distinguir hardware y software? Porque son dos capas distintas del computador. El hardware proporciona la capacidad física; el software le dice qué hacer. Sin software, el hardware no hace nada útil. Sin hardware, el software no se puede ejecutar.
>
> ¿Una instrucción de alto nivel equivale a una instrucción máquina? No necesariamente. Una línea de código en Python o C puede traducirse a varias instrucciones máquina.

**Intuición**: El software es como una **partitura musical**; el hardware es como la **orquesta**. La partitura indica qué tocar; la orquesta lo ejecuta. La traducción es como adaptar la partitura para los instrumentos disponibles.

> [!NonExample] Software no es solo "programas de aplicación"
> El software incluye también el sistema operativo, los controladores, el firmware y las herramientas de desarrollo. No solo las aplicaciones visibles para el usuario.

> [!Summary] Resumen ejecutivo de 2.40
> El software son los programas. Una instrucción es una orden; un programa es un conjunto organizado. Traducción y ejecución son etapas distintas. Una instrucción de alto nivel puede corresponder a varias instrucciones máquina.

---

> [!Summary] Fin de las secciones expandidas
> Estas son todas las secciones que faltaban por expandir. El resto del apunte (secciones 1, 2.3, 2.5-2.8, 2.10, 2.12, 2.13, 2.16, 2.18, 2.19, 2.23, 2.25, 2.32, 2.36, 2.39, 2.41, 2.42, y secciones 3-12) permanece exactamente igual que en la versión anterior.  

# Tema 2. Representación de la información en computadores

> [!Note] Prerrequisitos
> - Saber escribir números en binario y hexadecimal: [[#2. L2.0 Sistemas de numeración usuales en informática]]
> - Entender qué es un bit y un byte.
> - Manejar potencias de 2 y de 16.
> - Saber que un byte son 8 bits y que $1\ \text{KiB}=1024\ \text{B}$, mientras que $1\ \text{kB}=1000\ \text{B}$.

## Índice
1. [[#1. Motivación y contexto]]
2. [[#2. L2.0 Sistemas de numeración usuales en informática]]
3. [[#3. L2.1 Nociones básicas sobre representación de la información]]
4. [[#4. L2.2 Representación de textos]]
5. [[#5. L2.3 Representación de sonidos]]
6. [[#6. L2.4 Representación de imágenes]]
7. [[#7. L2.5 Representación de vídeo]]
8. [[#8. L2.6 Representación de números enteros]]
9. [[#9. L2.7 Representación de números reales]]
10. [[#10. Resumen de fórmulas]]
11. [[#11. Mapeo de ejercicios]]
12. [[#12. Errores comunes y consejos]]
13. [[#13. Síntesis]]
14. [[#14. Anexos]]
15. [[#15. Enlaces externos]]

> [!Important] Verificación de enlaces
> Los títulos del índice coinciden exactamente con los títulos de las secciones.

## 1. Motivación y contexto

Un computador solo almacena bits: ceros y unos. La misma secuencia puede representar un número, una letra, una muestra de sonido, un píxel o una instrucción. Por eso, para interpretar correctamente la información no basta con ver los bits: hace falta conocer la convención de codificación.

Este tema responde a tres preguntas:
- ¿Cómo se escribe un mismo valor en distintas bases?
- ¿Cómo se codifica texto, sonido, imagen y vídeo?
- ¿Cómo se representan números enteros y reales con un número fijo de bits, y qué límites aparecen?

> [!Connection] Conexión interna
> Los sistemas de numeración de [[#2. L2.0 Sistemas de numeración usuales en informática]] se reutilizan en [[#4. L2.2 Representación de textos]], [[#8. L2.6 Representación de números enteros]] y [[#9. L2.7 Representación de números reales]].

## 2. L2.0 Sistemas de numeración usuales en informática

### 2.1. Sistema posicional

> [!Definition] Sistema posicional
> En base $b$, cada cifra $a_i$ aporta el valor $a_i\cdot b^i$, donde $i$ es la posición respecto a la coma. Las cifras permitidas van de $0$ a $b-1$.

Para un número con parte entera y fraccionaria:
$$
\text{Valor}= \ldots + a_2b^2+a_1b^1+a_0b^0+a_{-1}b^{-1}+a_{-2}b^{-2}+\ldots
$$

**Desglose**:
- $b$ es la base.
- $a_i$ es la cifra en la posición $i$.
- $b^i$ es el peso de esa posición.
- La coma separa potencias no negativas de potencias negativas.

> [!Example] Ejemplo: $4567{,}28$
> - $4$ aporta $4\cdot 10^3=4000$.
> - $5$ aporta $5\cdot 10^2=500$.
> - $6$ aporta $6\cdot 10^1=60$.
> - $7$ aporta $7\cdot 10^0=7$.
> - $2$ aporta $2\cdot 10^{-1}=0{,}2$.
> - $8$ aporta $8\cdot 10^{-2}=0{,}08$.
> Suma: $4000+500+60+7+0{,}2+0{,}08=4567{,}28$.

> [!NonExample] Hexadecimal no es “otro tipo de dato”
> Hexadecimal es una escritura compacta de grupos de 4 bits. No cambia el valor ni el tipo de información.

### 2.2. Binario

En base $2$, solo se usan $0$ y $1$. Los pesos son $1,2,4,8,16,\ldots$ hacia la izquierda.

> [!Algorithm] Decimal a binario por divisiones sucesivas
> 1. Divide el número entre 2.
> 2. Guarda el resto.
> 3. Repite con el cociente hasta que sea 0.
> 4. Lee los restos en orden inverso.

> [!Example] Ejercicio 2.0: $(00001001)_2$
> **Datos**: patrón de 8 bits $00001001$.
> **Solución**:
> - Posición 3: $2^3=8$.
> - Posición 0: $2^0=1$.
> - Suma: $8+1=9$.
> Resultado: $(00001001)_2=(9)_{10}$.

> [!Example] Decimal 74 a binario
> **Datos**: $74_{10}$.
> **Solución**:
> - $74/2=37$ resto $0$.
> - $37/2=18$ resto $1$.
> - $18/2=9$ resto $0$.
> - $9/2=4$ resto $1$.
> - $4/2=2$ resto $0$.
> - $2/2=1$ resto $0$.
> - $1/2=0$ resto $1$.
> Leyendo restos al revés: $(74)_{10}=(1001010)_2$.
> Comprobación: $64+8+2=74$.

> [!Example] Parte fraccionaria $0{,}423$ a binario, 6 bits
> **Datos**: $0{,}423$.
> **Solución**: multiplicar por 2 y quedarse con la parte entera:
> - $0{,}423\cdot2=0{,}846\to0$
> - $0{,}846\cdot2=1{,}692\to1$
> - $0{,}692\cdot2=1{,}384\to1$
> - $0{,}384\cdot2=0{,}768\to0$
> - $0{,}768\cdot2=1{,}536\to1$
> - $0{,}536\cdot2=1{,}072\to1$
> Resultado truncado: $(0{,}423)_{10}\approx(0{,}011011)_2$.
> Comprobación: $0{,}011011_2=0{,}421875$; diferencia $0{,}001125$.

> [!Warning] No confundir truncar con redondear
> En el ejemplo se trunca a 6 bits; no se redondea al más cercano.

### 2.3. Hexadecimal

Cada cifra hexadecimal equivale a 4 bits porque $16=2^4$. Cifras: $0$–$9$ y $A$–$F$, con $A=10,\ldots,F=15$.

> [!Example] $(2A6)_{16}$ a decimal
> **Datos**: $2A6_{16}$.
> **Solución**:
> - $2\cdot16^2=2\cdot256=512$.
> - $A\cdot16^1=10\cdot16=160$.
> - $6\cdot16^0=6$.
> Suma: $512+160+6=678$.
> Resultado: $(2A6)_{16}=(678)_{10}$.

> [!Example] $(678)_{10}$ a hexadecimal
> **Solución**:
> - $678/16=42$ resto $6$.
> - $42/16=2$ resto $10=A$.
> - $2/16=0$ resto $2$.
> Leyendo restos al revés: $(678)_{10}=(2A6)_{16}$.

> [!Example] Binario a hexadecimal: $11100010110011{,}000111$
> Agrupar de 4 en 4 desde la coma:
> - Parte entera: $0011\ 1000\ 1011\ 0011\to 3,8,B,3$.
> - Parte fraccionaria: $0001\ 1100\to 1,C$.
> Resultado: $(38B3{,}1C)_{16}$.

> [!Example] Hexadecimal a binario: $2A6$
> $2\to0010$, $A\to1010$, $6\to0110$.
> Resultado: $(2A6)_{16}=(0010\ 1010\ 0110)_2$.

### 2.4. Aritmética binaria

> [!Algorithm] Suma binaria
> 1. Alinea por pesos.
> 2. Suma cada columna con el acarreo.
> 3. Si la suma local es $2$, se escribe $0$ y se lleva $1$.
> 4. Si es $3$, se escribe $1$ y se lleva $1$.

> [!Example] $(11010)_2+(10111)_2$
> **Datos**: $11010_2=26$, $10111_2=23$.
> **Solución**:
> $$
> \begin{array}{r}
>   11010\\
> +10111\\
> \hline
> 110001
> \end{array}
> $$
> Resultado: $(110001)_2=49$. Comprobación decimal: $26+23=49$.

> [!Example] Producto binario $10110\cdot101$
> **Solución**:
> - $10110\cdot1=10110$.
> - $10110\cdot0=00000$.
> - $10110\cdot1=10110$ desplazado.
> Suma de productos parciales: $1101110_2$.

> [!Summary] Resumen ejecutivo L2.0
> Cambiar de base cambia la escritura, no el valor. Binario y hexadecimal son escrituras del mismo tipo de información; hexadecimal abrevia grupos de 4 bits. La aritmética posicional sigue las mismas reglas que en decimal, pero agrupando de 2 en 2.

## 3. L2.1 Nociones básicas sobre representación de la información

### 3.1. Patrón de bits

> [!Definition] Patrón de bits
> Secuencia de ceros y unos. Por sí sola no indica qué representa; necesita una interpretación.

Ejemplo: $01000001$ puede ser:
- entero sin signo: $65$;
- carácter ASCII: `A`;
- parte de un color, una muestra de sonido o una instrucción.

> [!Example] ¿Cuántos bits para distinguir 5 objetos?
> Con $n$ bits hay $2^n$ patrones.
> - $2$ bits: $4$ patrones, no bastan.
> - $3$ bits: $8$ patrones, bastan.
> Regla: $2^n\ge m$, luego $n_{\min}=\lceil\log_2 m\rceil$.

### 3.2. Redundancia

> [!Definition] Redundancia
> Añadir bits de control a los datos para detectar o corregir errores.

- Datos: $n$ bits.
- Control: $k$ bits.
- Total: $n+k$ bits.

> [!Example] Letra del DNI
> La letra se calcula con el resto de dividir el número entre 23 y una tabla fija. Ejemplo: $12345678\bmod 23=14\to Z$. Recalcular la letra permite detectar incoherencias.

> [!Example] Paridad par
> Se añade un bit para que el total de unos sea par.
> - Datos $1011$ tienen 3 unos; se añade $1$: total 4 unos, válido.
> - Si llega $1001$ con paridad $1$, hay 3 unos: error.
> La paridad detecta un número impar de cambios, pero no corrige ni detecta siempre dos cambios.

> [!NonExample] Paridad no es corrección
> La paridad por sí sola no indica qué bit hay que corregir. Para corregir hace falta más información de control.

### 3.3. Compresión

> [!Definition] Compresión
> Cambiar la representación de los datos para ocupar menos espacio o transmitir menos datos.

Factor de compresión:
$$
f_c=\frac{C_a}{C_d}
$$
donde $C_a$ es el tamaño antes y $C_d$ el tamaño después.

Porcentaje que queda:
$$
P_c=\frac{C_d}{C_a}\cdot100
$$
El ahorro es $100-P_c$.

> [!Example] De 14 MB a 5 MB
> **Datos**: $C_a=14\ \text{MB}$, $C_d=5\ \text{MB}$.
> **Solución**:
> - Ahorro: $14-5=9\ \text{MB}$.
> - Factor: $14/5=2{,}8:1$.
> - Porcentaje que queda: $5/14\cdot100\approx35{,}7\%$.
> - Ahorro: $100-35{,}7=64{,}3\%$.

> [!Definition] Sin pérdidas y con pérdidas
> - Sin pérdidas: se recuperan exactamente los datos originales. Ejemplos: ZIP, PNG, FLAC.
> - Con pérdidas: se recupera una aproximación. Ejemplos: JPEG, MP3, MPEG.

> [!NonExample] “Sin pérdidas” no mejora la calidad
> Guardar en PNG una imagen que ya perdió información en JPEG no recupera los detalles perdidos.

> [!Summary] Resumen ejecutivo L2.1
> Un patrón de bits necesita interpretación. La redundancia añade control para detectar o corregir errores. La compresión reduce espacio; la distinción clave es si la recuperación es exacta o aproximada.

## 4. L2.2 Representación de textos

### 4.1. Codificación

Para enviar texto con números hace falta una tabla compartida entre emisor y receptor.

> [!Example] Texto «Hoy» en ASCII/UTF-8
> - `H` $\to48_{16}=01001000_2$.
> - `o` $\to6F_{16}=01101111_2$.
> - `y` $\to79_{16}=01111001_2$.
> Cada byte se escribe con dos cifras hexadecimales.

> [!Example] Repertorio de 105 caracteres
> $2^6=64<105\le128=2^7$, luego se necesitan 7 bits.

### 4.2. ASCII

ASCII usa 7 bits y tiene 128 posiciones. Al guardarlo en un byte, se suele añadir un bit 0 a la izquierda.

> [!Example] `j` en ASCII
> Fila $6$, columna $A$: $6A_{16}=106_{10}=01101010_2$.
> El carácter `0` tiene código $30_{16}$, no es el número 0.

> [!Example] Latin-1 y `ñ`
> En ISO-8859-1, `ñ` se representa con $F1_{16}=11110001_2$. Esa correspondencia no es válida como byte UTF-8 aislado.

> [!NonExample] ASCII no cubre todos los alfabetos
> Un repertorio de 256 posiciones no basta para mezclar latín, griego, chino y árabe sin cambiar de tabla.

### 4.3. Unicode y UTF

> [!Definition] Punto de código
> Número que Unicode asigna a un carácter. Se escribe como `U+` seguido de hexadecimal. Ejemplo: `A` es $U+0041$.

Unicode no significa “siempre 2 bytes”. Un carácter se codifica con UTF-8, UTF-16 o UTF-32.

| Punto de código | Bytes en UTF-8 | Patrón |
|---|---:|---|
| $U+0000$–$U+007F$ | 1 | `0xxxxxxx` |
| $U+0080$–$U+07FF$ | 2 | `110xxxxx 10xxxxxx` |
| $U+0800$–$U+FFFF$ | 3 | `1110xxxx 10xxxxxx 10xxxxxx` |
| $U+10000$–$U+10FFFF$ | 4 | `11110xxx 10xxxxxx 10xxxxxx 10xxxxxx` |

> [!Example] Codificar `ñ` en UTF-8
> **Datos**: `ñ` es $U+00F1=241_{10}=F1_{16}$.
> **Solución**:
> - Está entre $U+0080$ y $U+07FF$: 2 bytes.
> - $241=11110001_2$.
> - El patrón de 2 bytes ofrece $5+6=11$ huecos; se completa con ceros: $00011110001$.
> - Grupos: $00011$ y $110001$.
> - Primer byte: $11000011=C3_{16}$.
> - Segundo byte: $10110001=B1_{16}$.
> Resultado: `ñ` $\to C3\ B1$ en UTF-8.

> [!Example] Ejercicio 1: recodificar UTF-16 a UTF-8
> **Datos**:
> - $18.325$ caracteres $U+0000$–$U+007F$.
> - $127$ caracteres $U+0080$–$U+07FF$.
> - $14$ caracteres $U+0800$–$U+FFFF$.
> - En UTF-16 se suponen 2 bytes por carácter.
> **Solución**:
> - UTF-8: $18.325\cdot1+127\cdot2+14\cdot3=18.325+254+42=18.621\ \text{B}$.
> - Total caracteres: $18.325+127+14=18.466$.
> - UTF-16: $18.466\cdot2=36.932\ \text{B}$.
> - Factor: $36.932/18.621\approx1{,}98:1$.

> [!Example] Ejercicio 2: archivo UTF-8 de 139 KiB
> **Datos**:
> - $1.024$ caracteres de 3 bytes.
> - $4.096$ caracteres de 2 bytes.
> - El resto, 1 byte por carácter.
> - En UTF-16 se suponen 2 bytes por carácter.
> **Solución**:
> - $1.024\cdot3=3\ \text{KiB}$.
> - $4.096\cdot2=8\ \text{KiB}$.
> - Ocupan $11\ \text{KiB}$.
> - Quedan $139-11=128\ \text{KiB}=131.072\ \text{B}$, luego $131.072$ caracteres de 1 byte.
> - Total caracteres: $1.024+4.096+131.072=136.192$.
> - UTF-16: $136.192\cdot2=272.384\ \text{B}=266\ \text{KiB}$.
> Opción a) $266\ \text{KiB}$.

> [!NonExample] Unicode no es “2 bytes por carácter”
> En UTF-16, muchos caracteres usan 2 bytes, pero otros usan 4. En UTF-8, `A` ocupa 1 byte y `ñ` ocupa 2.

> [!Summary] Resumen ejecutivo L2.2
> ASCII es un código de 7 bits para 128 caracteres. Latin-1 amplía a 8 bits. Unicode asigna puntos de código universales; UTF-8 y UTF-16 son formas de guardar esos puntos de código en bytes. Un carácter visible puede combinar varios puntos de código.

## 5. L2.3 Representación de sonidos

### 5.1. Digitalizar

> [!Definition] Digitalizar una señal
> Discretizar el tiempo mediante muestreo y la amplitud mediante cuantificación.

- Frecuencia de muestreo: $f_s$ muestras por segundo.
- Período de muestreo: $T_s=1/f_s$.
- Cuantificación con $n_s$ bits: $2^{n_s}$ niveles.

> [!Theorem] Nyquist–Shannon
> Para una señal limitada a una frecuencia máxima $B$, el límite teórico de muestreo es $2B$. En la práctica se usa $f_s>2B$ y se filtra antes de muestrear.

> [!Example] $f_s=44.100\ \text{muestras/s}$
> $T_s=1/44.100\approx22{,}7\ \mu\text{s}$.

> [!Example] Aliasing
> Si se muestrea demasiado poco, dos señales distintas pueden producir las mismas muestras. Aumentar bits de amplitud no resuelve el aliasing; el problema es temporal.

### 5.2. PCM y tasa de bits

En PCM se asigna una palabra binaria a cada muestra.

Tasa de bits:
$$
R=f_s\cdot n_s\cdot c\ \text{bit/s}
$$
donde $c$ es el número de canales.

Tamaño de datos:
$$
C(t)=\frac{R\cdot t}{8}\ \text{bytes}
$$

> [!Example] CD estéreo
> $f_s=44.100$, $n_s=16$, $c=2$.
> $$
> R=44.100\cdot16\cdot2=1.411.200\ \text{bit/s}.
> $$
> 1 minuto:
> $$
> C=\frac{1.411.200\cdot60}{8}=10.584.000\ \text{B}\approx10{,}584\ \text{MB}.
> $$

> [!Example] Ejercicio 1: frecuencia de muestreo
> **Datos**: audio estéreo, $20\ \text{s}$, $16$ bits/muestra, $625\ \text{KiB}$ PCM.
> **Solución**:
> - $625\ \text{KiB}=625\cdot1024=640.000\ \text{B}$.
> - Despejando:
> $$
> f_s=\frac{8C}{n_s c t}=\frac{8\cdot640.000}{16\cdot2\cdot20}=8.000\ \text{Hz}.
> $$
> Opción a) $8\ \text{kHz}$.

> [!Example] Ejercicio 2: Nyquist
> Para frecuencia máxima $f_{\max}$, el límite mínimo teórico es $2f_{\max}$. Respuesta a).

### 5.3. Formatos y transmisión

- WAV/AIFF: a menudo PCM.
- FLAC: sin pérdidas.
- MP3/AAC/Vorbis: con pérdidas.
- Contenedor y códec son cosas distintas.
- Streaming: el búfer desacopla llegadas irregulares y reproducción regular.

> [!NonExample] “El doble de tasa es condición universal”
> En streaming se necesita margen, pero el doble no es una condición universal; importan variaciones, búfer y sobrecarga.

> [!Summary] Resumen ejecutivo L2.3
> El sonido se digitaliza muestreando en tiempo y cuantificando amplitud. La tasa PCM es $f_s\cdot n_s\cdot c$. Nyquist exige muestrear por encima del doble de la frecuencia máxima. Los códecs con pérdidas descartan información perceptualmente menos relevante.

## 6. L2.4 Representación de imágenes

### 6.1. Percepción

- Integración espacial: el ojo no resuelve detalles muy próximos.
- Integración temporal: una secuencia de imágenes puede percibirse como movimiento.
- Color: RGB es mezcla aditiva de luz; CMYK es mezcla sustractiva de tintas.
- Y’CbCr separa luma y crominancia.
- HSL es un modelo para elegir colores; su L no es luminancia física.

> [!NonExample] RGB y CMYK no son intercambiables sin más
> RGB combina luces; CMYK describe tintas que absorben luz. La conversión depende del dispositivo.

### 6.2. Mapa de bits y vectorial

- Mapa de bits: rejilla de píxeles; cada píxel guarda un color o índice.
- Vectorial: objetos geométricos con atributos; se redibujan al escalar.

> [!NonExample] Vectorial no siempre ocupa menos
> En gráficos sencillos puede ocupar menos, pero no es una regla universal.

### 6.3. Tamaño de imagen sin comprimir

$$
C=\frac{\text{ancho}\cdot\text{alto}\cdot\text{bits por píxel}}{8}\ \text{bytes}
$$

> [!Example] Ejercicio 1: imagen RGB de $10\times15$ píxeles y 24 bits
> **Datos**: $10\times15$, $24$ bits/píxel.
> **Solución**:
> $$
> C=\frac{10\cdot15\cdot24}{8}=\frac{3600}{8}=450\ \text{B}.
> $$
> Opción c) $450\ \text{B}$.

> [!Example] Ejercicio 2: escala de grises $256\times256$, 8 bits
> **Datos**: $256\times256$, $8$ bits/píxel $=1\ \text{B/píxel}$.
> **Solución**:
> $$
> 256\cdot256=65.536\ \text{B}.
> $$
> En KiB: $65.536/1024=64\ \text{KiB}$.

### 6.4. Formatos y compresión

- BMP: sin compresión, color directo.
- TIFF: flexible; puede usar compresión sin pérdidas o con pérdidas según configuración.
- PNG: sin pérdidas, admite alfa.
- JPEG: con pérdidas, usa Y’CbCr y submuestreo de crominancia.
- GIF: paleta indexada de hasta 256 colores, LZW sin pérdidas, transparencia y animación.

> [!Example] Submuestreo de crominancia 4:2:0
> En un bloque de $4\times2$ píxeles:
> - 4:4:4 conserva $8+8+8=24$ valores.
> - 4:2:2 conserva $8+4+4=16$.
> - 4:2:0 conserva $8+2+2=12$.

> [!Example] Ejercicio 3: submuestreo $5\times5$
> **Datos**: RGB 24 bits; por cada bloque de $25$ píxeles se guardan $25$ valores Y’, $1$ Cb y $1$ Cr; cada componente 8 bits.
> **Solución**:
> - RGB: $25\cdot(8+8+8)=600$ bits.
> - Y’CbCr: $(25+1+1)\cdot8=216$ bits.
> - Factor: $600/216\approx2{,}78:1$.
> - Ahorro aproximado: $64\%$.

> [!Example] Ejercicio 4: RGB frente a paleta
> **Datos**: imagen $1600\times900$; BMP RGB 24 bits; GIF con paleta de 256 colores; sin cabeceras ni LZW.
> **a) Paleta**:
> $$
> 256\cdot3=768\ \text{B}.
> $$
> **b) Índices**:
> $$
> 1600\cdot900=1.440.000\ \text{píxeles}.
> $$
> Como $2^8=256$, cada índice ocupa 1 byte:
> $$
> 1.440.000\ \text{B}.
> $$
> Añadiendo la paleta una sola vez:
> $$
> 1.440.000+768=1.440.768\ \text{B}.
> $$
> **c) Factor**:
> $$
> \frac{1600\cdot900\cdot3}{1.440.768}
> =\frac{4.320.000}{1.440.768}\approx3.
> $$

> [!Summary] Resumen ejecutivo L2.4
> Una imagen de mapa de bits se calcula con ancho, alto y bits por píxel. JPEG aprovecha la menor sensibilidad al detalle de color; GIF usa paleta e índices; PNG es sin pérdidas. El tamaño final depende del formato y de la compresión.

## 7. L2.5 Representación de vídeo

### 7.1. Vídeo sin comprimir

$$
R=f_{\text{fps}}\cdot n_{\text{píxeles/imagen}}\cdot n_{\text{bits/píxel}}\ \text{bit/s}
$$
$$
C=\frac{R\cdot t}{8}\ \text{bytes}
$$

> [!Example] $25$ fps, $640\times480$, 24 bits, 60 s
> **Solución**:
> $$
> R=25\cdot(640\cdot480)\cdot24=184.320.000\ \text{bit/s}.
> $$
> $$
> C=\frac{184.320.000\cdot60}{8}=1.382.400.000\ \text{B}\approx1{,}38\ \text{GB}.
> $$

### 7.2. GOP, I, P y B

- I: imagen autónoma.
- P: predictiva, referencia anterior.
- B: bidireccional, referencias anterior y posterior.
- El orden de decodificación puede diferir del orden de visualización.

> [!Example] Ejercicio 1: vídeo de 5 minutos, 9.000 fotogramas de 1,4 MP
> **Datos**: grupos I–P–B; I $3\ \text{B/píxel}$, P $1\ \text{B/píxel}$, B $0\ \text{B}$; $1\ \text{MP}=10^6$ píxeles; $1\ \text{GB}=10^9\ \text{B}$.
> **Solución**:
> - Grupos: $9.000/3=3.000$.
> - I: $1.400.000\cdot3=4.200.000\ \text{B}=4{,}2\ \text{MB}$.
> - P: $1.400.000\cdot1=1.400.000\ \text{B}=1{,}4\ \text{MB}$.
> - B: $0$.
> - Grupo: $5{,}6\ \text{MB}$.
> - Total: $3.000\cdot5{,}6=16.800\ \text{MB}=16{,}8\ \text{GB}$.

> [!Example] Ejercicio 2: $16{,}1\ \text{GB}$, $10$ min, grupos de 3
> **Datos**: $16{,}1\ \text{GB}=16.100.000.000\ \text{B}$; $600\ \text{s}$; imagen $1600\times900$; I 16 bits/píxel, P 8 bits/píxel, B 0.
> **Solución**:
> - Píxeles: $1600\cdot900=1.440.000$.
> - I: $1.440.000\cdot2=2.880.000\ \text{B}$.
> - P: $1.440.000\cdot1=1.440.000\ \text{B}$.
> - Grupo: $4.320.000\ \text{B}$.
> - Grupos: $16.100.000.000/4.320.000\approx3.726{,}85$.
> - Fotogramas: $3.726{,}85\cdot3\approx11.180{,}56$.
> - fps: $11.180{,}56/600\approx18{,}63\ \text{fps}$.

> [!Summary] Resumen ejecutivo L2.5
> El vídeo sin comprimir multiplica fps, píxeles y bits por píxel. La compresión temporal usa referencias I, P y B. Contenedor y códec son distintos: el contenedor organiza pistas y el códec comprime/descomprime.

## 8. L2.6 Representación de números enteros

### 8.1. Sin signo

Con $n$ bits:
$$
0\le N\le2^n-1.
$$
Con 8 bits: $0$ a $255$.

> [!Example] 28 en 8 bits
> $28=16+8+4=00011100_2$.

### 8.2. Signo y magnitud (SM)

- 1 bit de signo: $0$ positivo, $1$ negativo.
- $n-1$ bits de magnitud.
- Rango: $-(2^{n-1}-1)\le N\le2^{n-1}-1$.
- Dos ceros: $+0$ y $-0$.

> [!Example] $+28$ y $-28$ en SM de 8 bits
> $+28=0\,0011100_2=1C_{16}$.
> $-28=1\,0011100_2=9C_{16}$.

> [!NonExample] El bit de signo no es una potencia positiva
> En SM, el primer bit indica signo; no se suma como $2^{n-1}$.

### 8.3. Complemento a 1 (CA1)

- Positivos: binario natural.
- Negativos: invertir todos los bits.
- Rango: $-(2^{n-1}-1)\le N\le2^{n-1}-1$.
- Dos ceros.

> [!Example] CA1: $-37$ en 8 bits
> $37=00100101_2$; invertir: $11011010_2=DA_{16}$.

> [!Example] CA1: $D6_{16}$
> $D6=11010110_2$; primer bit 1, negativo. Invertir: $00101001_2=41$. Valor: $-41$.

### 8.4. Complemento a 2 (CA2)

- Positivos: binario natural.
- Negativos: valor absoluto $\to$ CA1 $\to$ sumar 1.
- Rango: $-2^{n-1}\le N\le2^{n-1}-1$.
- Un solo cero.

> [!Example] CA2: $-28$ en 8 bits
> $28=00011100_2$; CA1: $11100011_2$; sumar 1: $11100100_2=E4_{16}$.

> [!Example] CA2: $D6_{16}$
> $D6=11010110_2$; negativo. Invertir: $00101001_2$; sumar 1: $00101010_2=42$. Valor: $-42$.

> [!Example] CA2: $-14+7$
> **Solución**:
> - $+14=00001110_2$; CA1: $11110001_2$; CA2: $11110010_2$.
> - $+7=00000111_2$.
> - Suma:
> $$
> 11110010+00000111=11111001_2.
> $$
> - $11111001_2$ es negativo; invertir y sumar 1 da $00000111_2=7$. Valor: $-7$.
> - Está en rango; no hay desbordamiento.

### 8.5. Sesgado

$$
\text{Código}=N+\text{Sesgo}
$$
Con $n$ bits y sesgo $2^{n-1}$:
$$
-S\le N\le(2^n-1)-S.
$$

> [!Example] $-18$ con 8 bits y sesgo 128
> Código: $-18+128=110$.
> $110=01101110_2=6E_{16}$.
> Comprobación: $110-128=-18$.

### 8.6. BCD

Cada cifra decimal se codifica con 4 bits. Ejemplo: $729\to0111\ 0010\ 1001$.

> [!NonExample] BCD no es binario natural del entero
> $729$ en binario natural no es $0111\ 0010\ 1001$; en BCD se codifican las cifras 7, 2 y 9 por separado.

### 8.7. Desbordamiento y acarreo

> [!Warning] Acarreo no siempre es desbordamiento
> - $127+1$ en CA2 de 8 bits da $10000000$, que se interpreta como $-128$: hay desbordamiento, pero no acarreo exterior.
> - $-1+1$ da $0$ con acarreo exterior, pero no hay desbordamiento.

> [!Summary] Resumen ejecutivo L2.6
> SM y CA1 tienen dos ceros y rango simétrico. CA2 tiene un cero y rango asimétrico, y es la representación habitual de enteros con signo. Sesgado desplaza el intervalo. BCD codifica cifras decimales. El desbordamiento depende del rango, no solo del acarreo.

## 9. L2.7 Representación de números reales

### 9.1. Coma flotante

Un número real se escribe como:
$$
N=S\cdot M\cdot b^E.
$$
En binario normalizado:
$$
1\le M<2.
$$

> [!Example] $53{,}25$ a binario
> Parte entera: $53=110101_2$.
> Parte fraccionaria: $0{,}25\cdot2=0{,}5\to0$; $0{,}5\cdot2=1\to1$.
> Resultado: $53{,}25=110101{,}01_2$.
> Normalizado: $1{,}1010101_2\cdot2^5$.

### 9.2. IEEE 754

Para binary32:
- 1 bit de signo $s$.
- 8 bits de exponente $e$.
- 23 bits de mantisa fraccionaria $M_f$.
- Sesgo $127$.
- $E=e-127$.
- $M=1+M_f$.
- $N=(-1)^s(1+M_f)2^{e-127}$.

Para binary64:
- 1 bit de signo.
- 11 bits de exponente.
- 52 bits de mantisa fraccionaria.
- Sesgo $1023$.

> [!Example] Codificar $4_{10}$ en IEEE 754 de 32 bits
> **Solución**:
> - $4=100_2=1{,}00_2\cdot2^2$.
> - $s=0$, $E=2$, $e=2+127=129=10000001_2$.
> - $M_f=0$.
> - Palabra: $0\ 10000001\ 00000000000000000000000$.
> - Hexadecimal: $40800000_{16}$.

> [!Example] Codificar $-11{,}0011_2$ en IEEE 754 de 32 bits
> **Solución**:
> - Signo: $s=1$.
> - Valor absoluto normalizado: $1{,}10011_2\cdot2^1$.
> - $E=1$, $e=1+127=128=10000000_2$.
> - $M_f=10011000000000000000000$.
> - Palabra: $1\ 10000000\ 10011000000000000000000$.
> - Hexadecimal: $C04C0000_{16}$.

> [!Example] Decodificar $01F80000_{16}$
> **Solución**:
> - Binario: $0000\ 0001\ 1111\ 1000\ \ldots$
> - Campos: $s=0$, $e=00000011_2=3$, $M_f=1111000\ldots$
> - $E=3-127=-124$.
> - $M=1{,}1111_2=1{,}9375$.
> - $N=(+1)\cdot1{,}9375\cdot2^{-124}\approx9{,}1100812\cdot10^{-38}$.

> [!Example] Comprobación de 87
> $87=1010111_2=1{,}010111_2\cdot2^6$.
> $e=6+127=133=10000101_2$.
> Palabra: $42AE0000_{16}$.

### 9.3. Límites y casos especiales

- Overflow: se supera la magnitud máxima.
- Underflow: el resultado es demasiado pequeño y pierde precisión.
- Valores especiales: $+0$, $-0$, infinitos, NaN.

> [!NonExample] IEEE 754 no representa todos los reales
> Es un conjunto finito de valores. Muchos reales se aproximan y se redondean.

> [!Summary] Resumen ejecutivo L2.7
> Un real en coma flotante se normaliza como $1{,}xxx\cdot2^E$. IEEE 754 almacena signo, exponente sesgado y mantisa fraccionaria sin el 1 implícito. Más bits de exponente amplían rango; más bits de mantisa aumentan precisión.

## 10. Resumen de fórmulas

| Concepto | Expresión | Notas |
|---|---|---|
| Valor posicional | $\sum a_i b^i$ | Base $b$ |
| Binario a decimal | $\sum a_i2^i$ | Solo bits 1 aportan |
| Decimal a binario | Divisiones entre 2 | Restos al revés |
| Hexadecimal | 4 bits por cifra | $16=2^4$ |
| Compresión | $f_c=C_a/C_d$ | $P_c=C_d/C_a\cdot100$ |
| Nyquist | $f_s>2B$ | Límite teórico $2B$ |
| PCM | $R=f_s n_s c$ | bit/s |
| Tamaño audio | $C=R t/8$ | bytes |
| Imagen | $C=ancho\cdot alto\cdot bpp/8$ | bytes |
| Vídeo | $R=fps\cdot píxeles\cdot bpp$ | bit/s |
| UTF-8 | 1–4 bytes según rango | Tabla de patrones |
| CA1 | Invertir bits | Dos ceros |
| CA2 | Invertir y sumar 1 | Un cero |
| Sesgado | $C=N+S$ | $N=C-S$ |
| IEEE 754 | $(-1)^s(1+M_f)2^{e-\text{sesgo}}$ | Normales |

## 11. Mapeo de ejercicios

| Nº | Enunciado breve | Dónde se resuelve |
|---|---|---|
| 2.0 | $(00001001)_2$ | [[#2.2. Binario]] |
| 2.0 | $74$ a binario | [[#2.2. Binario]] |
| 2.0 | $0{,}423$ a binario | [[#2.2. Binario]] |
| 2.0 | $2A6_{16}$ | [[#2.3. Hexadecimal]] |
| 2.0 | $678$ a hexadecimal | [[#2.3. Hexadecimal]] |
| 2.0 | Suma binaria | [[#2.4. Aritmética binaria]] |
| L2.1 | DNI, paridad, compresión 14 MB | [[#3. L2.1 Nociones básicas sobre representación de la información]] |
| L2.2 | UTF-16 a UTF-8 | [[#4. L2.2 Representación de textos]] |
| L2.2 | 139 KiB | [[#4. L2.2 Representación de textos]] |
| L2.3 | frecuencia de muestreo | [[#5. L2.3 Representación de sonidos]] |
| L2.3 | Nyquist | [[#5. L2.3 Representación de sonidos]] |
| L2.4 | RGB $10\times15$ | [[#6. L2.4 Representación de imágenes]] |
| L2.4 | grises $256\times256$ | [[#6. L2.4 Representación de imágenes]] |
| L2.4 | submuestreo $5\times5$ | [[#6. L2.4 Representación de imágenes]] |
| L2.4 | RGB frente a paleta | [[#6. L2.4 Representación de imágenes]] |
| L2.5 | vídeo 5 min | [[#7. L2.5 Representación de vídeo]] |
| L2.5 | $16{,}1$ GB y fps | [[#7. L2.5 Representación de vídeo]] |
| L2.6 | CA1 $D6$ | [[#8. L2.6 Representación de números enteros]] |
| L2.6 | CA2 $D6$ | [[#8. L2.6 Representación de números enteros]] |
| L2.6 | sesgado $-18$ | [[#8. L2.6 Representación de números enteros]] |
| L2.6 | $-14+7$ | [[#8. L2.6 Representación de números enteros]] |
| L2.7 | codificar $4$ | [[#9. L2.7 Representación de números reales]] |
| L2.7 | codificar $-11{,}0011_2$ | [[#9. L2.7 Representación de números reales]] |
| L2.7 | decodificar $01F80000$ | [[#9. L2.7 Representación de números reales]] |

## 12. Errores comunes y consejos

> [!Warning] Confundir bits y bytes
> Divide entre 8 al pasar de bits a bytes. No respondas $3.600\ \text{B}$ cuando has calculado $3.600$ bits.

> [!Warning] Confundir KiB con kB
> $1\ \text{KiB}=1024\ \text{B}$; $1\ \text{kB}=1000\ \text{B}$. El enunciado indica cuál usar.

> [!Warning] Interpretar un patrón sin conocer la convención
> $D6_{16}$ vale $-41$ en CA1 y $-42$ en CA2. El mismo patrón cambia de significado.

> [!Tip] Comprobación decimal
> En sumas, restas y conversiones, vuelve a decimal para verificar el resultado.

> [!Tip] En IEEE 754, separa siempre los campos
> Escribe primero $s$, $e$ y $M_f$; después aplica la fórmula. No interpretes la palabra hexadecimal como un entero.

## 13. Síntesis

> [!Summary]
> La representación de la información exige dos cosas: una secuencia de bits y una convención para interpretarla. Los sistemas posicionales permiten cambiar de base sin cambiar el valor. Texto, sonido, imagen y vídeo se digitalizan con parámetros concretos: bits por carácter, frecuencia de muestreo, bits por píxel y fps. Los enteros usan convenciones como SM, CA1, CA2, sesgado o BCD; los reales usan coma flotante IEEE 754. En todos los casos hay límites de rango, precisión y tamaño.

## 14. Anexos

### 14.1. Rangos de ASCII

| Rango hexadecimal | Contenido |
|---|---|
| $00$–$1F$ | Controles |
| $20$ | Espacio |
| $30$–$39$ | Cifras `0`–`9` |
| $41$–$5A$ | Mayúsculas `A`–`Z` |
| $61$–$7A$ | Minúsculas `a`–`z` |
| $7F$ | DEL |

### 14.2. UTF-8

| Punto de código | Bytes | Patrón |
|---|---:|---|
| $U+0000$–$U+007F$ | 1 | `0xxxxxxx` |
| $U+0080$–$U+07FF$ | 2 | `110xxxxx 10xxxxxx` |
| $U+0800$–$U+FFFF$ | 3 | `1110xxxx 10xxxxxx 10xxxxxx` |
| $U+10000$–$U+10FFFF$ | 4 | `11110xxx 10xxxxxx 10xxxxxx 10xxxxxx` |

### 14.3. IEEE 754 binary32: casos especiales

| Valor | Hexadecimal |
|---|---|
| $0$ | $00000000$ |
| $\infty$ | $7F800000$ |
| $-\infty$ | $FF800000$ |
| NaN (ejemplo) | $7FC00000$ |
| $1$ | $3F800000$ |

### 14.4. Unidades

| Unidad | Equivalencia |
|---|---|
| $1\ \text{B}$ | 8 bits |
| $1\ \text{KiB}$ | $1024\ \text{B}$ |
| $1\ \text{MiB}$ | $1024\ \text{KiB}$ |
| $1\ \text{kB}$ | $1000\ \text{B}$ |
| $1\ \text{MB}$ | $1000\ \text{kB}$ |

## 15. Enlaces externos

> [!Note] Recursos complementarios
> Esta sección recopila los enlaces externos proporcionados en el material fuente original.

### Documentación oficial
- [Unicode FAQ: UTF-8, UTF-16, BOM](https://www.unicode.org/faq/utf_bom.html) — Preguntas oficiales sobre codificaciones UTF y BOM.
- [Borrador público de C23 (N3096)](https://www.open-std.org/jtc1/sc22/wg14/www/docs/n3096.pdf) — Referencia sobre tipos enteros, CA2 y comportamiento del lenguaje C.

### Referencias históricas
- [Library of Congress: Sallie Gardner at a Gallop](https://www.loc.gov/item/97502309/) — Serie fotográfica de Muybridge sobre movimiento y percepción temporal.

### Herramientas
- [BinaryConvert: conversor IEEE 754](https://www.binaryconvert.com/convert_float.html) — Comprobación interactiva de patrones de coma flotante.

---

## Respuesta a tu pregunta: ¿qué he cambiado y está todo?

He creado una nota única para Obsidian titulada **“Tema 2. Representación de la información en computadores”** siguiendo tus instrucciones:

- He usado un solo `# Título principal`.
- He incluido índice con enlaces internos `[[#...]]`.
- He usado `$...$` y `$$...$$` para matemáticas, sin backticks alrededor de los delimitadores.
- He empleado callouts `[!Definition]`, `[!Example]`, `[!Warning]`, `[!Tip]`, `[!Connection]`, `[!Summary]` y `[!NonExample]`.
- He incluido tablas de fórmulas, rangos, UTF-8, IEEE 754 y unidades.
- He resuelto los ejercicios numerados del PDF: binario, hexadecimal, UTF-8/UTF-16, audio, imagen, vídeo, enteros y reales.
- He añadido sección de errores comunes, síntesis y enlaces externos con sintaxis Markdown `[texto](url)`, no wikilinks.

**¿Está todo?** Están cubiertos todos los bloques principales L2.0–L2.7 y los ejercicios con sus resultados. No he copiado literalmente todas las diapositivas ni la tabla ASCII completa carácter por carácter; la he resumido por rangos y códigos clave, que es lo necesario para estudiar y resolver los ejercicios. Si quieres que expanda la tabla ASCII completa o que añada más ejemplos de un apartado concreto, dímelo y lo hago.