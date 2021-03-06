# Laboratorio-4-2P
# 1. OBJETIVOS 

**Objetivo general**

Analizar y comprobar de forma teórica y experimental la veracidad que tiene el Teorema de Superposición con respecto a los voltajes y corrientes de un circuito eléctrico, por lo que se espera los mismos resultados, se utilizara simuladores virtuales de circuitos eléctricos los cuales brindaran oportunidad de corroborar la exactitud de los datos teóricos obtenidos.

**Objetivos específicos**

* Conocer el comportamiento de la corriente dentro de diferentes nodos y como estas interactúan con los componentes que integran dichos nodos.

* Identificar qué tipo de nodos pueden presentarse dentro de un circuito eléctrico y determinar los nodos principales y nodo referencial.

* Comprender el uso de la ley de Kirchhoff y como aplicarlo dentro de un circuito mixto utilizando simuladores virtuales que permitan su corroboración o en su defecto permita la localización de fallas.

* Identificar las diferencias obtenidas por medio de la ejecución de un circuito mixto, dichas respuestas serán obtenidas de manera teórica, experimental y de simuladores.

# 2. MARCO TEORICO 

![image](https://user-images.githubusercontent.com/105617383/176051739-14a85931-ddf4-440b-9f56-964e2ba2942d.png)

# 3. EXPLICACIÓN DEL PROCEDIMIENTO

3.1 Construir el circuito de la figura 4.1
![image](https://user-images.githubusercontent.com/105617383/176054402-25094f1c-08ae-494d-9e36-d5c3aca33b6b.png)

1. Volver “cero” la fuente de voltaje de 12 V (V2), identificar el sentido de la corriente y encontrar el voltaje VA y la corriente Ix para el circuito nuevo que se formo.

![image](https://user-images.githubusercontent.com/105617383/176059067-b3f8892f-4ba5-4d77-a96f-e1aa68516f11.png)

Utilizando la ley de corrientes de Kirchhoff resolvemos el circuito.

![image](https://user-images.githubusercontent.com/105617383/176057647-bc1deac5-c273-4e78-bead-96b1ae19d05d.png)

2. Convertir en “cero” la fuente de voltaje de 20 V (V1), identificar el sentido de la corriente y medir el voltaje VA y la corriente Ix

![image](https://user-images.githubusercontent.com/105617383/176060703-7d08df23-8691-4ed1-9f89-47a0d6da95c9.png)

Como la fuente de 20 V se convierte en un cortocircuito, se puede obtener una resistencia equivalente para poder reducir el cicuito.

![image](https://user-images.githubusercontent.com/105617383/176059953-761613ba-f123-4200-a6e9-59033c21ba82.png)

En el nuevo circuito reducido identificamos los nodos.

![image](https://user-images.githubusercontent.com/105617383/176061485-a3b22eed-0f0e-4ba6-b15c-cd8792aff3bb.png)

En VA utilizando la Ley de Ohm encontramos su valor.

![image](https://user-images.githubusercontent.com/105671763/176086008-a8759ef2-19c9-4ead-8852-78288a0135d2.png)

Volvemos a reducir el circuito e identificamos los nuevos nodos.

![image](https://user-images.githubusercontent.com/105617383/176062268-4408df0e-5ec7-4d9a-998a-e1fc0bf43cd6.png)

Calculamos la corriente que pasa por Ix y también encontramos la corriente equivalente del circuito.

![image](https://user-images.githubusercontent.com/105671763/176065138-7678b31d-8503-48d5-8fbc-4842e0a07d7a.png)

Reduciendo todo el circuito nos quedamos con uno equivalente en serie.

![image](https://user-images.githubusercontent.com/105671763/176065433-36b3b69d-29b2-43b0-996d-e3e76e12ce72.png)

Calculamos la corriente total de Ix y el voltaje total de VA.

![image](https://user-images.githubusercontent.com/105671763/176066028-b6330100-f219-4780-8665-36243bc51d97.png)

Una vez obtenidos los datos, se colocan en la tabla 4.1 y 4.2 según corresponda.

# 4.RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

Simulación del circuito en Thinkercad.

4.1 Medir el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anotar el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

![image](https://user-images.githubusercontent.com/105617383/176052818-63b69792-0c84-47a4-be94-fb65ea4a1df0.png)

4.2 Circuito donde se hace “cero” la fuente de voltaje de 12 V (V2) y se mide el voltaje VA y la corriente
Ix, respetando tanto la polaridad del voltaje como el sentido de la corriente que se
proporcionan. Anotar el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

![image](https://user-images.githubusercontent.com/105617383/176052774-b32641d9-6ff1-403b-b006-a4cf49f3ae7a.png)

4.3 Circuito donde se hace “cero” la fuente de voltaje de 20 V (V1) y mida el voltaje VA y la corriente Ix, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anotar el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

![image](https://user-images.githubusercontent.com/105617383/176052796-1f98b246-69b3-4f9b-ba1a-0f13a4f3bd39.png)

![image](https://user-images.githubusercontent.com/105617383/176588069-3dd9c341-d9f6-482f-a979-6b60d49e0e18.png)

Tabla 4.1. Medición de voltaje aplicando superposición.

![image](https://user-images.githubusercontent.com/105671763/176570753-cde90b6a-cd5a-4801-bbcb-c0152c4359ac.png)

Tabla 4.2. Medición de corriente aplicando superposición.

![image](https://user-images.githubusercontent.com/105671763/176563370-cb905d44-c2e3-45e5-98b4-b016ad390961.png)

Tabla 4.3. Porcentaje de error del Voltaje Total (VA).

![image](https://user-images.githubusercontent.com/105671763/176559877-c6c157d4-bd57-4992-9b1e-06c5b8d96424.png)

Analizando el porcentaje de error que se muestra en la Tabla 4.3, se concluye que el voltaje total se encuentra bien calculado y la variación mínima del error entre los datos calculados y los simulados es por los decimales que son tomados en cuenta en los cálculos realizados, en cambia, el porcentaje de error entre los valores calculados y experimentales es mayor porque se conoce que los circuitos experimentales se ven afectados por distintos factores, en este caso, se ve afectado el circuito por el valor del voltaje de las fuentes. 

Tabla 4.4. Porcentaje de error de la corriente Total (Ix).

![image](https://user-images.githubusercontent.com/105671763/176559910-5ad12d34-f2b0-4f2e-85d1-33a1dcc7c164.png)

No existe un porcentaje de error entre los distintos datos tomados, permitiendo verificar que el proceso del circuito fue bien calculado y que permite verificar el teorema de superposición, donde las corrientes a través de cualquier elemento del circuito pueden obtenerse sumando algebraicamente las corrientes individuales generadas por una fuente funcionando por si sola y  manteniendo las demás fuentes igualadas a cero.

# 5.VIDEO

https://youtu.be/7dLC-LoGbO4

# 6.CONCLUSIONES
* El teorema de superposición se trata de anular una fuente de energía según su tipo, si es una fuente de voltaje esta se suspende, pero se mantiene la conexión donde se encontraba a diferencia de la fuente de corriente que al igualar a cero se genera un circuito abierto que genera la eliminación de la conexión que poseía esa fuente. El propósito de realizar la superposición es hallar el valor de la corriente con una sola fuente, es decir por separado y realizar la suma algebraica de aquellas para obtener la corriente real del circuito con las dos fuentes.

* Los resultados obtenidos de manera analítica utilizando la superposición son similares a los valores obtenidos en el simulador Thinkercard, es decir el teorema de superposición es un método factible para encontrar la corriente, Además se demostró que al calcular el voltaje en A con la corriente de una sola fuente y sumarla con el resultado que se realizó con la corriente de la otra fuente daba el valor del voltaje en A obtenido en Thinkercard.

# 7.BIBLIOGRAFÍA

Floyd, Thomas. 2007. Principios de circuitos eléctricos. Octava edición.
