# INFORME TAREA 9

**UNIVERSIDAD DE LAS FUERZAS ARMADAS**

**DEPARTAMENTO DE ELECTRICA Y ELECTRÓNICA**

**FUNDAMENTOS DE CIRCUITOS ELECTRICOS**

**Nombres:** Martin Coronel, Jefferson Chicaiza, Tito Obando 

**Carrera:** Electrónica y Automatización 

**NRC:** 10133

**1. OBJETIVOS**

*1.1 Objetivo General:* 

*1.2 Objetivos Especificos*

**2.MARCO TEORICO(RESUMEN)**

**3. EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS**

***CAPITULO N° 17***

Impedancia de circuitos RLC en serie 

1. Cierto circuito RLC en serie tiene los siguientes valores: R = 10 ohm, C = 0.047 mF, y L = 5 mH. Determine la impedancia en forma polar. ¿Cuál es la reactancia neta? La frecuencia de la fuente es de 5 kHz.

f = 5kHz
R = 10ohm
C = 0.047mF
L = 5mH

Z = raiz(R^2 + (Xtot)^2 ∠ (+/-) tan^-1 (Xtot/R)

Xc = 1/2pifC

XL = 2pifL

Xc = 1/2pifC = 1/2pi(5000)(0.047*10^-6) = 667.25ohm

XL = 2pi(5000)(0.005) = 157.08ohm

Xtot = |XL – Xc| = |157.08 – 667.25| = 520.17 ohm

Z = raiz(10^2 + (520.17)^2 ∠  tan^-1 (520.17/10) = 520.3 ∠ -88.9 capacitivo


3. Si en la figura la frecuencia del voltaje de fuente se duplica a partir del valor que producen las reactancias indicadas, ¿cómo cambia la magnitud de la impedancia?

![image](https://user-images.githubusercontent.com/94182617/155566420-04991891-5907-4175-a944-4b40b49dad67.png)

Xtot = |XL – Xc| = |80 – 35| = 45

Z = raiz(47^2 + (45)^2 ∠  tan^-1 (45/47) = 65.07 ∠ 43.75 

Se duplica:

XL = 80 * 2 = 160ohm

Xc = 35 /2 = 17.5 ohm

Xtot = |160 – 17.5 | = 142.5ohm

Z = raiz(47^2 + (142.5)^2 ∠  tan^-1 (142.5/47) = 150 ∠ 41.74

La impedancia se incrementa a 150 ohm

Análisis de circuitos RLC en serie

5. Para el circuito de la figura 17-59, determine Itot, VR, VL y VC en forma polar.

![image](https://user-images.githubusercontent.com/94182617/155566554-d1496939-16c8-4871-bfb0-b04ac62f38f1.png)

Z = R + jXL - jXC = 47 + j80 – j35 = 47 + j45 

Z = raiz(47^2 + (45)^2 ∠ tan^-1 (45/47) = 65.07 ∠ 43.75

I = Vs/Z = (4 ∠ 0)/( 65.07 ∠ 43.75) = 0.0615 ∠ -43.75 = 61.5 ∠ -43.75 mA

Vr = I * R = (0.0615 ∠ -43.75) * (47 ∠ 0) = 2.89 ∠ -43.75 V

VL = I * XL = (0.0615 ∠ -43.75) * (80 ∠ 90) = 4.92 ∠ 46.25 V

Vc = I * Xc = (0.0615 ∠ -43.75) * (35 ∠ -90) = 2.15∠ -134 V

7. Analice el circuito de la figura para determinar lo siguiente (f = 25 kHz): 

(a)Itot	 (b)Preal	 (c)Pr	 (d) Pa

![image](https://user-images.githubusercontent.com/94182617/155566650-3baa75bb-7195-4aea-b696-405e5bad609a.png)

Rtot = 1/(1/220 + 1/390) = 140.65 ohm

Ltot = 0.5 + 1 = 1.5mH = 0.0015 H

Ctot = 1*10^-8 + 1.8*10^-9 = 11.8*10^-9 F

Xc = 1/2pi(25*10^3)(11.8*10^-9) = 539.5 ohm

XL = 2piL(25*10^3) (0.0015) = 235.62 ohm

Xtot = |235.62 – 539.62| = 304

Z = raiz(140.65^2 + (304)^2 ∠ -tan^-1 (304/140.65) = 334.96 ∠ -65.17

(a) Itot = Vs/Z = (12 ∠ 0)/(334.96 ∠ -65.17) = 35.8∠65.17 mA

(b) Pr = I^2 * R = 35.8^2 * 140.65 = 181 mW

(c) Pr = I^2 * Xc = 35.8^2 * 539.5 = 390 mVAR

(d) Pa = I^2 * Z = 35.8^2 * 334.96 = 430 mVA


Resonancia en serie

9. Para el circuito de la figura, ¿cuál es el voltaje a través de R en condición de resonancia?

![image](https://user-images.githubusercontent.com/94182617/155566751-a1e44117-f49b-44d2-8088-0b7da24ba91a.png)

Al estar en frecuencia resonante Xc y XL se anulan por lo que la corriente será solo definida por R y Vs, entonces R tendrá el mismo voltaje que la fuente de 12V.

11. Cierto circuito resonante dispuesto en serie tiene una corriente mínima de 50 mA y un VL de 100 V. El voltaje aplicado es de 10 V. ¿Cuál es el valor de Z? ¿Cuáles los valores de XL y XC?

Xc = XL = 100V/0.05A = 2kohm

R = V/I = 10/0.05 = 200ohm

Z = R + jXL – jXc = 200ohm + 0 = 200ohm

13. Para la figura, ¿cuál es el valor de la corriente en los puntos de potencia media?

![image](https://user-images.githubusercontent.com/94182617/155566930-c6f7f889-2e02-4e6f-87d3-4eea26472bc3.png)

XL = Xc 

I = V/R = 7.07/10 = 0.707A

En los puntos de potencia media la corriente:

I = 0.707 * 0.707 = 500mA

15. Diseñe un circuito en el cual las siguientes frecuencias resonantes en serie se puedan seleccionar con un conmutador: 

(a) 500 kHz 	(b) 1000 kHz 	(c) 1500 kHz 	(d) 2000 kHz

![image](https://user-images.githubusercontent.com/94182617/155567001-e4ec7cd5-fd5d-4c0f-b297-34442c16d30c.png)

Impedancia de circuitos RLC en paralelo

17. ¿Es capacitivo o inductivo el circuito de la figura? Explique su respuesta.

![image](https://user-images.githubusercontent.com/94182617/155567065-eb7177ae-a7c9-4676-bcdc-7b0fe60d67d0.png)

Xc = 1/2pifC = 1/2pi(12*10^3)(0.022*10^-6) = 602.86

XL = 2pifL = 2pi(12*10^3)(15*10^-3) = 1130.97

1/Z = 1/R∠0° + 1/XL∠90° + 1/XC∠ -90° = 1/100∠0° + 1/1130.97∠90° + 1/602.86∠ -90°

1/Z = 0.01 ∠ 0 S + 0.00088 ∠ 90 S + 0.0016 ∠ -90

Z = 1/(0.01 -j0.00088 + j0.0016) = 1/(0.01 + j0.00072)

Z = 1/(raíz(0.01^2 + 0.00072^2) ∠ tan^-1(0.00072/0.01) = 1/(0.01 ∠ 4.12)

Z = 100 ∠ -4.12 indica un circuito levemente capacitivo

Análisis de circuitos RLC en paralelo

19. Para el circuito de la figura, determine todas las corrientes y los voltajes en forma polar.

![image](https://user-images.githubusercontent.com/94182617/155567161-ff12d52d-aaa3-4436-bd1c-8056d96f5709.png)

Xc = 1/2pifC = 1/2pi(12*10^3)(0.022*10^-6) = 602.86

XL = 2pifL = 2pi(12*10^3)(15*10^-3) = 1130.97

IR = Vs/R = (5 ∠ 0)/(100 ∠ 0) = 50 ∠ 0 mA

Ic = Vs/Xc = (5 ∠ 0)/(602.86 ∠ -90) = 8.3 ∠ 90 mA

IL = Vs/XL = (5 ∠ 0)/(1130.97 ∠ 90) = 4.42 ∠ -90 mA

Itot = IR + Ic + IL = (50 ∠ 0) + (8.3 ∠ 90) + (4.42 ∠ -90) = 50 +j8.3 – j4.42 = 50mA + j3.87mA

Itot = raiz(IR^2 + (Ic - IL)^2) ∠ tan^-1(ICL/IR) = raiz(50^2 + 3.87 ^2) ∠ tan^-1(3.87/50) = 

Itot = 50.15 ∠ 4.43 mA

VR = VL = VC = 5 ∠ 0° V

21. Cambie la frecuencia a 100 kHz en la figura y repita el problema 19.

![image](https://user-images.githubusercontent.com/94182617/155567247-9cb2cec5-f849-45a1-bd4c-e6d3abc69003.png)
Tito (12 ejercicios)

25.Determine Preal, Pr y Pa en el circuito de la figura 17-64 en condición de resonancia.

![image](https://user-images.githubusercontent.com/94098157/155448806-92b89d7e-01d3-410a-a291-297d78fb3dfa.png)

![image](https://user-images.githubusercontent.com/94098157/155531054-583779aa-e3d0-4ead-bd1f-0bcf2dc0e15a.png)
![image](https://user-images.githubusercontent.com/94098157/155531149-8802d9bc-ad5c-4009-bbf0-403fbdcf6782.png)
![image](https://user-images.githubusercontent.com/94098157/155531371-a3ac190e-ca59-4324-bc2f-5ec30e29e62d.png)

27.Para cada circuito de la figura 17-65, determine el ángulo de fase entre el voltaje de fuente y la corriente total.

![image](https://user-images.githubusercontent.com/94098157/155448987-23c82e25-8a93-464c-bd19-90f1927e3566.png)

![image](https://user-images.githubusercontent.com/94098157/155542096-37665c25-78be-4210-8c4f-b22a9b888176.png)

29.Convierta el circuito de la figura 17-66 a una forma equivalente dispuesta en serie.

![image](https://user-images.githubusercontent.com/94098157/155449056-332a8ed0-52ff-4dd7-a07d-6c198bacdc57.png)

![image](https://user-images.githubusercontent.com/94098157/155457969-656c3c54-a009-4f18-8914-e58baede5ff9.png)

31.En la figura 17-67, ¿cuál es el ángulo de fase entre I2 y el voltaje de fuente?

![image](https://user-images.githubusercontent.com/94098157/155449145-70353ae2-866d-42da-9e50-98a5dd924acc.png)

![image](https://user-images.githubusercontent.com/94098157/155459213-dfef4e29-1074-4b76-b4f4-a62c1ee18594.png)

33.Determine la corriente a través de cada componente mostrado en la figura 17-68. Encuentre el voltaje entre las terminales de cada  componente.

![image](https://user-images.githubusercontent.com/94098157/155449193-73730000-3f55-43e9-ae5d-d526c4a20cb3.png)


35.Si el valor de C es de 0.22 mF, ¿cuál es la corriente a través de un resistor de 100 Ω conectado de a a b en la figura 17-69?

![image](https://user-images.githubusercontent.com/94098157/155449283-5c36fbb1-9a9d-4142-830b-de61f22a6d47.png)

37.Determine las frecuencias resonantes y el voltaje de salida en cada frecuencia mostrada en la figura 17-70.

![image](https://user-images.githubusercontent.com/94098157/155449315-87a4fb6c-8a72-476d-815f-8d1228b21f30.png)

![image](https://user-images.githubusercontent.com/94098157/155536712-8d3c2f91-45f4-493e-b1e3-454f0ed4797c.png)
![image](https://user-images.githubusercontent.com/94098157/155537005-fedd51fd-b285-4df6-9fa3-2436cc35695e.png)
![image](https://user-images.githubusercontent.com/94098157/155537051-29c5a5e8-5acb-47e0-844c-813e0acc2235.png)

39.En condición de resonancia, XL 2kΩ  y RW  25Ω en un circuito RLC en paralelo. La frecuencia resonante es de 5 kHz. Determine el ancho de banda.

![image](https://user-images.githubusercontent.com/94098157/155462305-88878478-e8cb-430a-a5b1-9cd0a84b189d.png)

41.En cierto circuito RLC, la potencia en condición de resonancia es de 2.75 W. ¿Cuál es la potencia a la frecuencia crítica baja?

![image](https://user-images.githubusercontent.com/94098157/155463207-b6d2fa3f-971e-4508-83ac-b2536e6bfe73.png)

43.Cierto circuito resonante en paralelo tiene un factor Q de 50 y un AB de 400 Hz. Si Q se duplica, ¿cuál es el ancho de banda a la misma fr?

AB= 200 Hz

***CAPITULO N° 18***

1.En cierto filtro pasabajas, Xc= 500Ω y R = 2.2kΩ. ¿Cuál es el voltaje de salida (Vsal) cuando la entrada es de 10 V rms?

![image](https://user-images.githubusercontent.com/94098157/155450416-2f1bc453-99d6-4ee5-ab47-ec1b7748a2b6.png)

3.Determine el voltaje de salida (Vsal) de cada filtro mostrado en la figura 18-38 a la frecuencia especificada cuando Vent = 10 V.

![image](https://user-images.githubusercontent.com/94098157/155450824-85f514c5-6a71-4f33-a165-0c0bb05a9926.png)

![image](https://user-images.githubusercontent.com/94098157/155452247-3a34c76d-9bf2-49a2-a481-fe1aab1feb4b.png)

![image](https://user-images.githubusercontent.com/94098157/155452282-aab21dab-3cbf-4855-adb1-a97fe8926e48.png)

Impedancia de circuitos RLC en serie 

1. Cierto circuito RLC en serie tiene los siguientes valores: R = 10 ohm, C = 0.047 mF, y L = 5 mH. Determine la impedancia en forma polar. ¿Cuál es la reactancia neta? La frecuencia de la fuente es de 5 kHz.

f = 5kHz
R = 10ohm
C = 0.047mF
L = 5mH

Z = raiz(R^2 + (Xtot)^2 ∠ (+/-) tan^-1 (Xtot/R)

Xc = 1/2pifC

XL = 2pifL

Xc = 1/2pifC = 1/2pi(5000)(0.047*10^-6) = 667.25ohm

XL = 2pi(5000)(0.005) = 157.08ohm

Xtot = |XL – Xc| = |157.08 – 667.25| = 520.17 ohm

Z = raiz(10^2 + (520.17)^2 ∠  tan^-1 (520.17/10) = 520.3 ∠ -88.9 capacitivo


3. Si en la figura la frecuencia del voltaje de fuente se duplica a partir del valor que producen las reactancias indicadas, ¿cómo cambia la magnitud de la impedancia?

![image](https://user-images.githubusercontent.com/94182617/155566420-04991891-5907-4175-a944-4b40b49dad67.png)

Xtot = |XL – Xc| = |80 – 35| = 45

Z = raiz(47^2 + (45)^2 ∠  tan^-1 (45/47) = 65.07 ∠ 43.75 

Se duplica:

XL = 80 * 2 = 160ohm

Xc = 35 /2 = 17.5 ohm

Xtot = |160 – 17.5 | = 142.5ohm

Z = raiz(47^2 + (142.5)^2 ∠  tan^-1 (142.5/47) = 150 ∠ 41.74

La impedancia se incrementa a 150 ohm

Análisis de circuitos RLC en serie

5. Para el circuito de la figura 17-59, determine Itot, VR, VL y VC en forma polar.

![image](https://user-images.githubusercontent.com/94182617/155566554-d1496939-16c8-4871-bfb0-b04ac62f38f1.png)

Z = R + jXL - jXC = 47 + j80 – j35 = 47 + j45 

Z = raiz(47^2 + (45)^2 ∠ tan^-1 (45/47) = 65.07 ∠ 43.75

I = Vs/Z = (4 ∠ 0)/( 65.07 ∠ 43.75) = 0.0615 ∠ -43.75 = 61.5 ∠ -43.75 mA

Vr = I * R = (0.0615 ∠ -43.75) * (47 ∠ 0) = 2.89 ∠ -43.75 V

VL = I * XL = (0.0615 ∠ -43.75) * (80 ∠ 90) = 4.92 ∠ 46.25 V

Vc = I * Xc = (0.0615 ∠ -43.75) * (35 ∠ -90) = 2.15∠ -134 V

7. Analice el circuito de la figura para determinar lo siguiente (f = 25 kHz): 

(a)Itot	 (b)Preal	 (c)Pr	 (d) Pa

![image](https://user-images.githubusercontent.com/94182617/155566650-3baa75bb-7195-4aea-b696-405e5bad609a.png)

Rtot = 1/(1/220 + 1/390) = 140.65 ohm

Ltot = 0.5 + 1 = 1.5mH = 0.0015 H

Ctot = 1*10^-8 + 1.8*10^-9 = 11.8*10^-9 F

Xc = 1/2pi(25*10^3)(11.8*10^-9) = 539.5 ohm

XL = 2piL(25*10^3) (0.0015) = 235.62 ohm

Xtot = |235.62 – 539.62| = 304

Z = raiz(140.65^2 + (304)^2 ∠ -tan^-1 (304/140.65) = 334.96 ∠ -65.17

(a) Itot = Vs/Z = (12 ∠ 0)/(334.96 ∠ -65.17) = 35.8∠65.17 mA

(b) Pr = I^2 * R = 35.8^2 * 140.65 = 181 mW

(c) Pr = I^2 * Xc = 35.8^2 * 539.5 = 390 mVAR

(d) Pa = I^2 * Z = 35.8^2 * 334.96 = 430 mVA


Resonancia en serie

9. Para el circuito de la figura, ¿cuál es el voltaje a través de R en condición de resonancia?

![image](https://user-images.githubusercontent.com/94182617/155566751-a1e44117-f49b-44d2-8088-0b7da24ba91a.png)

Al estar en frecuencia resonante Xc y XL se anulan por lo que la corriente será solo definida por R y Vs, entonces R tendrá el mismo voltaje que la fuente de 12V.

11. Cierto circuito resonante dispuesto en serie tiene una corriente mínima de 50 mA y un VL de 100 V. El voltaje aplicado es de 10 V. ¿Cuál es el valor de Z? ¿Cuáles los valores de XL y XC?

Xc = XL = 100V/0.05A = 2kohm

R = V/I = 10/0.05 = 200ohm

Z = R + jXL – jXc = 200ohm + 0 = 200ohm

13. Para la figura, ¿cuál es el valor de la corriente en los puntos de potencia media?

![image](https://user-images.githubusercontent.com/94182617/155566930-c6f7f889-2e02-4e6f-87d3-4eea26472bc3.png)

XL = Xc 

I = V/R = 7.07/10 = 0.707A

En los puntos de potencia media la corriente:

I = 0.707 * 0.707 = 500mA

15. Diseñe un circuito en el cual las siguientes frecuencias resonantes en serie se puedan seleccionar con un conmutador: 

(a) 500 kHz 	(b) 1000 kHz 	(c) 1500 kHz 	(d) 2000 kHz

![image](https://user-images.githubusercontent.com/94182617/155567001-e4ec7cd5-fd5d-4c0f-b297-34442c16d30c.png)

Impedancia de circuitos RLC en paralelo

17. ¿Es capacitivo o inductivo el circuito de la figura? Explique su respuesta.

![image](https://user-images.githubusercontent.com/94182617/155567065-eb7177ae-a7c9-4676-bcdc-7b0fe60d67d0.png)

Xc = 1/2pifC = 1/2pi(12*10^3)(0.022*10^-6) = 602.86

XL = 2pifL = 2pi(12*10^3)(15*10^-3) = 1130.97

1/Z = 1/R∠0° + 1/XL∠90° + 1/XC∠ -90° = 1/100∠0° + 1/1130.97∠90° + 1/602.86∠ -90°

1/Z = 0.01 ∠ 0 S + 0.00088 ∠ 90 S + 0.0016 ∠ -90

Z = 1/(0.01 -j0.00088 + j0.0016) = 1/(0.01 + j0.00072)

Z = 1/(raíz(0.01^2 + 0.00072^2) ∠ tan^-1(0.00072/0.01) = 1/(0.01 ∠ 4.12)

Z = 100 ∠ -4.12 indica un circuito levemente capacitivo

Análisis de circuitos RLC en paralelo

19. Para el circuito de la figura, determine todas las corrientes y los voltajes en forma polar.

![image](https://user-images.githubusercontent.com/94182617/155567161-ff12d52d-aaa3-4436-bd1c-8056d96f5709.png)

Xc = 1/2pifC = 1/2pi(12*10^3)(0.022*10^-6) = 602.86

XL = 2pifL = 2pi(12*10^3)(15*10^-3) = 1130.97

IR = Vs/R = (5 ∠ 0)/(100 ∠ 0) = 50 ∠ 0 mA

Ic = Vs/Xc = (5 ∠ 0)/(602.86 ∠ -90) = 8.3 ∠ 90 mA

IL = Vs/XL = (5 ∠ 0)/(1130.97 ∠ 90) = 4.42 ∠ -90 mA

Itot = IR + Ic + IL = (50 ∠ 0) + (8.3 ∠ 90) + (4.42 ∠ -90) = 50 +j8.3 – j4.42 = 50mA + j3.87mA

Itot = raiz(IR^2 + (Ic - IL)^2) ∠ tan^-1(ICL/IR) = raiz(50^2 + 3.87 ^2) ∠ tan^-1(3.87/50) = 

Itot = 50.15 ∠ 4.43 mA

VR = VL = VC = 5 ∠ 0° V

21. Cambie la frecuencia a 100 kHz en la figura y repita el problema 19.

![image](https://user-images.githubusercontent.com/94182617/155567247-9cb2cec5-f849-45a1-bd4c-e6d3abc69003.png)

**3.VIDEO**

**4.CONCLUSIONES**

**5.BIBLIOGRAFÍA**

Floyd, T. (2007). *Principios de circuitos electricos* (Ed. 8va). Pearson EDUCATION.
