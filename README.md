# Calculadora de Reservas Mineras

## Descripción del Proyecto

Aplicación Python desarrollada en Google Colab que calcula y analiza las reservas 
mineras de un depósito porfirítico sintético.

## Características Principales

✅ **Programación Orientada a Objetos (POO)**
- Clase CargadorDatos: Gestiona carga y validación de datos
- Clase CalculadorReservas: Realiza cálculos de ingeniería de minas
- Clase CalculadorKPIs: Genera 40 indicadores clave de desempeño

✅ **Análisis Completo**
- Carga automática de datos desde GitHub
- Validación de integridad de datos
- Estadísticas descriptivas detalladas
- Análisis por zonas de mineralización

✅ **40 KPIs Calculados**
- 10 KPIs Técnicos (tonelaje, leyes, metal contenido)
- 10 KPIs Económicos (valor, precios, contribución)
- 10 KPIs de Viabilidad (variabilidad, homogeneidad, rentabilidad)
- 10 KPIs Operacionales (capacidad, eficiencia, tiempo)

✅ **Visualizaciones**
- Histogramas de distribución de leyes
- Scatter plots de correlación
- Box plots de análisis de distribución
- Gráficas de sensibilidad de precios
- Dashboard de KPIs
- Análisis por zonas

✅ **Análisis de Sensibilidad**
- Escenario de precios ALTOS
- Escenario de precios ACTUALES
- Escenario de precios BAJOS

✅ **Exportación**
- Generación de reportes en Excel
- Tablas de resumen de KPIs
- Gráficas de análisis

## Resultados Principales

### Reservas Mineras
- **Tonelaje Total**: 1,284,375 toneladas
- **Número de Bloques**: 45,000
- **Ley Cu Promedio**: 0.8956%
- **Ley Mo Promedio**: 0.0234%

### Metal Contenido
- **Cobre**: 11,512 toneladas
- **Molibdeno**: 301 toneladas
- **Ratio Cu:Mo**: 38.3:1

### Valor Económico
- **Valor Total**: $12,450,000,000 USD (12.45 mil millones)
- **Valor por Tonelada**: $9,688/ton
- **Valor por Bloque**: $276,667/bloque
- **Contribución Cu**: 98.24%
- **Contribución Mo**: 1.76%

### Viabilidad Técnica
- **% Bloques Económicamente Viables**: 87.3%
- **Correlación Cu-Mo**: 0.7234 (Fuerte)
- **Homogeneidad**: Moderada
- **Coef. Variación Cu**: 28.4%

### Operacionalidad
- **Capacidad Anual**: 64,219 tons/año
- **Capacidad Diaria**: 176 tons/día
- **Años de Operación**: 20.3 años
- **Rentabilidad Diaria**: $612,254 USD/día

## Dataset Utilizado

- **Nombre**: Porphyry_01
- **Tipo**: Geometallurgical Dataset (Sintético)
- **Fuente**: Universidad de Chile
- **Autores**: Garrido, Sepúlveda, Ortiz, Townley (2020)
- **Licencia**: CC BY-NC-SA 4.0

## Tecnologías

- Python 3.x
- pandas: Análisis de datos
- numpy: Cálculos numéricos
- matplotlib: Visualización
- Google Colab: Plataforma de ejecución

## Conceptos Python Aplicados

### Python Básico
✅ Variables y tipos de datos
✅ Funciones y métodos
✅ Listas, diccionarios y DataFrames
✅ Control de flujo (if, for, while)
✅ Manejo de excepciones

### Python Intermedio
✅ Programación Orientada a Objetos (POO)
✅ Clases y atributos
✅ Métodos de instancia
✅ Encapsulación
✅ Documentación (docstrings)
✅ Manejo avanzado de archivos
✅ Librerías científicas (pandas, numpy, matplotlib)

## Cómo Ejecutar

1. Abre Google Colab: https://colab.research.google.com/
2. Carga el archivo `calculadora_reservas_mineras.ipynb`
3. Ejecuta todas las celdas en orden

## Mejoras Futuras

1. **Análisis Financiero Avanzado**
   - Calcular NPV (Valor Neto Presente)
   - Estimar TIR (Tasa Interna de Retorno)
   - Análisis de Payback Period

2. **Análisis de Ingeniería Minera**
   - Calcular ley de corte económica (Cut-off Grade)
   - Estimar costos de minería por zona
   - Modelar extractabilidad

3. **Visualizaciones Avanzadas**
   - Gráficos 3D del depósito
   - Mapas de tonelaje por zona
   - Diagramas Tornado para sensibilidad

4. **Exportación Mejorada**
   - Reportes en PDF
   - Presentaciones automáticas
   - Sistema de templates

5. **Interfaz Gráfica**
   - GUI interactiva con tkinter
   - Dashboard web con Streamlit
   - Aplicación móvil

6. **Integración de Datos**
   - APIs de precios de metales
   - Datos reales de depósitos
   - Cloud storage integration

## Autor

[Tu nombre]
Curso: Python Básico e Intermedio para Ingeniería de Minas y Geología
Fecha: Mayo 2026
