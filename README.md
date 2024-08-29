## Estabilidad Absoluta

Un sistema es considerado estable cuando, ante una entrada limitada, produce una salida limitada.

![Sitema estable](https://github.com/user-attachments/assets/5e17785f-4079-4c4d-b5bd-790d401fa962)
## Clasificación de la Estabilidad

1. **Estabilidad Absoluta**: Todos los polos del sistema están ubicados en el semiplano izquierdo (parte real negativa) del plano complejo \(s\).
2. **Marginalmente Estable**: Algunos polos están en el eje imaginario, pero no en el semiplano derecho.
3. **Inestable**: Cualquier polo en el semiplano derecho (parte real positiva) del plano complejo \(s\).


![estabilidad_ejemplos](https://github.com/user-attachments/assets/e3746461-ff1e-4a9a-8a9d-6d4feae569b9)


Los polos del sistema en el espacio de Laplace tienen una equivalencia en la Transformada Z, lo que permite analizar la estabilidad en sistemas discretos. Esta equivalencia se expresa como:

> $$ Z = e^{Ts} $$

Donde:
- \( T \) es el período de muestreo.
- \( s = \sigma + j\omega \) es el polo en el plano \(s\), con \(\sigma\) representando la parte real y \(j\omega\) la parte imaginaria.

***Ejemplos:***
**a)** 

$$ s = σ + j w > Z=e^{Ts} $$

- decimos que

$$ σ > 0 $$ 

*es inestable*
