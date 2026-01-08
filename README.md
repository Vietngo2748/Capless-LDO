# Capless-LDO

This project discusses the design of capless LDO with compensation technique.

### Design Parameters and Specifications:
| **Parameter**                       | **Specification** |
| ----------------------------------- | ----------------- |
| Supply Voltage (VDD)                | 1.2 V             |
| Output Voltage                      | 0.75 V            |
| Dropout Voltage                     | 0.2 V             |
| Output Current                      | 10 µA – 1 mA      |
| Power Supply Rejection Ratio (PSRR) | > 50 dB           |
| Phase Margin                        | > 60°             |
| Load Capacitance                    | 1 pF              |

### PVT Conditions:
| **Condition**  | **Range**        |
| -------------- | ---------------- |
| Process        | 65 nm CMOS       |
| Supply Voltage | 1.08 – 1.32 V    |
| Temperature    | −40 °C to 125 °C |

*****************
### Implementation:
<img width="822" height="605" alt="image" src="https://github.com/user-attachments/assets/6ecd6dce-e6ae-4c18-bb74-d8cc692506c1" />

### Testbench Schematics:
### DC and AC Analysis
<img width="1072" height="701" alt="image" src="https://github.com/user-attachments/assets/94104080-40fa-4c70-aeb0-fe2bc3a6d49b" />

### Load regulation and Transient
<img width="1000" height="696" alt="image" src="https://github.com/user-attachments/assets/9a6f112a-e3b8-4a1c-8a94-80efac75257a" />

### PSRR:
<img width="1500" height="528" alt="image" src="https://github.com/user-attachments/assets/1bf7da39-3771-45b1-b4f6-16ced87adc41" />

### Load Transient Response:
<img width="1500" height="533" alt="image" src="https://github.com/user-attachments/assets/cbb9ab45-cafc-4c34-9618-54b21b68fa50" />

### Monte Carlo:
<img width="1500" height="528" alt="image" src="https://github.com/user-attachments/assets/69bebe60-a28b-4163-8d5a-e0a0db6b4b83" />

*****************
### Key References:

[1] Low Dropout Regulators, Pavan Kumar Hanumolu University of Illinois, Urbana-Champaign, P. Hanumolu CICC 2015.

[2] Chen, K. (2016). Power Management techniques for integrated circuit design. https://doi.org/10.1002/9781118896846

[3] Gabriel Alfonso Rincon-Mora B.S. M.S. Ph.D. (1970, January 1). Analog IC design with low-dropout regulators. McGraw-Hill Education - Access Engineering. https://www.accessengineeringlibrary.com/content/book/9780071826631?implicit-login=true.

[4] Y. Zhao, H. Quan, T. Zhang and J. Xiang, "A High-Performance LDO with Temperature-Coefficient Calibration," ITAIC, 2020.

[5] Robert J. Milliken; Jose Silva-Martinez; Edgar Sanchez-Sinencio, "Full On-Chip CMOS Low-Dropout Voltage Regulator," IEEE Transactions on Circuits and Systems I: Regular Papers, vol. 54, no. 9, pp. 1879 - 1890, 2007.

*****************


*****************

