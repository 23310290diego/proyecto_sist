el controlador es el elemento del lazo de control que ejecuta la "operación de error de entrada": toma la señal de [[error]] _e(t) = r(t) − y(t)_ y la transforma [matemáticamente](matemáticas) en una señal de control _u(t)_ que se aplica al sistema (planta) para producir el efecto deseado.

#### las tres acciones básicas

La familia de controladores más usada en la industria es la **PID**, que combina tres acciones sobre el [[error]]:

- **Acción Proporcional (P):** produce una salida proporcional al [[error]] actual: _u(t) = Kp·e(t)_. Su función de transferencia es simplemente _C(s) = Kp_. Un controlador P puede estabilizar cualquier planta estable, pero tiene desempeño limitado y deja un [[error en estado estacionario ]](offset) que no logra eliminar.
- **Acción Integral (I):** produce una salida proporcional a la acumulación histórica del error en el tiempo. Es un modo de control más lento, pero su virtud es precisamente eliminar el error de estado estacionario que deja la acción proporcional sola.
- **Acción Derivativa (D):** produce una salida proporcional a la tasa de cambio del [[error]], es decir, "predice" hacia dónde se dirige el [[error]]. Se usa para anticipar y amortiguar la [[respuesta]], reduciendo el [sobreimpulso](sobreimpulsos).