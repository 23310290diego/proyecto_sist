En[[ teoría de control]], los polos son los valores de la [[variable compleja]] \(s\) que hacen que el denominador de una[[ función de transferencia]] sea igual a cero y la [[respuesta]] del sistema tienda a infinito.
#### Por qué los polos son tan importantes

Los polos determinan casi por completo el comportamiento dinámico natural del [[sistema]] (su [[respuesta]] libre, sin entrada)

#### Relación con el lazo cerrado y el LGR

Los polos de[[ lazo cerrado]] son las raíces de la ecuación característica _1 + G(s)H(s) = 0_. Como esta ecuación depende de la ganancia _K_ del [[controlador]], al variar _K_ los polos se mueven por el plano _s_ — y precisamente esa trayectoria es lo que grafica el lugar geométrico de las raíces. Este es el hilo conductor que une los cuatro conceptos que acabas de pedir: el controlador fija _K_ → esto mueve los polos de lazo cerrado → la posición de esos polos determina la estabilidad y el [sobreimpulso](sobreimpulsos) del [[sistema]].