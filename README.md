# Pokecardex-collection


# 🃏 PokéVault & Pokécardex Data Studio

Sistema cuantitativo y visual desarrollado en Python y Streamlit para la gestión integral de colecciones de **Pokémon TCG**, análisis de portafolio en Cardmarket, diseño avanzado de binders temáticos y control inteligente de *bulk* para reventa.

## 🚀 Características Principales

* **🔓 Desencriptado Nativo de Pokécardex:** Motor criptográfico en Python (`AES-256-CBC`) para procesar las exportaciones de la plataforma sin fricciones.
* **📊 Dashboard Analítico de Colección:** Métricas en tiempo real de valor en Euros (Trend Price), distribución por expansiones, idiomas y estados de conservación.
* **📦 Gestor de Repetidas (Bulk):** Identificación automática de unidades sobrantes (`cantidad > 1`), simulador de precios de lista con "Precio Piso" (Floor Price) y exportación optimizada para la sección *List Bulk* de Cardmarket.
* **📘 Arquitecto de Binders Ilimitados:** Diseñador interactivo de hojas para grillas de **2x2 (4 bolsillos)**, **3x3 (9 bolsillos)** y **4x3 (12 bolsillos)** filtradas por número de Pokédex, personajes o ilustradores.
* **🎯 Generador de Wishlists:** Conexión en vivo con la API abierta de **TCGdex** para cruzar el catálogo histórico mundial de cartas con tu inventario actual y armar listas de faltantes listas para el *Shopping Wizard* de Cardmarket.

---

## 🛠️ Estructura del Proyecto

* `app.py`: Aplicación web interactiva completa montada sobre Streamlit.
* `Pokecardex_Studio_Colab.ipynb`: Notebook maestra de Google Colab para ejecutar todo el flujo analítico y sincronizar datos.
* `Coleccion_Pokecardex_Completa.csv`: Base de datos maestra unificada de tu colección internacional y japonesa.
* `Repetidas_Cardmarket_Bulk.csv`: Listado curado de cartas repetidas para optimizar ventas.
* `mis_binders.json`: Configuración de tus binders personalizados.
