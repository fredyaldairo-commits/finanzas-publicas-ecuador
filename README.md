# Finanzas Públicas del Ecuador (2000–2026)

Dashboard interactivo y accesible para el análisis del Sector Público No Financiero (SPNF) de la República del Ecuador, con datos oficiales de base devengado del Banco Central del Ecuador (BCE) y del Ministerio de Economía y Finanzas (MEF).

## 🚀 Ver en vivo

Puedes acceder y explorar el dashboard interactivo directamente en:
👉 **[https://fredyaldairo-commits.github.io/finanzas-publicas-ecuador/](https://fredyaldairo-commits.github.io/finanzas-publicas-ecuador/)**

---

## 📊 Características y Funcionalidades Interactivas

1. **Semáforo del Gasto Público:**
   - Divide el gasto total entre el ingreso total de cada año.
   - **Verde (≤ 1.00):** Gastó igual o menos de lo que ingresó.
   - **Amarillo (1.01 a 1.10):** Gastó hasta un 10% más de lo que ingresó.
   - **Rojo (> 1.10):** Gastó más de un 10% por encima de sus ingresos.
   - Botones rápidos tipo *chip* para alternar entre años y visualizar el ratio instantáneamente.
   - Ranking histórico de presidentes según la relación de gasto sobre ingreso.

2. **Ingresos vs. Gastos Anuales:**
   - Visualización por barras con franjas de fondo que identifican cada mandato presidencial.

3. **Evolución Mensual:**
   - Comparación mensual interactiva para el año seleccionado o la serie histórica completa (2000–2026).
   - Tooltips enriquecidos con detalle de presidente del mes, resultado y semáforo mensual.

4. **Endeudamiento y Sostenibilidad:**
   - Déficit / Superávit como porcentaje del PIB y en millones de dólares.
   - Intereses pagados como porcentaje del PIB y millones de dólares.
   - Variación de deuda nueva neta.

5. **Deuda Externa Pública y Privada:**
   - Saldo al cierre de cada año (2008 a 2026) y porcentaje del PIB.
   - Comparativa de la deuda externa pública frente al volumen de ingresos fiscales anuales.

6. **Desglose de Ingresos y Gastos Principales:**
   - Ingresos: Petroleros, IVA, Renta, Otros tributos, Seguridad social, Otros no petroleros.
   - Gastos: Sueldos y salarios, Bienes y servicios, Intereses, Prestaciones de la seguridad social, Inversión/capital, Otros.
   - Ranking interactivo porcentual actualizado con el año seleccionado.

7. **Tabla de Datos Completa:**
   - Vista tabular completa con todos los indicadores para máxima accesibilidad y descarga/copia de datos.

8. **Modo Claro / Modo Oscuro:**
   - Soporte automático según preferencias del sistema y botón manual de cambio de tema.

---

## 📂 Fuentes Oficiales de Datos

- **BCE:** *Operaciones del Sector Público No Financiero (SPNF)* — `OperSPNF_DOLARES.xlsx`
- **BCE:** *Operaciones SPNF en porcentaje del PIB* — `OperSPNF_PorcPIB.xlsx`
- **BCE:** *Deuda Externa Total Mensual* — `DeudaExternaTotalMensual.xlsx`

---

## 🛠️ Tecnologías

- **HTML5 + Vanilla CSS:** Diseño responsivo, variables CSS dinámicas, glassmorphism y micro-interacciones.
- **JavaScript Moderno (ES6+):** Motor reactivo ligero sin dependencias pesadas.
- **Chart.js 4.4:** Renderizado interactivo sobre Canvas con tooltips y plugins personalizados.

---

Desarrollado para libre consulta ciudadana, investigación económica y análisis fiscal del Ecuador.
