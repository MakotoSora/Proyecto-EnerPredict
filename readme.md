# ⚡ EnerPredict

Calculadora web desarrollada en Python con **Streamlit** para predecir el consumo eléctrico mensual (kWh), estimar el gasto en pesos mexicanos ($ MXN) bajo tarifas de la CFE y simular cuánto dinero se puede ahorrar aplicando medidas de eficiencia energética.

---

## 🚀 ¿Qué hace?

- **Carga de datos flexible:** Permite subir un historial de recibos en formato `.csv` o ingresar directamente un promedio de consumo mensual/diario.
- **Predicción de consumo:** Usa un modelo de Regresión Lineal (`scikit-learn`) para proyectar el consumo eléctrico de 1 a 24 meses a futuro.
- **Cálculo de tarifas CFE:** Estima el costo en `$ MXN` considerando bloques de consumo (básico, intermedio, excedente) y alerta sobre la tarifa de Alto Consumo (DAC).
- **Simulación de ahorro:** Calcula la reducción en kWh y el ahorro económico al aplicar mejoras como iluminación LED, aislamiento térmico o hábitos de ahorro.
- **Gráficas y métricas:** Muestra comparativas visuales y métricas de precisión del modelo (`MAE`, `MAPE` y `R²`).

---

## 🛠️ Tecnologías utilizadas

- **Python 3**
- **Streamlit** (interfaz web)
- **Pandas & NumPy** (procesamiento de datos)
- **Scikit-learn** (modelo de regresión lineal y métricas)
- **Matplotlib** (gráficas)

---

## 💻 Instalación y ejecución

1. **Clona este repositorio:**
   ```bash
   git clone https://github.com/tu-usuario/EnerPredict.git
   cd EnerPredict
   ```

2. **Instala las dependencias necesarias:**
   ```bash
   pip install streamlit numpy pandas matplotlib scikit-learn
   ```

3. **Ejecuta la aplicación:**
   ```bash
   streamlit run app.py
   ```

---

## 📄 Formato del CSV (opcional)

Si deseas cargar tu historial de recibos, el archivo `.csv` debe tener las siguientes columnas:

```csv
periodo,kwh,importe
2024-10,287.0,459.20
2024-11,270.0,432.00
2024-12,264.2,422.72
```

---

## 👥 Equipo 10

Proyecto académico desarrollado para la materia **Metodología y Práctica de la Investigación** (Ciclo 2026B).

- **Carlos Hermosillo Prado** — Ciencias Computacionales
- **Andrés Eduardo Sahagún Márquez** — Ciencias Computacionales
- **Diego Alejandro Saldaña Ramírez** — Nanotecnología
- **Christofer Silvestre Ortiz** — Energías Renovables

**Profesora:** Elizabeth Cristina Hernandez Hernandez