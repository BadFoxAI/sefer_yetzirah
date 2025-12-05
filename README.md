Here is the raw Markdown table for the **Sefer Yetzirah System Architecture**. You can copy and paste the block below directly into your documentation.

```markdown
| Letter | Char | Literal Meaning | SY Group | Vector $(x, y, z)$ | Cube Location | Math Operator | Logical Function |
| :--- | :---: | :--- | :---: | :---: | :--- | :--- | :--- |
| **Aleph** | א | Ox / Master / Leader | Mother | $(0, 0, 0)$ | Axis: Air (Balance) | `RESET / UNITY` | Master Reset (Set to 0/Neutral). Carrier wave. |
| **Mem** | מ | Water / Chaos | Mother | $(-1, 0, 0)$ | Axis: West (Negative) | `MIN / AND` | Returns the lower/absorptive value (Logic Low). |
| **Shin** | ש | Tooth / Fire / Sharp | Mother | $(+1, 0, 0)$ | Axis: East (Positive) | `MAX / OR` | Returns the higher/emissive value (Logic High). |
| | | | | | | | |
| **Bet** | ב | House / Tent | Double | $(0, 0, +1)$ | Face: Up | `STORE` | Write value to memory (The Container). |
| **Gimel** | ג | Camel / Bridge | Double | $(0, 0, -1)$ | Face: Down | `MOV` | Transport/Copy data from Source to Dest. |
| **Dalet** | ד | Door / Gate | Double | $(+1, 0, 0)$ | Face: East | `JNZ / BRANCH` | Conditional Jump (Open the door if value != 0). |
| **Kaph** | כ | Palm / Spoon | Double | $(-1, 0, 0)$ | Face: West | `LOAD` | Read/Scoop value into Accumulator. |
| **Pe** | פ | Mouth / Opening | Double | $(0, +1, 0)$ | Face: North | `EMIT / OUT` | Output/Speak the current state. |
| **Resh** | ר | Head / Beginning | Double | $(0, -1, 0)$ | Face: South | `INIT` | Initialize Pointer to Head (Start). |
| **Tav** | ת | Mark / Sign / Seal | Double | $(0, 0, 0)$ | Center (Palace) | `HALT` | Stop execution (The Seal of Completion). |
| | | | | | | | |
| **He** | ה | Window / Reveal | Simple | $(+1, +1, 0)$ | Edge: North-East | `PEEK / DEBUG` | Reveal raw internal state of a register. |
| **Vav** | ו | Hook / Peg | Simple | $(+1, -1, 0)$ | Edge: South-East | `ADD / JOIN` | Connects two values (Summation). |
| **Zayin** | ז | Sword / Weapon | Simple | $(+1, 0, +1)$ | Edge: East-Up | `SUB / CUT` | Divides/Differences two values. |
| **Chet** | ח | Fence / Wall | Simple | $(+1, 0, -1)$ | Edge: East-Down | `CLAMP` | Enforce limits (Logic Fence). |
| **Tet** | ט | Snake / Coil | Simple | $(0, +1, +1)$ | Edge: North-Up | `NOT / INVERT` | Flip polarity (1 becomes -1). |
| **Yod** | י | Hand / Point | Simple | $(0, +1, -1)$ | Edge: North-Down | `PTR / DEREF` | Pointer logic (Value at address). |
| **Lamed** | ל | Goad / Staff | Simple | $(-1, +1, 0)$ | Edge: North-West | `SHL / DRIVE` | Bitwise Shift Left (Drive forward). |
| **Nun** | נ | Fish / Sprout | Simple | $(-1, -1, 0)$ | Edge: South-West | `INC / SPAWN` | Increment/Allocate new value. |
| **Samekh**| ס | Prop / Support | Simple | $(-1, 0, +1)$ | Edge: West-Up | `PUSH` | Push value onto Stack (Support). |
| **Ayin** | ע | Eye / See | Simple | $(-1, 0, -1)$ | Edge: West-Down | `CMP / TEST` | Compare (Observe equality). |
| **Tzade** | צ | Hook / Trap | Simple | $(0, -1, +1)$ | Edge: South-Up | `POP` | Pop value from Stack (Catch). |
| **Qoph** | ק | Monkey / Eye of Needle | Simple | $(0, -1, -1)$ | Edge: South-Down | `LOOP / DEC` | Decrement & Loop (Mimic cycle). |
```
