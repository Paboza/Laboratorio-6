# Laboratorio-6
INTEGRANTES : Boza Paul

NRC:10069

FECHA: 17 de Enero de 2023

Objetivo General.-

Analizar y desarrollar ejercicios de circuitos aplicables a la teoría de máxima transferencia de potencia para descomponer sus propiedades, que permitan calcular mejor y de forma más sencilla variables desconocidas utilizando información teórica.

Objetivo Especifico.-

Describir las características de la teoría de máxima transmisión correspondiente, utilizando para ello la información teórica proporcionada mediante el uso de la página web y los videotutoriales. Analizar y calcular diferentes ejemplos de circuitos previamente aprendidos en clase para tensión y potencia aplicada, que serán validados mediante un simulador virtual mediante ejercicios de laboratorio.

Marco Teorico.-

    - Teorema de transferencia de potencia máxima

El teorema de transferencia de potencia máxima no es tanto un medio de análisis como una ayuda para el diseño del sistema. En pocas palabras, la cantidad máxima de energía se disipará por una resistencia de carga cuando esa resistencia de carga sea igual a la resistencia de Thevenin / Norton de la red que suministra la energía. Si la resistencia de carga es menor o mayor que la resistencia Thevenin / Norton de la red de origen, su potencia disipada será menor que la máxima.

Esto es esencialmente lo que se pretende en el diseño del transmisor de radio, donde la “impedancia” de la antena o la línea de transmisión se corresponde con la potencia final amplificador “impedancia” para obtener la máxima potencia de radiofrecuencia. La impedancia, la oposición general a la corriente CA y CC, es muy similar a la resistencia y debe ser igual entre la fuente y la carga para que se transfiera la mayor cantidad de energía a la carga. Una impedancia de carga demasiado alta dará como resultado una salida de baja potencia. Una impedancia de carga demasiado baja no solo dará como resultado una salida de baja potencia, sino que posiblemente se sobrecalentará el amplificador debido a la potencia disipada en su impedancia interna (Thevenin o Norton). 

     - La potencia máxima no significa la máxima eficiencia
     
El teorema de transferencia de potencia máxima no: La transferencia de potencia máxima no coincide con la eficiencia máxima. La aplicación del teorema de la máxima transferencia de energía a la distribución de energía de CA no dará como resultado una eficiencia máxima o incluso alta. El objetivo de la alta eficiencia es más importante para la distribución de energía de CA, que dicta una impedancia del generador relativamente baja en comparación con la impedancia de carga.

Similar a la distribución de alimentación de CA, los amplificadores de audio de alta fidelidad están diseñados para una impedancia de salida relativamente baja y una impedancia de carga de altavoz relativamente alta. Como relación, “impedancia de salida”: “impedancia de carga” se conoce como factor de amortiguación , típicamente en el rango de 100 a 1000.


La transferencia de potencia máxima no coincide con el objetivo del ruido más bajo. Por ejemplo, el amplificador de radiofrecuencia de bajo nivel entre la antena y un receptor de radio a menudo está diseñado para el menor ruido posible. Esto a menudo requiere un desajuste de la impedancia de entrada del amplificador a la antena en comparación con la dictada por el teorema de transferencia de potencia máxima.

     - REVISIÓN:

El Teorema de transferencia de energía máxima establece que la cantidad máxima de energía se disipará por una resistencia de carga si es igual a la resistencia de Thevenin o Norton de la red que suministra energía.

El teorema de transferencia de potencia máxima no satisface el objetivo de máxima eficiencia.

  - Procedimiento.-

    ![image](https://user-images.githubusercontent.com/116833964/213584623-91f47cfa-907e-4175-8226-48eeb94287fc.png)
    
        - 6.5.2. Mida el voltaje y la corriente para cada valor de RL que se indica en la tabla 6.1.
    
    ![e1adfd693fcd2017f2e3370dbe591bbc-0](https://user-images.githubusercontent.com/116833964/213823841-8fbed583-de4f-4e66-8113-9e5204d84162.jpg)
    ![e1adfd693fcd2017f2e3370dbe591bbc-1](https://user-images.githubusercontent.com/116833964/213823847-91aa9c63-f398-4e77-88bc-465ad1e71cd0.jpg)
    ![e1adfd693fcd2017f2e3370dbe591bbc-2](https://user-images.githubusercontent.com/116833964/213823854-58ed0559-3179-4cea-af9d-6e46764d9cbf.jpg)
![e1adfd693fcd2017f2e3370dbe591bbc-3](https://user-images.githubusercontent.com/116833964/213823996-07881c94-180b-4426-a25f-e2146f6c3be8.jpg)
![e1adfd693fcd2017f2e3370dbe591bbc-4](https://user-images.githubusercontent.com/116833964/213824009-742808c0-faec-4c96-b47c-c2e0cf9f0397.jpg)

        - 6.5.3. Calcule la potencia consumida por RL, para cada valor dado y anote los resultados en la tabla 6.1.
    
![e1adfd693fcd2017f2e3370dbe591bbc-5](https://user-images.githubusercontent.com/116833964/213824689-49e3bd60-760a-49ba-ab9e-bce0cc98ceaa.jpg)
![e1adfd693fcd2017f2e3370dbe591bbc-6](https://user-images.githubusercontent.com/116833964/213824703-8685aba0-6fe2-4cc2-905f-6e2741fb106e.jpg)

     - 6.5.4. Mida la potencia empleando un vatímetro en el software ACDCLAB en RL y anote los resultados en la tabla 6.1.
    
    
![image](https://user-images.githubusercontent.com/116833964/213824209-26cf22d4-640d-4732-a3e8-cbdbdef467dc.png)
![image](https://user-images.githubusercontent.com/116833964/213824293-d38ea983-0a3e-4556-bd1e-9b15127c4bf9.png)
![image](https://user-images.githubusercontent.com/116833964/213824329-cf3e85ae-7029-41da-bcfc-4a337f43c544.png)
![image](https://user-images.githubusercontent.com/116833964/213824357-f3714bfc-ae0d-4b33-86e5-e2c10b444267.png)
![image](https://user-images.githubusercontent.com/116833964/213824385-c52bb985-f8d9-4c6b-8e00-aa060e2f89f4.png)
![image](https://user-images.githubusercontent.com/116833964/213824408-0f35641c-1c15-47b7-81a5-f1f7496dda23.png)
![image](https://user-images.githubusercontent.com/116833964/213824445-6a2de833-a10d-4487-a9e9-8069fff8ccb9.png)
![image](https://user-images.githubusercontent.com/116833964/213824481-befb2d85-cd3c-43b5-afb5-e5c861715e83.png)
![image](https://user-images.githubusercontent.com/116833964/213824508-813349d3-aa75-447b-8c2a-97de1f62b95e.png)
![image](https://user-images.githubusercontent.com/116833964/213824612-6faf0b82-2309-46ef-82dd-7e5886c3482a.png)

Anote los resultados medidos.

![e1adfd693fcd2017f2e3370dbe591bbc-7](https://user-images.githubusercontent.com/116833964/213824170-0a19f1bf-5a7b-48ce-aa85-fc677d1f13b6.jpg)

    - 6.5.4. ¿Se cumple el Teorema de la Máxima Transferencia de Potencia? Argumente su respuesta.
    
   R: Si cumple con el teorema ya que los cálculos sacados son iguales a los simulados, estos contienen un pequeño calculo de erros pero si son cálculos buenos ya que la diferencia solo son por decimales 

     - 6.5.5. ¿Cuál fue la potencia máxima en RL? __________________Watts
    
   Es de 0.048 W

     - 6.5.6. ¿Para qué valor de RL se obtiene la MTP? _______________ Ω
    
   Es de 1000 Ω

     - 6.5.7. Grafique la curva Potencia vs RL .

![image](https://user-images.githubusercontent.com/116833964/213825447-65d1d898-27be-4406-b8cc-c568d8b71453.png)

Calcular errores de las mediciones y comentar los resultados.

![image](https://user-images.githubusercontent.com/116833964/213825226-32e8a606-fb28-42c7-9000-f50abaccde7c.png)

- Conclusion.-

Al hacer cálculos, considere el tipo de multímetro y qué parte del multímetro está mirando, ya que el multímetro puede perderse si se usa incorrectamente. Los protoboards intentan distribuir bien su funcionalidad, en lugar de tener todo en un solo lugar. En los cálculos, considerar las fórmulas del teorema de Thevenin, para cálculos que requieran la aplicación del método, considerar los problemas que nos exigen encontrar y realizar cálculos valiosos, los componentes del experimento, considerarlos y revisarlos antes de ponerlos en práctica, verificar el voltaje de entrada, y presione en consecuencia Instruir para hacer el trabajo.

- Bibliografia.-

Floyd, T. L. (2007). Principios de Circuitos Electronicos. Mexico: Pearson educación.
