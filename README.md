# 📊 Análisis de Datos del Comercio Global

<img src='https://images.pexels.com/photos/5561923/pexels-photo-5561923.jpeg?auto=compress&cs=tinysrgb&w=600' width='600px'>

## Descripción del Proyecto
En este proyecto, asumo el rol de **Científico de Datos** en una empresa de comercio global. La compañía busca comprender mejor su base de clientes, productos y operaciones para **maximizar beneficios** y **optimizar procesos**.

El trabajo se centra en:
- **Segmentar clientes y productos** mediante técnicas de **clustering**.
- Diseñar **modelos de regresión** específicos para cada segmento.
- Generar **insights accionables** que permitan optimizar decisiones estratégicas.

### Datos Utilizados

[Archivo de Datos Original](datos\descripcion_datos.md)

---

## ⚙️ Instalación del Entorno

Clonar repositorio y ejecutar el siguiente comando:

```bash
pip install -r requirements.txt
```

## 🗂️ Estructura Proyecto
```
Proyecto9/
├── datos/
│   ├── tratados/                   # Datos procesados y segmentados.
│   │   ├── clusters/               # Segmentación de clientes y productos.
│   │   │   ├── clientes/           # Clusters específicos de clientes.
│   │   │   │   ├── cluster0_clientes.pkl
│   │   │   │   ├── cluster1_clientes.pkl
│   │   │   │   ├── cluster2_clientes.pkl
│   │   │   │   ├── cluster3_clientes.pkl
│   │   │   │   └── explicacion_clusters_clientes.ipynb
│   │   │   │
│   │   │   ├── productos/          # Clusters específicos de productos.
│   │   │   │   ├── cluster0_productos.pkl
│   │   │   │   ├── cluster1_productos.pkl
│   │   │   │   ├── cluster2_productos.pkl
│   │   │   │   ├── cluster3_productos.pkl
│   │   │   │   └── explicacion_clusters_productos.ipynb
│   │   │
│   │   ├── clustered_info_clientes.pkl  # Info clientes clusterizada.
│   │   ├── clustered_info_productos.pkl # Info productos clusterizada.
│   │   ├── info_clientes.pkl            # Información original clientes.
│   │   └── info_productos.pkl           # Información original productos.
│   │
│   ├── Global_Superstore.csv       # Datos brutos originales del comercio global.
│   └── descripcion_datos.md        # Descripción de los datos utilizados.
│
├── notebooks/
│   ├── 1_EDA.ipynb                 # Análisis exploratorio de datos.
│   ├── config.py                   # Configuración general del proyecto.
│   ├── 2_clustering/               # Notebooks de clustering.
│   │   ├── 2.1_Clustering_Productos.ipynb
│   │   └── 2.2_Clustering_Clientes.ipynb
│   │
│   └── 3_predicciones/             # Notebooks de predicciones.
│       └── 3.1_Prediccion_Productos.ipynb
│
├── src/
│   ├── analisis_estadistico/       # Scripts para análisis estadísticos avanzados.
│   ├── clasificacion/              # Algoritmos y scripts de clasificación.
│   ├── clustering/                 # Scripts relacionados con clustering.
│   ├── combinatoria/               # Scripts de generación de combinatorias.
│   ├── eda/                        # Scripts relacionados con el EDA.
│   └── regresion/                  # Scripts de regresión.
│
├── transformers/
│   ├── base/                       # Transformadores base.
│   └── good_ones/                  # Transformadores optimizados para modelos.
│
├── requirements_dev.txt            # Dependencias para desarrollo.
├── README.md                       # Documentación del proyecto.
└── .gitignore                      # Archivos y directorios ignorados por Git.

```