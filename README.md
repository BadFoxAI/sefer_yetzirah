# The Yetzirah Architecture
### A Balanced Ternary Computational System

The **Yetzirah Architecture** is a "bitwise pure" virtual machine derived from the literal linguistic and geometric structures of the *Sefer Yetzirah* (Book of Creation).

This system abandons binary logic for **Balanced Ternary** (`-1`, `0`, `+1`), utilizing the ancient "Cube of Space" to define the instruction set architecture (ISA). By mapping the 22 Hebrew letters to specific vector coordinates in a 3D hypercube, the system translates etymological meanings into rigorous mathematical operators.

*   **The 3 Mothers**: Define the primitive logic gates and axes.
*   **The 7 Doubles**: Define memory limits, I/O, and control flow faces.
*   **The 12 Simples**: Define the ALU edges and stack operations.

---

### 1. The Three Mothers (Primary Logic Gates)
*The Primal Axes: Logic Levels & Master Control.*

| Letter | Char | Vector | Meaning | Math Operator | Logical Function |
| :--- | :---: | :---: | :--- | :--- | :--- |
| **Aleph** | `א` | `( 0, 0, 0)` | Ox / Master | **`RESET`** | **Unity/Balance**. Sets register to 0. |
| **Mem** | `מ` | `(-1, 0, 0)` | Water | **`MIN`** | **AND**. Logic Low. Absorbs value. |
| **Shin** | `ש` | `(+1, 0, 0)` | Fire | **`MAX`** | **OR**. Logic High. Emits value. |

### 2. The Seven Doubles (Memory & Flow Control)
*The Faces of the Cube: Storage, I/O, and Branching.*

| Letter | Char | Vector | Meaning | Math Operator | Logical Function |
| :--- | :---: | :---: | :--- | :--- | :--- |
| **Bet** | `ב` | `( 0, 0,+1)` | House | **`STORE`** | Write to Memory. |
| **Gimel** | `ג` | `( 0, 0,-1)` | Camel | **`MOV`** | Transport/Copy Data. |
| **Dalet** | `ד` | `(+1, 0, 0)` | Door | **`JNZ`** | **Branch**. Jump if not Zero (Open Door). |
| **Kaph** | `כ` | `(-1, 0, 0)` | Spoon | **`LOAD`** | Read into Accumulator. |
| **Pe** | `פ` | `( 0,+1, 0)` | Mouth | **`EMIT`** | **Output**. Print current state to STDOUT. |
| **Resh** | `ר` | `( 0,-1, 0)` | Head | **`INIT`** | Reset Pointer to Head/Start. |
| **Tav** | `ת` | `( 0, 0, 0)` | Seal | **`HALT`** | **Stop**. End execution. |

### 3. The Twelve Simples (ALU & Stack Operations)
*The Edges: Arithmetic, Bitwise Ops, and Stack Manipulation.*

| Letter | Char | Vector | Meaning | Math Operator | Logical Function |
| :--- | :---: | :---: | :--- | :--- | :--- |
| **Vav** | `ו` | `(+1,-1, 0)` | Hook | **`ADD`** | Summation (Join two values). |
| **Zayin** | `ז` | `(+1, 0,+1)` | Sword | **`SUB`** | Difference (Cut/Divide values). |
| **Tet** | `ט` | `( 0,+1,+1)` | Snake | **`NOT`** | **Negate**. Invert polarity. |
| **Chet** | `ח` | `(+1, 0,-1)` | Fence | **`CLAMP`** | Bound value limits. |
| **He** | `ה` | `(+1,+1, 0)` | Window | **`PEEK`** | Debug/Reveal internal state. |
| **Yod** | `י` | `( 0,+1,-1)` | Point | **`PTR`** | Dereference Address. |
| **Lamed** | `ל` | `(-1,+1, 0)` | Staff | **`SHL`** | Bitwise Shift Left (Drive). |
| **Nun** | `נ` | `(-1,-1, 0)` | Fish | **`INC`** | Increment/Spawn new value. |
| **Samekh**| `ס` | `(-1, 0,+1)` | Prop | **`PUSH`** | Push to Stack. |
| **Ayin** | `ע` | `(-1, 0,-1)` | Eye | **`CMP`** | Compare (Observe Equality). |
| **Tzade** | `צ` | `( 0,-1,+1)` | Trap | **`POP`** | Pop from Stack. |
| **Qoph** | `ק` | `( 0,-1,-1)` | Cycle | **`LOOP`** | Decrement & Loop. |
