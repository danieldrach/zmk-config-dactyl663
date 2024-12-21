# Left keyboard side

I will represent my physical rows the following way:
* **Rows**: From the top of the keyboard down, meaning `R1` will be the topmost row and `R6` the lower one (thumb cluster).
* **Columns**: From left to right, with the keycaps facing up, meaning the `<shift>`  key will be in `C0` and the `B` key will be in C6. 

Both halves are wired in the exact same way, suitable inversions are made in the `.dtsi` files and in the mapping.
## nice!nano_v2 pinout

| C                       | Left Side (KB-COLS) | Right Side (KB-ROWs) | R                       |
|-------------------------|---------------------|----------------------|-------------------------|
| -                       | GND                 | BATTERY+             | -                       |
| -                       | D1 (P0.06)          | BATTERY+             | -                       |
| -                       | D0 (P0.08)          | GND                  | -                       |
| -                       | GND                 | RESET                | -                       |
| -                       | GND                 | 3.3V                 | -                       |
| -                       | D2 (P0.17)          | D21 (P0.31)          | -                       |
| -                       | D3 (P0.20)          | D20 (P0.29)          | -                       |
| $${\color{green}C1}$$   | D4 (P0.22)          | D19 (P0.02)          | $${\color{blue}R1}$$    |
| $${\color{blue}C2}$$    | D5 (P0.24)          | D18 (P1.15)          | $${\color{green}R2}$$   |
| $${\color{violet}C3}$$  | D6 (P1.00)          | D15 (P1.13)          | $${\color{yellow}R3}$$  |
| $${\color{gray}C4}$$    | D7 (P0.11)          | D14 (P1.11)          | $${\color{orange}R4}$$  |
| $${\color{white}C5}$$   | D8 (P1.04)          | D16 (P0.10)          | $${\color{red}R5}$$     |
| $${\color{black}C6}$$   | D9 (P1.06)          | D10 (P0.09)          | $${\color{brown}R6}$$   |
