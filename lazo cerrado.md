un [[sistema]] en lazo cerrado es aquel en el que la [[señal de salida]] se retroalimenta y se compara continuamente contra la referencia, generando el [[error]] que alimenta al controlador — a diferencia del [[lazo abierto]], donde la señal de control se calcula sin verificar el resultado real obtenido.

#### Función de transferencia en lazo cerrado

Si _G(s)_ es la planta y _H(s)_ es la realimentación (sensor), la función de transferencia global del lazo cerrado es:

M(s)=Y(s)/R(s) = G(s)/1+G(s)H(s0

El término _1 + G(s)H(s) = 0_ se llama ecuación característica del sistema, y sus raíces son precisamente los [[polos]] de lazo cerrado — el punto donde este concepto se conecta directamente con el punto 9.

#### Por qué importa el lazo cerrado

- Permite **rechazar perturbaciones**: si algo externo altera la salida, el [[error]] lo detecta y el controlador corrige.
- Permite operar con **incertidumbre en el modelo** de la planta, porque no depende de que el modelo sea perfecto — se corrige en tiempo real contra la salida medida.
- Introduce el **riesgo de inestabilidad**: la realimentación negativa reduce el error, pero si la dinámica del lazo tiene ciertas características, puede comportarse como si fuera positiva y generar oscilaciones crecientes ("hunting").