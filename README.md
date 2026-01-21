# Plantilla TOPSIS – Evaluación Multicriterio (Excel)

Esta plantilla en Excel implementa el método **TOPSIS** (*Technique for Order Preference by Similarity to Ideal Solution*), una técnica de **toma de decisiones multicriterio** utilizada para **evaluar y rankear alternativas** con base en múltiples criterios ponderados.

La plantilla está pensada para **uso académico y práctico**, y combina los métodos **AHP + TOPSIS** de forma automatizada.

---

## Objetivo de la plantilla

Facilitar la toma de decisiones cuando existen varias alternativas y múltiples criterios de evaluación, permitiendo identificar la alternativa **más cercana a la solución ideal**.

Ejemplos de aplicación:
- Selección de proveedores  
- Evaluación de proyectos  
- Comparación de tecnologías  
- Análisis financiero  
- Evaluación de riesgos  
- Toma de decisiones empresariales  

---

## Métodos implementados

### 🔹 AHP (Analytic Hierarchy Process)
Se utiliza para **calcular los pesos de los criterios** a partir de comparaciones por pares, asegurando coherencia en la importancia asignada a cada criterio.

### 🔹 TOPSIS
Se utiliza para:
- Normalizar la matriz de decisión  
- Aplicar los pesos de los criterios  
- Calcular la solución ideal y anti-ideal  
- Determinar un **ranking final de alternativas**  


---

## 📝 Hoja 1: ENTRADA

### Función
Permite ingresar los **datos base del problema de decisión**.

### Contenido
- Lista de alternativas (A1, A2, A3, etc.)  
- Lista de criterios (C1, C2, C3, etc.)  
- Matriz de evaluación donde cada alternativa se evalúa según cada criterio  

** Notas importantes**
- Todos los valores deben ser numéricos  
- Los criterios deben definirse previamente como **beneficio** o **costo**  
- Esta hoja alimenta todo el proceso posterior  

---

## Hoja 2: AHP

### Función
Calcular los **pesos de los criterios** mediante comparaciones por pares.

### Qué se obtiene
- Pesos normalizados de cada criterio  
- Verificación de consistencia del juicio (CR)  

**Recomendación**
- El índice de consistencia (CR) debe ser aceptable antes de continuar  
- Los pesos calculados se usan automáticamente en TOPSIS  

---

## Hoja 3: CÁLCULOS

### Función
Ejecutar internamente el método TOPSIS.

### Procesos automáticos
- Normalización de la matriz de decisión  
- Aplicación de los pesos de AHP  
- Cálculo de la solución ideal positiva y negativa  
- Cálculo de distancias a cada solución  

**Esta hoja no debe modificarse**  
Contiene fórmulas automatizadas dependientes de las hojas anteriores.

---

## Hoja 4: RESULTADOS

### Función
Mostrar los **resultados finales del análisis**.

### Resultados mostrados
- Coeficiente de cercanía para cada alternativa  
- Ranking de alternativas (de mejor a peor)  
- Identificación de la alternativa óptima  

 Cuanto **mayor sea el coeficiente de cercanía**, mejor es la alternativa evaluada.

---

##  Flujo de uso recomendado

1️⃣ Ingresar alternativas y criterios en **ENTRADA**  
2️⃣ Definir pesos de criterios en **AHP**  
3️⃣ Revisar cálculos automáticos en **CÁLCULOS**  
4️⃣ Analizar el ranking final en **RESULTADOS**  

---

## Requisitos

- Microsoft Excel (compatible con archivos `.xlsm`)  
- Macros habilitadas  
- No requiere conexión a internet  
- No requiere software adicional  

---

## Referencias

- Hwang, C. L., & Yoon, K. (1981). *Multiple Attribute Decision Making*  
- Saaty, T. L. (1980). *The Analytic Hierarchy Process*  

---

## Autor

**Daniel Stevan Ortiz Dorado**  
Plantilla desarrollada con fines **educativos y analíticos**.


