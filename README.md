# Informe Laboratorio 5

# 1. OBJETIVOS

**General**

-Analizar los circuitos mediante el uso del teorema de THÉVENIN  para poder simplificar circuitos complejos 



**Específicos**

-Emplear los conocimientos anteriormente vistos para el analisis de los circuitos

-Interpretar los datos y diagramas presentesn en el circuito

-Construir el circuito en tinkercad para mejorar nuestro analisis 



# 2. MARCO TEÓRICO

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBN/Diagrama%20en%20blanco%20(8).png)


# 3. EXPLICACIÓN DEL PROCEDIMIENTO

**MATERIALES**

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/1.png)

**Circuito analizado**

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/2.png)

**PROCEDIMIENTO**

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/3.png)

**Calcular el voltaje y la corriente en R5, para ello se utiliza el teorema de superposición**

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/4.png)

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/5.png)

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/6.png)

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/7.png)

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/8.png)

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/9.png)

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/10.png)

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/11.png)

**VOLTAJE DE THÉVENIN**

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/12.png)

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/13.png)

Quitar la resistencia R5 y utilizar el teorema de superposición para calcular el voltaje en el circuito abierto:

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/14.png)

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/15.png)

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/16.png)

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/17.png)

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/18.png)

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/19.png)

**RESISTENCIA DE THÉVENIN** 

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/20.png)

**DIAGRAMA DEL CIRCUITO EQUIVALENTE DE THÉVENIN**

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/21.png)

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/22.png)

**SIMULACIÓN EN TINKERCAD**

- Mida el voltaje y la corriente en el resistor R5, anote los resultados en la tabla 5.2.

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/d1.png)

- Desconecte el resistor R5 y mida el voltaje en el circuito abierto. Anote el valor medido en la tabla 5.1.

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/d2.png)

- Anule el efecto de las fuentes de alimentación. Desconecte R5 y desde el circuito abierto resultante mida la resistencia equivalente. Anote el valor medido en la tabla 5.1.

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBV/d3.png)

- Implemente el circuito equivalente de Thévenin, agregue el resistor R5 y mida la corriente y el voltaje en el mismo, anote los resultados en la tabla 5.2.

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMG%20TH/S_1.JPG)

**RECOPILACIÓN DE DATOS**

**Tabla 5.1. Valores del Circuito Equivalente de Thévenin**

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMG%20TH/T_1.JPG)

**Tabla 5.2. Comprobación del Teorema de Thévenin.**

![](https://github.com/bavargas5/Laboratorio5/blob/main/IMG%20TH/T_2.JPG)

# 4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR


Los porcentajes de error son muy bajos ya que los simuladores trabajan con sistemas ideales


![](https://github.com/bavargas5/Laboratorio5/blob/main/IMGBN/Captura.PNG)

**Valores del Circuito Equivalente de Thévenin**

| | CALCULADO | MEDIDO | % ERROR|
| ------------- | ------------- | ------------- | ------------- |
| V_TH | 5.06v | 5.06 | 0 % |
| R_TH | 289.86 ohm | 289 ohm | 0.29 % |


**Comprobación del Teorema de Thévenin.**


|CIRCUITO ORIGINAL | CALCULADO | MEDIDO | % ERROR|
| ------------- | ------------- | ------------- | ------------- |
| V | 3.88v | 3.89 V| 0.25 % |
| I | 3.88 mA | 3.89 mA | 0.25 % |


|CIRCUITO EQUIVALENTE TH | CALCULADO | MEDIDO | % ERROR|
| ------------- | ------------- | ------------- | ------------- |
| V | 3.92v | 3.89 V| 0.76 % |
| I | 3.92 mA | 3.89 mA | 0.76 % |


# 5. VIDEO



# 6. CONCLUSIONES

- Se visualizo que mediante el uso de el teorema de  THÉVENIN el circuito que se encontraba en la guía del laboratorio que se observaba complejo se logró simplificar y así se convirtió en un circuito equivalente mucho más simple

- Tal y como hemos podido comprobar al utilizar el teorema de superposición que es un teorema anteriormente aprendido entre otras cosas, se pudo comparar con el circuito simplificado que se obtuvo por el teorema de THÉVENIN


- Es importante aclarar que  al usar el teorema de  THÉVENIN  nos facilita el calculo de voltajes y corrientes en un circuito

# 7. BIBLIOGRAFÍA

-C. (2021, 17 diciembre). Teorema de Thevenin – Análisis de circuitos eléctricos. dademuchconnection. https://dademuch.com/2019/11/10/teorema-de-thevenin-analisis-de-circuitos-electricos/

-Áreatecnología. (s. f.). Teorema de Thevenin y de Norton Para Resolver Circuitos Aprende Facil. https://www.areatecnologia.com/electricidad/teorema-de-thevenin-y-norton.html


