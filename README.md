# 📊 Análisis de Ventas - Alura Store Latam

Este proyecto corresponde al **desafío de análisis de datos** para el Sr. Juan, dueño de la cadena de tiendas **Alura Store**.  
El objetivo fue identificar **qué tienda vender** para financiar un nuevo emprendimiento, basándonos en métricas de ingresos, ventas, calificaciones de clientes, productos más/menos vendidos y costos de envío.

---

## 📁 Contenido del repositorio
- `AluraStoreLatam.ipynb`: Notebook con todo el análisis, código y visualizaciones.
- `challenge1-data-science-latam-main/`: Carpeta con los datasets de las 4 tiendas en formato CSV.
- Este `README.md`.

---

## 📌 Datos analizados
Se usaron datos de **4 tiendas** (`tienda_1.csv`, `tienda_2.csv`, `tienda_3.csv`, `tienda_4.csv`) con las siguientes columnas principales:

- `Producto`: Nombre del producto vendido.
- `Categoría del Producto`: Tipo de producto.
- `Precio`: Precio de venta.
- `Calificación`: Calificación del cliente (1 a 5).
- `Costo de envío`: Costo del envío del producto.

---

## 🔍 Análisis realizado

### **1. Ingresos totales por tienda**
| Tienda | Ingresos totales |
|--------|------------------|
| Tienda 1 | $1,150,880,400 |
| Tienda 2 | $1,116,343,500 |
| Tienda 3 | $1,098,019,600 |
| Tienda 4 | $1,038,375,700 |

---

### **2. Categorías de productos más vendidas**
En las 4 tiendas, la categoría **Muebles** fue la más vendida, seguida por **Electrónicos**.

---

### **3. Calificación promedio por tienda**
| Tienda | Calificación promedio |
|--------|-----------------------|
| Tienda 1 | 3.98 |
| Tienda 2 | 4.04 |
| Tienda 3 | 4.05 |
| Tienda 4 | 4.00 |

---

### **4. Productos más y menos vendidos**
| Tienda | Más vendido (ventas) | Menos vendido (ventas) |
|--------|----------------------|------------------------|
| Tienda 1 | Armario (X) | Celular ABXY (X) |
| Tienda 2 | Iniciando en programación (X) | Juego de mesa (X) |
| Tienda 3 | Kit de bancas (X) | Bloques de construcción (X) |
| Tienda 4 | Cama box (X) | Guitarra eléctrica (X) |

---

### **5. Costo de envío promedio**
| Tienda | Costo envío promedio |
|--------|----------------------|
| Tienda 1 | $26,018.61 |
| Tienda 2 | $25,216.24 |
| Tienda 3 | $24,805.68 |
| Tienda 4 | $23,459.46 |

---

## 📊 Visualizaciones
En el notebook encontrarás:
- **Gráfico de barras** comparando ingresos totales.
- **Gráfico de barras** para ventas por categoría.
- **Gráfico horizontal** para calificaciones promedio.
- **Gráfico comparativo** de productos más y menos vendidos.
- **Gráfico horizontal** para costos de envío promedio.

---

## 📝 Conclusiones
Basado en los datos:
- La **Tienda 4** tiene los ingresos más bajos y el costo de envío promedio más bajo.
- Aunque la calificación de clientes es similar a las demás, su volumen de ventas y variedad en categorías la hacen menos competitiva.
- Se recomienda **vender la Tienda 4** para iniciar el nuevo emprendimiento.

---

## 🚀 Cómo ejecutar
1. Clonar este repositorio:
   ```bash
   git clone https://github.com/RafaelD-drive/CHALLENGE-1.git
2. Abrir el archivo AluraStoreLatam.ipynb en Google Colab o Jupyter Notebook.

3. Ejecutar las celdas para reproducir el análisis.
