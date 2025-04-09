# 📊 Análisis Integral de Rentabilidad para Cadena de Tiendas - *Alura Store*

## 🎯 Propósito del Análisis

Este proyecto tiene como objetivo analizar y comparar la rentabilidad de **cuatro tiendas** pertenecientes a la cadena **Alura Store**. Mediante un enfoque basado en datos, se identificó la tienda menos rentable y se generaron recomendaciones estratégicas para su mejora.

🔍 Las **métricas clave** analizadas fueron:

- 💰 Facturación total estimada
- 🛒 Popularidad de categorías de productos
- ⭐ Niveles de satisfacción del cliente (basados en calificaciones)
- 📦 Desempeño de productos (más y menos vendidos)
- 🚚 Eficiencia logística (costo promedio de envío)

---

## 🗂️ Estructura del Proyecto

| Archivo/Notebook      | Descripción                                               |
|-----------------------|-----------------------------------------------------------|
| `AluraStoreLatam.ipynb` | Notebook principal con el análisis completo en Python     |
| `challenge_2.py`      | Versión del análisis en script Python (alternativa al `.ipynb`) |
| Carpeta `/imagenes` *(opcional)* | Contiene los gráficos exportados si se guardan como `.png` |

---

## ⚙️ Funcionalidades del Código

El script realiza los siguientes pasos:

1. **📥 Carga de Datos:** Descarga y lee datos desde URLs públicas (GitHub) usando `pandas`.
2. **🧹 Preprocesamiento:** Limpieza de datos y transformación de columnas.
3. **📈 Análisis de Datos:** Cálculo de métricas clave por tienda.
4. **🧾 Generación de Informe:** Consolidación de hallazgos en estructuras fáciles de leer.
5. **📊 Visualización:** Creación de gráficos comparativos con `matplotlib` y `seaborn`.
6. **💡 Recomendaciones:** Propuesta de mejoras estratégicas para la tienda con menor rentabilidad.

---

## 📸 Ejemplos de Gráficos e Insights Obtenidos

### 💰 Facturación Total
> 📉 La **Tienda 4** presentó la menor facturación total.

### 🛍️ Categorías Populares
> 🥇 La categoría **"Electrónicos"** es la más popular en todas las tiendas, aunque con diferentes proporciones.

### ⭐ Satisfacción del Cliente
> 🔄 Las calificaciones promedio son similares, pero con una ligera ventaja para la **Tienda 2**.

### 📦 Productos Más y Menos Vendidos
> ✅ Identificación de productos estrella y otros con bajo desempeño en ventas.

### 🚛 Costos de Envío
> 🔍 La **Tienda 3** presenta el costo promedio de envío más elevado — oportunidad para optimización logística.

### 🧭 Análisis Comparativo Global
> 📊 El **Gráfico Radar** sintetiza el desempeño de cada tienda en múltiples métricas.

💡 **Insight Clave:** La **Tienda 4** fue identificada como la menos rentable. Se generaron recomendaciones para reestructurar su inventario, mejorar la logística y reforzar la estrategia de marketing.

---

## ▶️ Cómo Ejecutar el Proyecto

### 1. Abrir en Google Colab
- Abre el archivo `AluraStoreLatam.ipynb` desde tu Google Drive o directamente desde GitHub.
- O bien, copia el contenido de `challenge_2.py` en un nuevo notebook en Colab.

### 2. Ejecutar las Celdas
- Haz clic en ▶️ al lado de cada celda o usa `Ejecutar todo` en el menú superior.

### 3. Visualización de Gráficos
- Los gráficos aparecerán directamente debajo de las celdas que los generan.
- Si modificas el código para usar `plt.savefig()`, se guardarán como `.png`.

### 4. Revisión del Informe
- Asegúrate de ejecutar las funciones `generar_informe()` y `presentar_recomendaciones()` para obtener la conclusión y estrategias finales.

---

## ✍️ Autor

**Pablo Monsalvo**  
📧 [polargentino@gmail.com](mailto:polargentino@gmail.com)

---

## 📅 Fecha

🗓️ 09 de abril de 2025

---

## 🧩 Versión del Proyecto

**v2.0**

---

## 📌 Recomendación

Si quieres incluir gráficos en el README al visualizarlo desde GitHub, puedes guardar tus imágenes como archivos `.png` y usar sintaxis Markdown para insertarlas, por ejemplo:

```markdown
![Facturación por Tienda](imagenes/facturacion_tiendas.png)
### Las imagenes se generan automaticamente con Google Colab, para guardarlas cambiar las lineas de código:  # plt.show()
    plt.savefig("analisis_comparativo_radar.png")  # Guardar la figura
    plt.close() # Cierra la figura para liberar memoria
