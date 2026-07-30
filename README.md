Pequeño modulo de pronostico de cumplimiento de metas comerciales utilizando regresion lineal ponderada y suavizamiento exponencial

Caracteristicas tecnicas:
* Deteccion de Outliers ( Metodo IQR) para limpiar ruido en datos historicos
* Ponderacion por antiguedad (Decaimiento exponencial) para dar mas peso a los meses recientes
* Calculo de R² (Coeficiente de determinacion) para medir la precision del modelo
* MAPE ( error porcentual absoluto medio) para calcular el nivel de confianza (ALTO / MEDIO / BAJO)
* Arquitectura: laravel 10, mysql, programacion orientada a objetos (patron service)
