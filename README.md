🌍 Proyecto: Descripción automática de imágenes satelitales con IA

Este proyecto combina visión por computadora y modelos de lenguaje para transformar datos satelitales en descripciones automáticas en lenguaje natural, accesibles para usuarios no técnicos.

🔹 Objetivo principal
Convertir series temporales de imágenes multiespectrales en descripciones textuales claras sobre el uso del suelo, tipo de cultivo y su evolución temporal.

🔹 Cómo funciona

Extracción de embeddings visuales con DINOv3-Sat
 (visión auto-supervisada).

Enriquecimiento multimodal con AlphaEarth
, integrando datos de clima, relieve y contexto geoespacial.

Generación de descripciones usando LLaMA
, un modelo de lenguaje open source adaptado mediante fine-tuning con el dataset PASTIS
.

🔹 Dataset base

PASTIS (Parcels Annotated with Sentinel-2 Image Time Series): más de 2,400 parcelas agrícolas en Francia (2017–2019), con imágenes multiespectrales de Sentinel-2 y etiquetas de uso del suelo.

🔹 Impacto esperado

Democratizar el acceso a datos satelitales para agricultores, investigadores y responsables de políticas.

Facilitar la interpretación automática de series temporales sin necesidad de expertos en teledetección.

Servir como pipeline multimodal replicable en otros contextos de análisis geoespacial.

🚀 Tecnologías principales

Visión por computadora: DINOv3-Sat

Modelos fundacionales geoespaciales: AlphaEarth

Modelos de lenguaje: LLaMA (fine-tuning con LoRA)

Dataset: PASTIS (Sentinel-2 multiespectral)

Frameworks: PyTorch, Hugging Face, PEFT
