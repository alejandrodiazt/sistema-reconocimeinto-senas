\# Sistema Multimodal de Reconocimiento de Lenguaje de Señas



Este repositorio contiene el producto final académico-profesional correspondiente al módulo de Machine Learning y Aprendizaje Profundo. La arquitectura ha sido optimizada mediante MobileNetV2 y exportada al formato ONNX para garantizar una eficiencia computacional absoluta durante la inferencia en tiempo real.



\## origen de los datos

Se empleó el conjunto de datos público Sign Language MNIST disponible originalmente en Kaggle el cual contiene decenas de miles de imágenes en escala de grises que representan el alfabeto manual estático.



\## instrucciones para reproducir el flujo completo

1\. Clonar este repositorio en un entorno local o en la plataforma Google Colab.

2\. Instalar las dependencias matemáticas ejecutando el comando `pip install -r requirements.txt` en la terminal.

3\. Asegurarse de que el archivo `modelo\_senas\_v4.onnx` se encuentre en el mismo directorio que el script principal.

4\. Ejecutar el comando `python app.py` para levantar el servidor local de inferencia.

5\. Acceder a la dirección web proporcionada por la consola de Gradio para interactuar con el modelo subiendo imágenes de señas manuales y observando la latencia ultrabaja del motor ONNX Runtime.

