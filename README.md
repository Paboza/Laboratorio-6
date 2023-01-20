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
    
    - 6.5.3. Calcule la potencia consumida por RL, para cada valor dado y anote los resultados en la tabla 6.1.

    - 6.5.4. Mida la potencia empleando un vatímetro en el software ACDCLAB en RL y anote los resultados en la tabla 6.1.

    - 6.5.4. ¿Se cumple el Teorema de la Máxima Transferencia de Potencia? Argumente su respuesta.

    - 6.5.5. ¿Cuál fue la potencia máxima en RL? __________________Watts

    - 6.5.6. ¿Para qué valor de RL se obtiene la MTP? _______________ Ω

    - 6.5.7. Grafique la curva Potencia vs RL y comente.

Calcular errores de las mediciones y comentar los resultados.

- Conclusion.-

Al hacer cálculos, considere el tipo de multímetro y qué parte del multímetro está mirando, ya que el multímetro puede perderse si se usa incorrectamente. Los protoboards intentan distribuir bien su funcionalidad, en lugar de tener todo en un solo lugar. En los cálculos, considerar las fórmulas del teorema de Thevenin, para cálculos que requieran la aplicación del método, considerar los problemas que nos exigen encontrar y realizar cálculos valiosos, los componentes del experimento, considerarlos y revisarlos antes de ponerlos en práctica, verificar el voltaje de entrada, y presione en consecuencia Instruir para hacer el trabajo.

- Bibliografia.-

Floyd, T. L. (2007). Principios de Circuitos Electronicos. Mexico: Pearson educación.
