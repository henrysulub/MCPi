# MCPi
Estimación Pi Método Montecarlo

Explicación mas rigurosa de pasos para utilizar el método de Monte Carlo para el calculo de π:
1.-Definir un cuadrado: Para aplicar el método de Monte Carlo, primero debemos definir un cuadrado de lado 2 unidades. Este cuadrado actuará como nuestra región de muestreo.
2.-Generar puntos aleatorios: A continuación, generaremos un gran número de puntos aleatorios dentro del cuadrado. Estos puntos se distribuirán uniformemente en toda el área del cuadrado.
3.-Determinar si los puntos están dentro del círculo: Después de generar los puntos aleatorios, debemos determinar si cada punto se encuentra dentro del círculo de radio 1 unidad inscrito en el cuadrado. Esto se puede hacer utilizando la ecuación del círculo: x² + y² ≤ 1.
4.-Calcular la aproximación de Pi: Para obtener una aproximación del valor de Pi, contamos el número de puntos generados que caen dentro del círculo y lo dividimos por el número total de puntos generados. Luego, multiplicamos este cociente por 4, ya que la relación entre el área del círculo y el área del cuadrado es Pi/4.

El método de Monte Carlo es una poderosa herramienta para estimar el valor de Pi y otras cantidades importantes. A medida que generamos más puntos aleatorios, nuestra aproximación de Pi se vuelve más precisa. Este método es especialmente útil en problemas donde las soluciones analíticas son difíciles de obtener.
Recuerda que el método de Monte Carlo tiene aplicaciones más allá de la estimación de Pi. Puede ser utilizado en problemas de simulación, optimización y toma de decisiones, entre otros.
