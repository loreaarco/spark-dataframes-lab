# Evidencias de la práctica

Incluye aquí capturas o salidas relevantes del cuaderno.

## 1. Entorno levantado
- Captura de JupyterLab
![Captura de JupyterLab](image.png)
- Captura del Spark Master UI
![Captura del Spark Master UI](image-1.png)

## 2. Lectura de datos
- Esquema de `clientes`
- Esquema de `pedidos`
![Esquema de clientes y pedidos](image-2.png)
- Muestra inicial de datos
![Muestra inicial de datos de clientes y pedidos](image-3.png)

## 3. Limpieza
- Resultado tras `trim`
- Eliminación de duplicados
- Tratamiento de valores nulos
![Limpieza](image-4.png)

## 4. Join
- Resultado del join entre clientes y pedidos
- Explicación breve de los registros perdidos
![Resultado del join entre clientes y pedidos](image-6.png)
En el inner join se pierden los registros cuyo id no aparece en ambas tablas. Esto ocurre porque solo conserva filas con coincidencia exacta en la clave de unión.

## 5. Agregaciones
- Resumen por ciudad y segmento
- Interpretación breve de los resultados
![Resumen por ciudad y segmento](image-7.png)
Los resultados muestran que las ciudades con segmento “Alto” concentran más pedidos y mayores ingresos, como Bilbao y Alicante.
En cambio, los segmentos “Medio” y “Bajo” tienen menos pedidos y menor importe promedio, reflejando menor actividad comercial.

## 6. SQL
- Consulta SQL realizada
- Resultado obtenido
![SQL](image-8.png)

## 7. Parquet
- Escritura del resultado
- Lectura posterior del fichero Parquet
![Parquet](image-9.png)
![Salida Parquet](image-10.png)