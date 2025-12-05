SEFER YETZIRAH SYSTEM ARCHITECTURE: THE 22 OPERATORS
========================================================================================================================
LETTER   CHAR  LITERAL MEANING      SY GROUP  VECTOR       CUBE LOCATION     MATH OPERATOR  LOGICAL FUNCTION
------------------------------------------------------------------------------------------------------------------------
Aleph    א     Ox / Master          Mother    ( 0, 0, 0)   Axis: Air         RESET / UNITY  Master Reset (Set to 0)
Mem      מ     Water / Chaos        Mother    (-1, 0, 0)   Axis: West (-)    MIN / AND      Logic Low (Absorb/Min)
Shin     ש     Tooth / Fire         Mother    (+1, 0, 0)   Axis: East (+)    MAX / OR       Logic High (Emit/Max)

Bet      ב     House / Tent         Double    ( 0, 0,+1)   Face: Up          STORE          Write to Memory
Gimel    ג     Camel / Bridge       Double    ( 0, 0,-1)   Face: Down        MOV            Transport/Copy Data
Dalet    ד     Door / Gate          Double    (+1, 0, 0)   Face: East        JNZ / BRANCH   Conditional Jump (!=0)
Kaph     כ     Palm / Spoon         Double    (-1, 0, 0)   Face: West        LOAD           Read into Accumulator
Pe       פ     Mouth / Opening      Double    ( 0,+1, 0)   Face: North       EMIT / OUT     Output/Print State
Resh     ר     Head / Beginning     Double    ( 0,-1, 0)   Face: South       INIT           Reset Pointer to Head
Tav      ת     Mark / Seal          Double    ( 0, 0, 0)   Center (Palace)   HALT           Stop Execution

He       ה     Window / Reveal      Simple    (+1,+1, 0)   Edge: North-East  PEEK / DEBUG   Reveal Internal State
Vav      ו     Hook / Peg           Simple    (+1,-1, 0)   Edge: South-East  ADD / JOIN     Summation (Join values)
Zayin    ז     Sword / Weapon       Simple    (+1, 0,+1)   Edge: East-Up     SUB / CUT      Difference (Cut values)
Chet     ח     Fence / Wall         Simple    (+1, 0,-1)   Edge: East-Down   CLAMP          Enforce Limits (Fence)
Tet      ט     Snake / Coil         Simple    ( 0,+1,+1)   Edge: North-Up    NOT / INVERT   Flip Polarity (Negate)
Yod      י     Hand / Point         Simple    ( 0,+1,-1)   Edge: North-Down  PTR / DEREF    Pointer (Value at Addr)
Lamed    ל     Goad / Staff         Simple    (-1,+1, 0)   Edge: North-West  SHL / DRIVE    Bitwise Shift Left
Nun      נ     Fish / Sprout        Simple    (-1,-1, 0)   Edge: South-West  INC / SPAWN    Increment/Allocate
Samekh   ס     Prop / Support       Simple    (-1, 0,+1)   Edge: West-Up     PUSH           Push to Stack
Ayin     ע     Eye / See            Simple    (-1, 0,-1)   Edge: West-Down   CMP / TEST     Compare (Observe Equal)
Tzade    צ     Hook / Trap          Simple    ( 0,-1,+1)   Edge: South-Up    POP            Pop from Stack
Qoph     ק     Monkey / Cycle       Simple    ( 0,-1,-1)   Edge: South-Down  LOOP / DEC     Decrement & Loop
========================================================================================================================
