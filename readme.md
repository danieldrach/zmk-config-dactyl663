# Left keyboard side

I will represent my physical rows the following way:
* **Rows**: From the top of the keyboard down, meaning `R1` will be the topmost row and `R6` the lower one (thumb cluster).
* **Columns**: From left to right, with the keycaps facing up, meaning the `<shift>`  key will be in `C0` and the `B` key will be in C6. 

## nice!nano_v2 pinout

| C                                    | Left Side (KB-COLS) | Right Side (KB-ROWs) | R                                         |
|--------------------------------------|---------------------|----------------------|-------------------------------------------|
| -                                    | GND                 | BATTERY+             | -                                         |
| -                                    | D1 (P0.06)          | BATTERY+             | -                                         |
| -                                    | D0 (P0.08)          | GND                  | -                                         |
| -                                    | GND                 | RESET                | -                                         |
| -                                    | GND                 | 3.3V                 | -                                         |
| -                                    | D2 (P0.17)          | D21 (P0.31)          | -                                         |
| -                                    | D3 (P0.20)          | D20 (P0.29)          | -                                         |
| <span style="color:green">C1</span>  | D4 (P0.22)          | D19 (P0.02)          | <span style="color:blue">R1</span>        |
| <span style="color:blue">C2</span>   | D5 (P0.24)          | D18 (P1.15)          | <span style="color:green">R2</span>       |
| <span style="color:indigo">C3</span> | D6 (P1.00)          | D15 (P1.13)          | <span style="color:gold">R3</span>        |
| <span style="color:grey">C4</span>   | D7 (P0.11)          | D14 (P1.11)          | <span style="color:orange">R4</span>      |
| <span style="color:linen">C5</span>  | D8 (P1.04)          | D16 (P0.10)          | <span style="color:Red">R5</span>         |
| <span style="color:black">C6</span>  | D9 (P1.06)          | D10 (P0.09)          | <span style="color:SaddleBrown">R6</span> |


# Right keyboard side
## nice!nano_v2 pinout

| C                                    | Left Side (KB-COLS) | Right Side (KB-ROWs) | R                                         |
|--------------------------------------|---------------------|----------------------|-------------------------------------------|
| -                                    | GND                 | BATTERY+             | -                                         |
| -                                    | D1 (P0.06)          | BATTERY+             | -                                         |
| -                                    | D0 (P0.08)          | GND                  | -                                         |
| -                                    | GND                 | RESET                | -                                         |
| -                                    | GND                 | 3.3V                 | -                                         |
| -                                    | D2 (P0.17)          | D21 (P0.31)          | -                                         |
| -                                    | D3 (P0.20)          | D20 (P0.29)          | -                                         |
| <span style="color:black">C6</span>  | D4 (P0.22)          | D19 (P0.02)          | <span style="color:blue">R1</span>        |
| <span style="color:linen">C5</span>  | D5 (P0.24)          | D18 (P1.15)          | <span style="color:green">R2</span>       |
| <span style="color:grey">C4</span>   | D6 (P1.00)          | D15 (P1.13)          | <span style="color:gold">R3</span>        |
| <span style="color:indigo">C3</span> | D7 (P0.11)          | D14 (P1.11)          | <span style="color:orange">R4</span>      |
| <span style="color:blue">C2</span>   | D8 (P1.04)          | D16 (P0.10)          | <span style="color:Red">R5</span>         |
| <span style="color:green">C1</span>  | D9 (P1.06)          | D10 (P0.09)          | <span style="color:SaddleBrown">R6</span> |
