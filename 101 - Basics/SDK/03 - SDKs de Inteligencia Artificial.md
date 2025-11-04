# 🤖 SDKs de Inteligencia Artifical

En el campo de **Inteligencia Artificial (IA)** hay una gran cantidad de **SDKs (Software Development Kits)** que facilitan integrar modelos de **Machine Learning, procesamiento de lenguaje natural, visión artificial y más** en tus proyectos.

A continuación te muestro los **principales SDKs de IA**, agrupados por tipo de aplicación 👇

---

## 🤖 **1. Modelos Generativos (texto, imágenes, audio, video)**

Estos SDKs permiten usar **modelos fundacionales** como ChatGPT, Claude, Gemini o DALL·E.

| SDK                        | Empresa      | Uso principal                                                       | Paquete                           |
| -------------------------- | ------------ | ------------------------------------------------------------------- | --------------------------------- |
| **OpenAI SDK**             | OpenAI       | ChatGPT, GPT-4, DALL·E, Whisper (texto, imagen, voz)                | `openai`                          |
| **Anthropic SDK**          | Anthropic    | Claude (modelo conversacional alternativo a ChatGPT)                | `anthropic`                       |
| **Google AI / Gemini SDK** | Google       | Modelos Gemini (texto, imagen, código, razonamiento)                | `google-generativeai`             |
| **Cohere SDK**             | Cohere       | NLP, embeddings, clasificación semántica                            | `cohere`                          |
| **Mistral AI SDK**         | Mistral      | Modelos open-source y APIs de LLMs eficientes                       | `mistralai`                       |
| **Hugging Face Hub SDK**   | Hugging Face | Acceso a miles de modelos open source (transformers, visión, audio) | `huggingface_hub`, `transformers` |

---

## 🧠 **2. Machine Learning tradicional**

SDKs enfocados en entrenar, evaluar y desplegar modelos.

| SDK                               | Uso principal                                                    | Paquete                           |
| --------------------------------- | ---------------------------------------------------------------- | --------------------------------- |
| **TensorFlow**                    | Entrenamiento de redes neuronales, IA en producción              | `tensorflow`                      |
| **PyTorch**                       | Modelos de Deep Learning (muy usado en investigación y academia) | `torch`, `torchvision`            |
| **Scikit-learn**                  | Machine Learning clásico (regresión, clustering, árboles)        | `scikit-learn`                    |
| **XGBoost / LightGBM / CatBoost** | Modelos de boosting optimizados                                  | `xgboost`, `lightgbm`, `catboost` |
| **ONNX Runtime**                  | Ejecutar modelos de IA optimizados en distintas plataformas      | `onnxruntime`                     |

---

## 👁️ **3. Visión por Computadora**

SDKs que permiten trabajar con imágenes, detección de objetos o reconocimiento facial.

| SDK                      | Uso principal                                       | Paquete         |
| ------------------------ | --------------------------------------------------- | --------------- |
| **OpenCV**               | Procesamiento de imágenes y video                   | `opencv-python` |
| **MediaPipe**            | Detección de rostros, manos, postura, etc. (Google) | `mediapipe`     |
| **Ultralytics YOLO SDK** | Detección de objetos en tiempo real                 | `ultralytics`   |
| **Detectron2**           | Segmentación y detección avanzada (Meta AI)         | `detectron2`    |

---

## 🗣️ **4. Procesamiento de Lenguaje Natural (NLP)**

SDKs especializados en análisis de texto, sentimientos, clasificación, embeddings, etc.

| SDK                           | Empresa / Proyecto                                     | Paquete        |
| ----------------------------- | ------------------------------------------------------ | -------------- |
| **Hugging Face Transformers** | Librería de modelos NLP (BERT, GPT, RoBERTa, etc.)     | `transformers` |
| **SpaCy**                     | NLP industrial (tokenización, entidades, dependencias) | `spacy`        |
| **NLTK**                      | Toolkit académico para análisis de texto               | `nltk`         |
| **Cohere SDK**                | Generación de texto y embeddings semánticos            | `cohere`       |
| **OpenAI SDK**                | ChatGPT, embeddings, resumen, traducción               | `openai`       |

---

## 🔊 **5. Audio y Voz**

SDKs para reconocimiento, transcripción o generación de voz.

| SDK                         | Uso                                                 | Paquete             |
| --------------------------- | --------------------------------------------------- | ------------------- |
| **Whisper (OpenAI)**        | Transcripción y traducción de audio                 | `openai`            |
| **SpeechRecognition**       | API para reconocimiento de voz (Google, Bing, etc.) | `speechrecognition` |
| **PyDub**                   | Procesamiento y manipulación de audio               | `pydub`             |
| **Coqui TTS / Mozilla TTS** | Síntesis de voz (texto a voz open source)           | `TTS`               |

---

## 🧩 **6. Plataformas y frameworks de IA completa**

SDKs que ofrecen **entornos integrales de IA** (entrenamiento, despliegue, orquestación de modelos).

| SDK                        | Empresa                                                                      | Uso principal             | Paquete |
| -------------------------- | ---------------------------------------------------------------------------- | ------------------------- | ------- |
| **LangChain**              | Construcción de aplicaciones con LLMs (agentes, flujos de conversación, RAG) | `langchain`               |         |
| **LlamaIndex (GPT Index)** | Integración de datos externos con modelos LLM                                | `llama-index`             |         |
| **Vertex AI SDK**          | Google Cloud AI (entrenamiento, despliegue, predicción)                      | `google-cloud-aiplatform` |         |
| **Azure AI SDK**           | Microsoft (Cognitive Services, OpenAI API, visión, voz, etc.)                | `azure-ai-*`              |         |
| **AWS SageMaker SDK**      | Entrenamiento y despliegue de modelos en AWS                                 | `boto3` + `sagemaker`     |         |

---

### 🚀 En resumen

| Tipo                  | Ejemplos destacados                             |
| --------------------- | ----------------------------------------------- |
| Generativos           | OpenAI, Anthropic, Gemini, Cohere, Hugging Face |
| Machine Learning      | TensorFlow, PyTorch, Scikit-learn               |
| Visión                | OpenCV, MediaPipe, YOLO                         |
| NLP                   | Transformers, SpaCy, NLTK                       |
| Audio/Voz             | Whisper, Coqui TTS                              |
| Frameworks integrales | LangChain, LlamaIndex, SageMaker, Vertex AI     |

