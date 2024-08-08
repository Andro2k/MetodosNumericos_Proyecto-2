# 🚁 Proyecto II: Nanodron - Métodos Numéricos 🌟

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
- Realizar experimentos con al menos 3 casos de prueba diferentes y 3 posiciones iniciales cercanas entre sí.
- Generar un video de máximo 30 segundos demostrando el uso del programa.

## 🛠️ Metodología

### Descripción de la Solución
Para simular las trayectorias del nanodron, se implementarán algoritmos numéricos que resuelvan las ecuaciones diferenciales que describen su movimiento. El programa debe permitir la entrada de parámetros y condiciones iniciales, y visualizar la trayectoria en un gráfico tridimensional.

### Desarrollo Matemático
Se utilizarán métodos numéricos como el método de Euler o el método de Runge-Kutta para la integración de las ecuaciones diferenciales.

### 📊 Diagrama de Flujo / Pseudocódigo
1. **Inicio**
2. Definir las constantes $\alpha$, $\beta$, $\gamma$ y el tiempo de simulación.
3. Establecer las condiciones iniciales $x(0)$, $y(0)$, $z(0)$.
4. Elegir el método de integración numérica.
5. Calcular la trayectoria utilizando el método elegido.
6. Graficar la trayectoria en 3D.
7. Repetir para diferentes parámetros y condiciones iniciales.
8. **Fin**

### Detalles Importantes de la Implementación
- La elección del método numérico influye en la precisión de la simulación.
- Las trayectorias serán representadas en un espacio tridimensional, utilizando una librería gráfica adecuada para mostrar la evolución del movimiento del nanodron.

## 📈 Resultados
En esta sección se presentarán las gráficas de las trayectorias para los diferentes casos de prueba y condiciones iniciales. Se discutirán las diferencias observadas en las trayectorias debido a las variaciones en los parámetros $\alpha$, $\beta$ y $\gamma$.

### 🌟 Caso 1
- Parámetros: $\alpha = 0.1$, $\beta = 0.1$, $\gamma = 0.1$
- Posicion inicial:
  - A: $x = 1$, $y = 1$, $z = 1$

![alt text](ezgif-2-1fabaa24c0.gif)

### 🌟 Caso 2
- Parámetros: $\alpha = 10$, $\beta = 28$, $\gamma = \frac{8}{3}$
- Posicion inicial:
  - B: $x = 0.9$, $y = 0.9$, $z = 0.9$
## 📃 Informe General:
[![Informe General](assets/info.png)](https://epnecuador-my.sharepoint.com/:w:/g/personal/jose_andino_epn_edu_ec/EcrDU2tIPdRAk0satv8X9t8BoqURWEQh-E0G2Zu5oUFQxg)

## 📜 Conclusiones
Se discutirán las conclusiones obtenidas de los experimentos realizados, evaluando cómo las diferentes configuraciones de parámetros afectan la estabilidad y el comportamiento de las trayectorias del nanodron.

## 🎥 Video
Un video de 30 segundos que muestra el uso del programa y la visualización de las trayectorias simuladas.
