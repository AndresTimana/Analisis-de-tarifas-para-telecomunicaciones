# 📱 Análisis de Planes Telefónicos de Megaline

Este proyecto analiza los datos de 500 clientes de **Megaline**, una empresa de telecomunicaciones que ofrece dos planes de prepago: **Surf** y **Ultimate**. El objetivo es entender cuál de los dos planes genera más ingresos para la empresa y si hay diferencias de consumo entre distintas regiones del país.

---

## 🎯 Objetivo

Descubrir:

- ¿Cuál de los dos planes (Surf o Ultimate) le da más ganancias a la empresa?
- ¿Los ingresos cambian dependiendo de la región donde viven los usuarios?

---

## 🛠️ Herramientas utilizadas

- **Python**: Para procesar y analizar los datos.
- **Jupyter Notebook**: Entorno para visualizar el análisis paso a paso.
- **Archivos CSV**: Con información de usuarios, llamadas, mensajes, internet y planes.

---

## 📂 Qué se hizo

1. **Exploración de datos**:
   - Se revisó la calidad de los datos y su estructura general.

2. **Limpieza y preparación**:
   - Se corrigieron formatos, se trataron valores faltantes y se organizaron los datos mensualmente por usuario.

3. **Cálculos y análisis**:
   - Se calculó cuánto paga cada cliente según su consumo y plan.
   - Se compararon los ingresos por usuario y región.

4. **Pruebas estadísticas**:
   - Se aplicaron pruebas para saber si las diferencias encontradas eran significativas.

---

## 📊 Resultados principales

- **Ingreso promedio por plan**:
  - **Surf:** $60.71 (con mucha variación)
  - **Ultimate:** $72.31 (estable)

- **Conclusión estadística**:
  ✔️ Se confirmó que los ingresos entre los dos planes **son significativamente diferentes**.
  ✔️ También se encontró una diferencia significativa entre los ingresos de usuarios en **Nueva York / Nueva Jersey** y los del resto del país.

- Muchos usuarios del plan Surf sobrepasan los límites incluidos, lo cual genera cargos adicionales. Esto les hace pagar más sin saberlo, incluso más que el plan Ultimate.

---

## 💡 Conclusión general

Aunque el plan Surf puede parecer más barato, muchos usuarios terminan pagando más de lo esperado por exceder los límites. Megaline podría ayudar a estos usuarios a elegir un plan más adecuado, como el Ultimate, lo cual beneficiaría tanto a la empresa como al cliente.  
Además, las diferencias por regiones indican que se podrían crear campañas específicas según el lugar donde viven los clientes.
