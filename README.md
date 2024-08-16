# 🚁 Proyecto II: Nanodron - Métodos Numéricos 🌟

## Integrantes:
- ROBERTH ALEXANDER GANCINO TOALOMBO
- OSCAR PAUL ALBAN CAMPANA
- FABIAN ALEXANDER SIMBANA PINDUISACA
- JOSE LUIS ANDINO PADILLA

## 📖 Descripción
El proyecto **Nanodron** consiste en simular el movimiento de un nanodron de masa despreciable que se utilizará en aplicaciones meteorológicas. El movimiento del nanodron está gobernado por las siguientes ecuaciones diferenciales:

$$\frac{\delta x}{\delta t} = \alpha (y - x)$$

$$\frac{\delta y}{\delta t} = x(\beta - z) - y$$

$$\frac{\delta z}{\delta t} = xy - \gamma z$$

Donde:
- $x$, $y$ y $z$ son las coordenadas del nanodron en el espacio.
- $\alpha$, $\beta$ y $\gamma$ son constantes positivas.
- $t$ es el tiempo.

## 🎯 Objetivo
El objetivo de este proyecto es desarrollar un programa que permita graficar la trayectoria del nanodron en el espacio, utilizando diferentes valores para $\alpha$, $\beta$ y $\gamma$. Además, el programa debe ser capaz de:
- Permitir la entrada interactiva de los valores de $\alpha$, $\beta$ y $\gamma$.
- Configurar el tiempo de simulación.
- Graficar la trayectoria para diferentes combinaciones de parámetros y condiciones iniciales.

### Detalles Importantes de la Implementación
- La elección del método numérico influye en la precisión de la simulación.
- Las trayectorias serán representadas en un espacio tridimensional, utilizando una librería gráfica adecuada para mostrar la evolución del movimiento del nanodron.

