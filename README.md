# Aprendizaje Federado para la Detección de Anomalías en Entornos IoT



## Descripción

Este proyecto desarrolla un Sistema de Detección de Intrusiones (IDS) utilizando *Aprendizaje Federado* en entornos de *Internet de las Cosas* (IoT). La detección de anomalías distribuidas protege la privacidad de los datos sensibles en los dispositivos IoT, mejorando la seguridad sin centralizar información crítica.

### Características principales:

- **Aprendizaje Federado**: Entrenamiento distribuido sin compartir datos privados.
- **Detección de Anomalías**: Identificación eficaz de intrusiones en redes IoT mediante técnicas de *Machine Learning*.
- **IoT**: Especialmente diseñado para sistemas de dispositivos conectados con limitaciones de recursos.
- **Privacidad Garantizada**: Los datos permanecen en los dispositivos locales.

## Tecnologías Utilizadas

### Lenguajes y Herramientas

<p align="center">
  <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn" />
  <img src="https://img.shields.io/badge/Flower-34D058?style=for-the-badge&logo=leaf&logoColor=white" alt="Flower" />
  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=google-colab&logoColor=white" alt="Google Colab" />
</p>

## Contenidos del Proyecto

1. **Introducción**
   - Justificación del uso de *Aprendizaje Federado* y su relevancia en IoT para proteger la privacidad de los usuarios y garantizar la seguridad.
2. **Análisis Exploratorio de Datos (EDA)**
   - Carga de datasets, limpieza de datos, y selección de características utilizando herramientas de análisis como *Pandas* y *NumPy*.
3. **Modelos de Machine Learning**
   - Algoritmos de detección de anomalías como SVM, Árboles de Decisión y Redes Neuronales Profundas.
4. **Red de Aprendizaje Federado**
   - Implementación de la red federada y evaluación comparativa con enfoques centralizados.
5. **Resultados y Simulaciones**
   - Comparación de resultados obtenidos con métricas como precisión, recall, y F1-score para métodos centralizados y federados.

## Instalación y Ejecución

### Paso 1: Clonar el Repositorio

```bash
git clone https://github.com/usuario/repositorio.git
cd repositorio
```

### Paso 2: Crear un Entorno Virtual

```bash
python3 -m venv venv
source venv/bin/activate  # Para Linux/MacOS
venv\Scripts\activate  # Para Windows
```

### Paso 3: Instalar Dependencias

```bash
pip install -r requirements.txt
```

### Paso 4: Ejecución de los Modelos

Para ejecutar los cuadernos de este proyecto, levanta un servidor de Jupyter Notebook con el siguiente comando:

```bash
jupyter notebook
```

Esto abrirá una interfaz web donde podrás acceder y ejecutar los cuadernos incluidos en el repositorio. Navega al directorio `notebooks` y selecciona el cuaderno que deseas ejecutar.

## Datasets Utilizados

- **NSL-KDD**: Dataset clásico para la detección de intrusiones.
- **CSE CIC 2018**: Conjunto de datos actualizado con múltiples categorías de ataques.
- **UNSW-NB15**: Dataset diseñado para analizar el tráfico en entornos IoT.

## Resultados

Los resultados muestran que el uso del *Aprendizaje Federado* mejora la privacidad de los datos y proporciona una detección de anomalías más efectiva. A continuación, algunos ejemplos gráficos:

- **Accuracy** durante el entrenamiento.
- **Recall y Precisión** en la clasificación de ataques.
- Comparación entre **métodos centralizados y federados**.

## Futuras Líneas de Investigación

- Mejora del balance de clases en datasets desbalanceados.
- Exploración de nuevos algoritmos de agregación para aprendizaje federado.
- Expansión de la red para la detección de ataques en tiempo real en entornos IoT más amplios.
