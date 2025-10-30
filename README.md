# 🧠 TFI Redes Neuronales
**Maestría en Ciencias de Datos**

Facultad de Ingenieria - UCASAL
* Profesor: Dr. Diego Lizondo
* Alumno: Leopoldo Eugenio Lugones
## 🚦 Traffic Sign Classification using CNN
*Multi-class, single-image classification challenge*
### Objetivo
Clasificación Multi-Clase de Imágenes. El modelo debe tomar una única imagen de una señal de tráfico y determinar a cuál de las clases posibles pertenece.
### Dataset: German Traffic Sign Recognition Benchmark (GTSRB)
Conjunto de datos grande y realista, con imágenes capturadas en condiciones de vida real, lo que añade ruido, variaciones de luz, oclusión parcial y diferentes ángulos.

**Archivos:** [gtsrb-german-traffic-sign.zip](https://drive.google.com/file/d/1kCssKYlqeIl-HQce5m1PxUnYHqbMQxwP/view?usp=sharing)
### Clases
El desafío implica clasificar 43 clases diferentes de señales de tráfico (límites de velocidad, advertencias, prohibiciones, etc.). Esto lo convierte en un problema de alta dimensionalidad en el espacio de etiquetas.
### Contexto
El desafío de clasificación de señales de tráfico alemanas (German Traffic Sign Benchmark) es un reto de clasificación multiclase a partir de una sola imagen, celebrado en la Conferencia Internacional Conjunta sobre Redes Neuronales (IJCNN) 2011. Invitamos cordialmente a investigadores de campos relevantes a participar: la competición está diseñada para permitir la participación sin conocimientos especializados del dominio. Nuestro desafío presenta las siguientes características:
* Problema de clasificación multiclase a partir de una sola imagen
* Más de 40 clases
* Más de 50 000 imágenes en total
* Amplia base de datos realista
### Solución
La Convolutional Neural Network (CNN) es la arquitectura elegida debido a su probada eficacia en tareas de reconocimiento de imágenes:
* **Extracción de Características (Capas Convolucionales):** La CNN automáticamente aprende a identificar características clave de las imágenes, como los bordes, las formas y los patrones de color (como el círculo rojo o el triángulo de advertencia), que definen a cada señal.
* **Robustez:** Gracias al entrenamiento con aumento de datos (data augmentation) y las capas de Dropout, el modelo está diseñado para ser robusto y capaz de clasificar la señal correctamente incluso si la imagen está ligeramente rotada, distorsionada o tiene iluminación variable.
* **Resultado Final:** El modelo genera una Predicción (Prediction), indicando la probabilidad de que la imagen de entrada pertenezca a cada una de las 43 clases de señales.
### Agradecimientos
[INI Benchmark Website](http://benchmark.ini.rub.de/)
