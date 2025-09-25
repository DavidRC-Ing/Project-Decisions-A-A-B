# 📱 Project-Decisions-A-A-B
**Análisis de Toma de Decisiones con Pruebas A/A/B**

![A/A/B Test Dashboard](https://via.placeholder.com/900x400.png?text=A%2FA%2FB+Testing+Dashboard)

---

## 📋 Descripción del Proyecto
**PROYECTO TOMA DE DECISIONES A/A/B TEST** es un estudio de datos enfocado en evaluar el impacto de un **cambio de tipografía** en una aplicación móvil de venta de productos alimenticios.  

El análisis contempla:  
- 📊 Limpieza y exploración de datos de eventos de usuario  
- 🔎 Evaluación del **embudo de conversión**  
- 👥 Segmentación experimental con grupos **A/A/B**  
- 🧪 Ejecución de pruebas estadísticas para identificar diferencias significativas  

---

## ✨ Características Principales
- 🧹 **Procesamiento de Datos:** depuración y normalización de eventos de usuario  
- 🔍 **Exploración del Embudo de Conversión:** análisis de cada etapa en la ruta de compra  
- 👥 **Segmentación Experimental:** dos grupos de control (A1 y A2) y un grupo experimental (B)  
- 🧾 **Pruebas de proporciones z con corrección de Bonferroni** para garantizar rigor estadístico  
- 🎯 **Recomendaciones Accionables** sobre el cambio propuesto evaluado  

---

## 🛠️ Stack Tecnológico
`Python` · `Pandas` · `NumPy` · `SciPy` · `Matplotlib` · `Seaborn` · `Jupyter Notebook`

---

## 📊 Resultados Principales
| Métrica | Hallazgo |
|---------|-----------|
| 🔄 Conversión | No hubo diferencias significativas entre A1, A2 y B |
| 🛍️ Embudo de Compra | Flujo de usuario estable en todas las etapas |
| 📊 Pruebas Estadísticas | Resultados no significativos tras ajustar con Bonferroni |
| 💡 Recomendación | No implementar el cambio de tipografía en su forma actual |

---

## 🎯 Conclusiones
- ❌ El cambio de tipografía **no genera impacto medible** en las tasas de conversión.  
- 🎯 Los grupos **A1, A2 y B** mostraron comportamientos equivalentes en todo el embudo.  
- 📈 La corrección de Bonferroni confirmó que los resultados no son estadísticamente relevantes.  
- 🔄 Se recomienda **iterar en la propuesta** antes de lanzarla en producción.  
- 👀 Fundamental continuar con un **monitoreo constante** de los usuarios para detectar mejoras futuras.  

---

## 🚀 Instalación y Uso
```bash
# Instalar dependencias
pip install pandas numpy scipy matplotlib seaborn jupyter

# Clonar repositorio
git clone https://github.com/tu-usuario/Project-Decisions-A-A-B.git
cd Project-Decisions-A-A-B

# Ejecutar análisis
jupyter notebook
