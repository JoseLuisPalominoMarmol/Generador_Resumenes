# Generador de Resúmenes
Este proyecto consiste en un generador de resúmenes utilizando modelos de procesamiento de lenguaje natural. El modelo ha sido entrenado con un dataset específico y se ha utilizado el modelo preentrenado `mT5_multilingual_XLSum` de HuggingFace.

## Requisitos (ver requirements.txt)
- Python 3.7 o superior
- `transformers` de HuggingFace
- `datasets` de HuggingFace
- `rouge_score` para la evaluación
- Jupyter Notebook

## Instalación
Para instalar las dependencias necesarias, puedes utilizar el siguiente comando:
pip install transformers datasets rouge_score

## Uso
Carga del Dataset
El dataset debe ser tokenizado antes de ser utilizado para entrenar el modelo. En este caso, se utiliza el modelo mT5_multilingual_XLSum para tokenizar el texto.

## Entrenamiento del Modelo
Puedes entrenar el modelo utilizando el script proporcionado en el cuaderno Jupyter. Asegúrate de ajustar los hiperparámetros según sea necesario para tu caso específico.

## Evaluación del Modelo
Se utiliza la métrica ROUGE para evaluar la calidad de los resúmenes generados. Puedes instalar esta métrica usando:
pip install rouge_score

## Guardado del Modelo
Una vez completado el entrenamiento, el modelo se guarda y se sube a HuggingFace para su uso futuro. El modelo entrenado está disponible en HuggingFace.
