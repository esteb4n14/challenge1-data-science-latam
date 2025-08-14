# Challenge 1 - Data Science LATAM: Análisis de Alura Store

Este proyecto analiza el desempeño de cuatro tiendas de Alura Store para recomendar cuál debería venderse, basándose en métricas clave como facturación, satisfacción del cliente, costos de envío y composición de ventas. El análisis completo y detallado se encuentra en el notebook `AluraStoreLatam.ipynb`.

## Estructura del repositorio

```
challenge1-data-science-latam/
├─ base-de-datos-challenge1-latam/        # Archivos de datos fuente
├─ AluraStoreLatam.ipynb                  # Notebook con el análisis completo
└─ README.md                              # Este archivo
```

## Resultados clave

* **Facturación total**: Tienda 4 tiene la menor facturación ($1,038,375,700), un 9.8% menos que la líder (Tienda 1).

* **Calificación promedio**: Tienda 4 tiene una calificación aceptable (4.00), pero inferior a la mejor (Tienda 3: 4.05).

* **Costo de envío promedio**: Tienda 4 es la más eficiente ($23,459.46), pero no convierte esta ventaja en mayores ingresos.

* **Índice de eficiencia global**: Tienda 4 tiene el menor índice (0.286), reflejando un desempeño inferior en comparación con las demás.

## Conclusión

Se recomienda vender la **Tienda 4** debido a su menor facturación, baja eficiencia global y composición de ventas menos alineada con la demanda. La venta permitirá optimizar recursos y mejorar el retorno general.

## Cómo ejecutar

1. Clona el repositorio:

```bash
git clone https://github.com/esteb4n14/challenge1-data-science-latam.git
cd challenge1-data-science-latam
```

1. Instala las dependencias necesarias:

```bash
pip install jupyter pandas numpy matplotlib seaborn
```

1. Abre y ejecuta el notebook:

```bash
jupyter notebook AluraStoreLatam.ipynb
```

## Autor

* Esteban (esteb4n14)
