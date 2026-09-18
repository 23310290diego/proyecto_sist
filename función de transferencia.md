dado un sistema lineal e invariante en el tiempo (LTI) descrito por una [[ecuación diferencial]] de orden _n_, y aplicando la [[transformada de Laplace]] a ambos lados bajo el supuesto de condiciones iniciales nulas, la[[ ecuación diferencial]] se convierte en una ecuación algebraica en la variable compleja _s_. La función de transferencia se define como el cociente:

G(s)=Y(s)U(s)G(s) = \frac{Y(s)}{U(s)}G(s)=U(s)Y(s)​

es decir, la relación entre la [[transformada de Laplace]] de la salida y la de la entrada.

#### Por qué es la herramienta central del control clásico

Convertir una [[ecuación diferencial]] (difícil de manipular) en una función racional de polinomios (fácil de manipular algebraicamente) es lo que hace posible casi todo el análisis clásico: estabilidad, respuesta transitoria, diseño de compensadores, lugar de las raíces, respuesta en frecuencia, etc.

Interpretación física:

La función de transferencia también puede entenderse como la [[respuesta]] del [[sistema]] a un impulso unitario en la entrada, transformada al dominio de Laplace — es decir, resume por completo el comportamiento dinámico del sistema ante cualquier entrada, sin necesidad de resolver la[[ ecuación diferencial]] cada vez.