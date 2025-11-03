# 🧭 Proyecto de Decisión Multicriterio – Elección de la Mejor Consultora Estratégica

> *Trabajo práctico de Teoría de la Decisión (AHP, ELECTRE, PROMETHEE) – Grado en Estadística.*

---

## 📘 Descripción general

Este proyecto aplica **técnicas de decisión multicriterio** para determinar cuál de las principales firmas de consultoría estratégica resulta **más adecuada para un perfil junior**, considerando criterios cualitativos y cuantitativos.  

El estudio se basa en el **Proceso Analítico Jerárquico (AHP)** en sus distintas variantes y se complementará con los métodos **ELECTRE** y **PROMETHEE**.

---

## 🧩 Objetivo

Seleccionar, entre cinco alternativas —**McKinsey, BCG, Bain, Oliver Wyman y EY-Parthenon**—, la consultora óptima para un joven profesional considerando los siguientes **criterios de decisión**:

1. Prestigio  
2. Aprendizaje  
3. Cultura organizacional  
4. Proyectos y sectores  
5. Remuneración

---

## ⚙️ Estructura del proyecto
```plaintext
📂 decision-multicriterio-consultoras/
├── funciones_auxiliares/                             # Scripts R con funciones y cálculos intermedios
│   ├── teoriadecision_funciones_multicriterio.R
│   ├── teoriadecision_funciones_multicriterio_utiles.R
│   └── teoriadecision_funciones_multicriterio_diagram.R
├── modelo_consultoras.ahp         # Modelo AHP en formato YAML (paquete ahp)
├── trabajo2.qmd       # Documento principal (Quarto)
├── README.md                      # Este archivo
└── outputs/                       # Tablas, gráficos y resultados finales
```

---

## 🧠 Métodos aplicados

| Método | Descripción breve | Paquete principal |
|:-------|:------------------|:------------------|
| **AHP (Método 1)** | Autovector del mayor autovalor (Saaty clásico) | Funciones de clase |
| **AHP (Método 2)** | Media geométrica | Funciones de clase |
| **AHP (Método 3)** | AHP completo (“de una pasada”) | Funciones de clase |
| **AHP (Método 6)** | Implementación YAML + GUI (`ahp` package) | `ahp` |
| **ELECTRE / PROMETHEE** *(en desarrollo)* | Métodos de sobreclasificación | `MCDA`, `electreR`, `PROMETHEE` |

---

## 🧩 Dependencias de R

Para reproducir el análisis, se utilizan funciones auxiliares propias definidas en los archivos del profesor:

	•	teoriadecision_funciones_multicriterio.R
	•	teoriadecision_funciones_multicriterio_utiles.R
	•	teoriadecision_funciones_multicriterio_diagram.R

---

## 🎓 Autores

Joaquín Vidal Pereira
Universidad de Sevilla - Grado en Estadística
Asignatura: Teoría de la Decisión
Profesor: Pedro L. Luque