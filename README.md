# 📊 Análisis de datos del tráfico de pasajeros por vía aérea en Argentina

## 📋 Descripción
A partir de los registros de aterrizajes y despegues procesados por la Administración Nacional de Aviación Civil (ANAC) en el año 2026, se analizan los flujos de pasajeros en el territorio Argentino como así también el aeropuerto con más actividad aérea.

## 📂 Dataset
- Fuente: [Secretaria de Transporte](https://datos.transporte.gob.ar/dataset/aterrizajes-y-despegues-procesados-por-la-administracion-nacional-de-aviacion-civil-anac/archivo/7b6d0103-0a69-4c67-aed9-33cb58ae12f5)
- Registros: 419262
- Variables:
  1. Fecha UTC
  2. Hora UTC                          
  3. Clase de Vuelo (todos los vuelos)  
  4. Clasificación Vuelo                
  5. Tipo de Movimiento                 
  6. Aeropuerto                         
  7. Origen / Destino                   
  8. Aerolinea Nombre                  
  9. Aeronave                           
  10. Matrícula                          
  11. Pasajeros                          
  12. PAX                                
  13. Calidad dato
  
## :mag:Investigación
### Con Google Colab
- Los 5 (cinco) aeropuertos con mayor actividad aérea (despegues y aterrizajes) en el país.
- Los 5 (cinco) aeropuertos con mayor tráfico de pasajeros.
- Del aeropuerto con mayor tráfico de pasajeros: el flujo de pasajeros por mes y la clase de vuelo que predomina según el volumen de pasajeros.
- Flujo por mes del tráfico nacional e internacional de pasajeros dentro del país.
### Con Power BI 
- Aeropuertos con mayor flujo de pasajeros.
- Porcentaje de pasajeros que vuelan de forma internacional y nacional en territorio Argentino y en el aeropuerto más activo.
- Flujo de pasajeros por mes en territorio Argentino y en el aeropuerto más activo.
- Las 5 (cinco) aerolíneas que más pasajeros transportan (aerolíneas más activas).
## 🛠️ Tecnologías
- Python 3.9
- Librerías: pandas, numpy, matplotlib, seaborn, plotly
- Jupyter Notebook
- Power BI

## 📈 Resultados
Considerando datos oficiales, desde comienzo de año hasta el mes de Julio de 2026 transitaron aproximadamente 20 millones de pasajeros en territorio Argentino. El 52,67% lo hizo por medio de vuelos nacionales (domésticos). [Aeroparque Jorge Newbery](dashboard/dashboard.pdf) (AER) fue el aeropuerto más concurrido en ese período.

<img width="1195" height="672" alt="dashboard" src="https://github.com/user-attachments/assets/65ea0add-cbd6-4de7-831b-89bb3d369aca" />


## 👤 Autor
Carolina Merlos - Curso de Herramientas Básicas para el análisis de datos de Centro de e-Learning UTN BA
