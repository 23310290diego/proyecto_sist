Es un parámetro (típicamente un escalar multiplicativo) que ajusta la magnitud de la acción de control o de la función de transferencia de lazo abierto; en el contexto del lugar geométrico de las raíces, es el parámetro que se hace variar desde 0 hasta infinito para observar el efecto sobre la ubicación de los polos de lazo cerrado.

La ganancia _K_ es, junto con la ubicación de [[polos]] y ceros de la planta, la principal variable de diseño en control clásico. Su efecto es doble y a menudo contrapuesto:

- Aumentarla generalmente hace al [[sistema]] más rápido y reduce el error en estado estacionario.
- Pero, pasado cierto valor, puede empujar los polos de lazo cerrado hacia el semiplano derecho del plano _s_, **desestabilizando** al sistema (o aumentando excesivamente el [sobreimpulso](sobreimpulsos) y las oscilaciones).

Esta tensión entre velocidad de [[respuesta]] y estabilidad es exactamente lo que el lugar geométrico de las raíces permite visualizar y usar como herramienta de diseño: muestra gráficamente para qué rango de valores de _K_ el sistema permanece estable y con qué características de [[respuesta]].