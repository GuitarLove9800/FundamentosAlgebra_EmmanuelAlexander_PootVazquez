
## 12. Sistemas de numeración (Ejercicios 73 a 102)

### Conversión de binario a decimal (73 a 78)
- **73) $00001111_2$**
  - Proceso: $2^3 + 2^2 + 2^1 + 2^0 = 8 + 4 + 2 + 1 = 15$
  - **Resultado:** $15$
- **74) $10011001_2$**
  - Proceso: $128 + 16 + 8 + 1 = 153$
  - **Resultado:** $153$
- **75) $11001100_2$**
  - Proceso: $128 + 64 + 8 + 4 = 204$
  - **Resultado:** $204$
- **76) $01111011_2$**
  - Proceso: $64 + 32 + 16 + 8 + 2 + 1 = 123$
  - **Resultado:** $123$
- **77) $00000000\;11111111_2$**
  - Proceso: $128 + 64 + 32 + 16 + 8 + 4 + 2 + 1 = 255$
  - **Resultado:** $255$
- **78) $00000010\;00000000_2$**
  - Proceso: El bit encendido está en la posición $2^9 = 512$
  - **Resultado:** $512$

### Conversión de binario a octal (79 a 84)
*Se agrupa de 3 en 3 bits de derecha a izquierda.*
- **79) $11010101_2$**
  - Agrupación: $011 \mid 010 \mid 101 \implies 3, 2, 5$
  - **Resultado:** $325_8$
- **80) $01101110_2$**
  - Agrupación: $001 \mid 101 \mid 110 \implies 1, 5, 6$
  - **Resultado:** $156_8$
- **81) $10110011_2$**
  - Agrupación: $010 \mid 110 \mid 011 \implies 2, 6, 3$
  - **Resultado:** $263_8$
- **82) $00000000\;11111111_2$**
  - Descartando ceros a la izquierda: $11111111_2 \implies 011 \mid 111 \mid 111 \implies 3, 7, 7$
  - **Resultado:** $377_8$
- **83) $00000011\;11000000_2$**
  - Bits significativos: $1111000000_2 \implies 001 \mid 111 \mid 000 \mid 000 \implies 1, 7, 0, 0$ (o $01700_8$)
  - **Resultado:** $1700_8$
- **84) $00000101\;01010101_2$**
  - Agrupación: $000 \mid 001 \mid 010 \mid 101 \mid 010 \mid 101 \implies 0, 1, 2, 5, 2, 5$
  - **Resultado:** $12525_8$ (o $052525_8$)

### Conversión de binario a hexadecimal (85 a 90)
*Se agrupa de 4 en 4 bits de derecha a izquierda.*
- **85) $11011010_2$**
  - Agrupación: $1101_2 = 13 = \text{D}$, $1010_2 = 10 = \text{A}$
  - **Resultado:** $\text{DA}_{16}$
- **86) $01111100_2$**
  - Agrupación: $0111_2 = 7$, $1100_2 = 12 = \text{C}$
  - **Resultado:** $7\text{C}_{16}$
- **87) $10110101_2$**
  - Agrupación: $1011_2 = 11 = \text{B}$, $0101_2 = 5$
  - **Resultado:** $\text{B}5_{16}$
- **88) $11110000\;10100101_2$**
  - Agrupación: $1111 = \text{F}$, $0000 = 0$, $1010 = \text{A}$, $0101 = 5$
  - **Resultado:** $\text{F0A5}_{16}$
- **89) $00001111\;00001111_2$**
  - Agrupación: $0000 = 0$, $1111 = \text{F}$, $0000 = 0$, $1111 = \text{F}$
  - **Resultado:** $0\text{F}0\text{F}_{16}$ (o $\text{F0F}_{16}$)
- **90) $10000000\;00000001_2$**
  - Agrupación: $1000 = 8$, $0000 = 0$, $0000 = 0$, $0001 = 1$
  - **Resultado:** $8001_{16}$

### Conversión de octal a binario (91 a 96)
*Cada dígito octal se expande a 3 bits.*
- **91) $325_8$**
  - $3 \to 011$, $2 \to 010$, $5 \to 101$
  - **Resultado:** $11010101_2$
- **92) $156_8$**
  - $1 \to 001$, $5 \to 101$, $6 \to 110$
  - **Resultado:** $1101110_2$
- **93) $377_8$**
  - $3 \to 011$, $7 \to 111$, $7 \to 111$
  - **Resultado:** $11111111_2$
- **94) $01777_8$**
  - $0 \to 000$, $1 \to 001$, $7 \to 111$, $7 \to 111$, $7 \to 111$
  - **Resultado:** $1111111111_2$
- **95) $03700_8$**
  - $0 \to 000$, $3 \to 011$, $7 \to 111$, $0 \to 000$, $0 \to 000$
  - **Resultado:** $11111000000_2$
- **96) $05255_8$**
  - $0 \to 000$, $5 \to 101$, $2 \to 010$, $5 \to 101$, $5 \to 101$
  - **Resultado:** $101010101101_2$

### Conversión de hexadecimal a binario (97 a 102)
*Cada dígito hexadecimal se expande a 4 bits.*
- **97) $\text{DA}_{16}$**
  - $\text{D} = 13 \to 1101$, $\text{A} = 10 \to 1010$
  - **Resultado:** $11011010_2$
- **98) $7\text{C}_{16}$**
  - $7 \to 0111$, $\text{C} = 12 \to 1100$
  - **Resultado:** $01111100_2$
- **99) $\text{B}5_{16}$**
  - $\text{B} = 11 \to 1011$, $5 \to 0101$
  - **Resultado:** $10110101_2$
- **100) $\text{F0A5}_{16}$**
  - $\text{F} \to 1111$, $0 \to 0000$, $\text{A} \to 1010$, $5 \to 0101$
  - **Resultado:** $1111000010100101_2$
- **101) $0\text{F}0\text{F}_{16}$**
  - $0 \to 0000$, $\text{F} \to 1111$, $0 \to 0000$, $\text{F} \to 1111$
  - **Resultado:** $0000111100001111_2$ (o $111100001111_2$)
- **102) $8001_{16}$**
  - $8 \to 1000$, $0 \to 0000$, $0 \to 0000$, $1 \to 0001$
  - **Resultado:** $1000000000000001_2$

---

## 13. Clasificación de polinomios (Ejercicios 103 a 108)

Clasificación por grado (mayor exponente) y por número de términos:
- **103) $5n + 5$**
  - Grado 1 (Lineal), 2 términos (Binomio).
  - **Nombre:** Binomio lineal.

- **104) $-10p^3 - 6 + 9p^2 - 4p^5 - 2p^8$**
  - Grado 8 (Octavo grado), 5 términos (Polinomio de 5 términos).
  - **Nombre:** Polinomio de octavo grado de 5 términos.

- **105) $7x^8$**
  - Grado 8 (Octavo grado), 1 término (Monomio).
  - **Nombre:** Monomio de octavo grado.

- **106) $-2n + n^4 + 10n^6$**
  - Grado 6 (Sexto grado), 3 términos (Trinomio).
  - **Nombre:** Trinomio de sexto grado.

- **107) $5$**
  - Grado 0 (Constante), 1 término (Monomio).
  - **Nombre:** Monomio constante.

- **108) $5v^7$**
  - Grado 7 (Séptimo grado), 1 término (Monomio).
  - **Nombre:** Monomio de séptimo grado.

---

## 14. Problemas de aplicación (Ejercicios 109 a 114)

### Ejercicio 109: Trabajo compartido (Amy y Jill)
- **Planteamiento:**
  - Tasa de Amy: $R_A = \frac{1}{8}$ obras/hora.
  - Tasa combinada: $R_{A+J} = \frac{1}{3.08}$ obras/hora.
  - Tasa de Jill: $R_J = \frac{1}{t_J}$.
  - Ecuación: $\frac{1}{8} + \frac{1}{t_J} = \frac{1}{3.08} \implies \frac{1}{t_J} = \frac{1}{3.08} - \frac{1}{8}$.
- **Cálculo:**
  $$\frac{1}{t_J} \approx 0.324675 - 0.125 = 0.199675$$
  $$t_J = \frac{1}{0.199675} \approx 5.008 \approx 5 \text{ horas}$$
  *(En forma fraccionaria exacta: $3.08 = \frac{77}{25} \implies \frac{25}{77} - \frac{1}{8} = \frac{200 - 77}{616} = \frac{123}{616} \implies t_J = \frac{616}{123} \approx 5.01 \text{ horas}$)*
- **Resultado:** A Jill le tomaría aproximadamente **$5$ horas** (exactamente $\frac{616}{123} \text{ h}$).

---

### Ejercicio 110: Trabajo compartido (Jaidee y Ted)
- **Planteamiento:**
  - Tasa de Jaidee: $\frac{1}{5}$ hoyos/hora.
  - Tasa de Ted: $\frac{1}{7}$ hoyos/hora.
  - Tasa combinada: $\frac{1}{5} + \frac{1}{7} = \frac{7 + 5}{35} = \frac{12}{35}$ hoyos/hora.
- **Cálculo:**
  $$t = \frac{35}{12} \text{ horas} = 2.9167 \text{ horas} \approx 2 \text{ horas y } 55 \text{ minutos}$$
- **Resultado:** **$\frac{35}{12}$ horas** ($\approx 2.92 \text{ h}$).

---

### Ejercicio 111: Movimiento y persecución (Avión de carga y Fuerza Aérea)
- **Planteamiento:**
  - El avión de carga sale y vuela durante $t_c = 4 + 6 = 10$ horas a velocidad $v$.
  - El avión militar vuela a $310\text{ km/h}$ durante $6$ horas.
  - En el punto de alcance, ambas distancias son iguales:
    $$d = v \times 10 = 310 \times 6$$
- **Cálculo:**
  $$10v = 1860 \implies v = \frac{1860}{10} = 186\text{ km/h}$$
- **Resultado:** La velocidad promedio fue de **$186\text{ km/h}$**.

---

### Ejercicio 112: Movimiento de ida y vuelta (Tren de carga)
- **Planteamiento:**
  - La distancia de ida es idéntica a la distancia de regreso: $d = v_{\text{ida}} \times t_{\text{ida}} = v_{\text{regreso}} \times t_{\text{regreso}}$.
  - $v_{\text{ida}} = 35\text{ km/h}$
  - $v_{\text{regreso}} = 49\text{ km/h}$
  - $t_{\text{regreso}} = 10\text{ horas}$
- **Cálculo:**
  $$35 \times t_{\text{ida}} = 49 \times 10 = 490$$
  $$t_{\text{ida}} = \frac{490}{35} = 14\text{ horas}$$
- **Resultado:** El viaje de ida tomó **$14\text{ horas}$**.

---

### Ejercicio 113: Mezcla de tierra y arena
- **Planteamiento:**
  - Lote 1: $1\text{ yd}^3$ al $30\%$ de arena $\implies 1 \times 0.30 = 0.30\text{ yd}^3$ de arena.
  - Lote 2: $4\text{ yd}^3$ al $20\%$ de arena $\implies 4 \times 0.20 = 0.80\text{ yd}^3$ de arena.
  - Volumen total: $1 + 4 = 5\text{ yd}^3$.
  - Arena total: $0.30 + 0.80 = 1.10\text{ yd}^3$.
- **Cálculo:**
  $$\% \text{ de arena} = \frac{1.10}{5} \times 100\% = 0.22 \times 100\% = 22\%$$
- **Resultado:** El contenido de arena es del **$22\%$**.

---

### Ejercicio 114: Mezcla de ponche de frutas
- **Planteamiento:**
  - Ponche A: $7\text{ L}$ al $11\% \implies 7 \times 0.11 = 0.77\text{ L}$ de jugo puro.
  - Ponche B: $6\text{ L}$ al $24\% \implies 6 \times 0.24 = 1.44\text{ L}$ de jugo puro.
  - Volumen total: $7 + 6 = 13\text{ L}$.
  - Jugo puro total: $0.77 + 1.44 = 2.21\text{ L}$.
- **Cálculo:**
  $$\% \text{ de jugo} = \frac{2.21}{13} \times 100\% = 0.17 \times 100\% = 17\%$$
- **Resultado:** La mezcla contiene **$17\%$** de jugo de fruta.
