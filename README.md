# LLMs
proyecto de bootcamp IA generativa con pythoon

# MODELO DE LENGUAJE ELEGIDO DE HUGGINFACE: 
DistillBert-base-spanish = https://huggingface.co/mrm8488/distill-bert-base-spanish-wwm-cased-finetuned-spa-squad2-es

Elegí este modelo ya que el modelo de lenguaje de bert destilado es una versión mucho más ligera que la original y tiene un 97% de similitud en rendimiento y eficiencia que el Bert base. Esta elección me permite realizar pruebas mucho más rápido y sin consumir mucha memoria de mi computadora. Considero que para este proyecto es lo necesario, tambien he notado que la versión en ingles es superior a la versión de español pero ire realizando pruebas para decidir finalmente si este será el modelo final que usaré o si usaré la versión en ingles; pero definitivamente usaré el distillBert. 

Algo importante que mencionar es que he seleccionado una version del distillbert entrenada mucho más en lo que es responder preguntas con contexto. Al compararlo con el distillbert en español uncased me he dado cuenta que la que estoy utilizando es mejor ya que me ofrece los mismos resultados en otras actividades pero en la de responder preguntas es muy superior.

# Justificación clara de la Elección del Modelo Encoder
- Eficiencia: Es más rápido y ligero que BERT y RoBERTa, lo que es ideal para generar embeddings de manera eficiente.
- Soporte Multilingüe: La versión multilingüe de DistilBERT está diseñada para manejar varios idiomas, incluido el español (Es por ello que todavía estoy decidiendo si utilizar la versión en español o la original).
- Facilidad de Integración: Es compatible con la biblioteca Transformers de Hugging Face, facilitando su uso y adaptación al proyecto.

# COMPARACIÓN CON OTROS MODELOS: 

# BERT (Bidirectional Encoder Representations from Transformers):
- Modelo base: 'bert-base-uncased'
- Ventajas: Muy preciso en diversas tareas NLP debido a su entrenamiento bidireccional.
- Desventajas: Requiere muchos recursos computacionales.

# RoBERTa (Robustly optimized BERT approach):
- Modelo base: roberta-base.
- Ventajas: Mejor rendimiento que BERT debido a mejoras en el preentrenamiento.
- Desventajas: Similar a BERT en cuanto a tamaño y recursos necesarios.

# DistilBERT:
- Modelo base: distilbert-base-uncased.
- Ventajas: Más ligero y rápido que BERT, manteniendo el 97% del rendimiento.
- Desventajas: Ligeramente menos preciso que BERT y RoBERTa.

# BETO:
- Modelo base: dccuchile/bert-base-spanish-wwm-cased.
- Ventajas: Entrenado específicamente para español.
- Desventajas: Similar a BERT en cuanto a tamaño y recursos necesarios.

# Tecnologías
Este proyecto utiliza las siguientes tecnologías:
- Python 3.10.0 importante tener esta version
- https://www.python.org/downloads/release/python-3100/
