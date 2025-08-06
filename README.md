# 📊 Análisis Basado en Datos: Comparativa de Tarifas de Prepago en Megaline

Este proyecto analiza el comportamiento de consumo de los clientes de **Megaline**, un operador de telecomunicaciones. Utilizando datos reales de 500 usuarios, se busca determinar cuál de las dos tarifas de prepago —**Surf** o **Ultimate**— genera mayores ingresos mensuales para la empresa y si hay diferencias significativas entre regiones.

---

## 🎯 Objetivo

Probar las siguientes hipótesis:

- El ingreso promedio generado por los usuarios varía entre las tarifas **Surf** y **Ultimate**.  
- El ingreso promedio en la región de **Nueva York y Nueva Jersey** difiere del resto del país.

---

## 🛠️ Tecnologías Utilizadas

- **Python**: Bibliotecas *pandas*, *numpy* y *scipy* para análisis y pruebas estadísticas.
- **Jupyter Notebook**: Entorno interactivo para el desarrollo del análisis.
- **Conjunto de Datos CSV**: Datos de usuarios, llamadas, mensajes, sesiones de internet y planes tarifarios.

---

## 📊 Pasos Clave

1. **Descripción de los datos**:
   - Revisión de la estructura de cinco tablas: usuarios, llamadas, mensajes, internet y planes.
   - Identificación de valores faltantes y tipos de datos incorrectos.

2. **Preprocesamiento de los datos**:
   - Conversión de tipos de datos, tratamiento de valores nulos (`churn_date`), corrección de formatos y cálculo de consumo mensual por usuario (minutos, SMS, datos y costos).
   - Agrupación de la información por usuario y mes.

3. **Análisis estadístico**:
   - Cálculo de la media, varianza y desviación estándar del uso mensual de minutos, SMS y datos para cada plan.
   - Visualización de las distribuciones mediante histogramas.

4. **Pruebas de hipótesis**:
   - Uso de prueba t de Student para comparar los ingresos mensuales entre planes y entre regiones.

---

## 📈 Resultados

- Los usuarios del plan **Surf** suelen superar sus límites mensuales, generando cargos adicionales que incrementan sus costos.
- Aunque esto representa mayores ingresos para Megaline, muchos usuarios podrían estar pagando más de lo necesario por no elegir el plan adecuado.
- Se recomienda orientar mejor a los usuarios con alto consumo hacia el plan **Ultimate**, optimizando su gasto y fidelizando clientes.
- La diferencia de ingresos entre regiones también resultó significativa, lo cual puede ser útil para campañas publicitarias segmentadas.

---

## ▶️ Cómo ejecutar el proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/TU-USUARIO/megaline-tarifas-analisis
