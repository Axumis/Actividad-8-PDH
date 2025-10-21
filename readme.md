# 🧠 Procesamiento del Habla

Este proyecto implementa dos aplicaciones fundamentales del **procesamiento del habla** en Python:

1. 🎙️ **Reconocimiento de voz (Speech-to-Text)** → Convierte audio en texto.  
2. 🔊 **Síntesis de voz (Text-to-Speech)** → Convierte texto en voz.

Cada funcionalidad se desarrolla en un **notebook independiente**, utilizando librerías de Python especializadas en cada tarea.

---

## 📁 Estructura del repositorio
```bash
procesamiento_del_habla/
│
├── reconocimiento_de_voz.ipynb # Convierte voz (audio .wav) a texto
├── sintesis_de_voz.ipynb # Convierte texto a voz
├── ejemplo.wav # Archivo de audio de ejemplo
├── README.md # Descripción y guía del proyecto
└── requirements.txt # Dependencias necesarias
```
---

## ⚙️ Requisitos

Instalar las dependencias necesarias con el siguiente comando:

```bash
pip install -r requirements.txt
```
---

## Contenido del archivo requirements.txt:
pyttsx3

SpeechRecognition

---

## ▶️ Ejecución
🔊 Síntesis de voz (Texto → Voz)

Abrir el archivo sintesis_de_voz.ipynb.

Ejecutar las celdas del notebook.

Ingresar el texto que quieras convertir en voz.

El programa reproducirá el texto con una voz sintética.

---

## 🎙️ Reconocimiento de voz (Voz → Texto)

Abrir el archivo reconocimiento_de_voz.ipynb.

Asegurarte de tener un archivo de audio en formato .wav en el mismo directorio (por ejemplo, ejemplo.wav).

Ejecutar las celdas del notebook.

El programa procesará el audio y mostrará el texto reconocido.

---

## 🎧 Archivo de ejemplo

El repositorio incluye un archivo de ejemplo:
Audio.wav → contiene una grabación corta (por ejemplo:

“Hola, este es un ejemplo de reconocimiento de voz.”)

---

## 💡 Tecnologías utilizadas

Python 3

pyttsx3 → librería offline para síntesis de voz.

SpeechRecognition → librería para convertir voz en texto (usa la API de Google).

pyaudio → permite la entrada y salida de audio desde el micrófono.

---

## 🧩 Aplicaciones posibles

Asistentes virtuales.

Sistemas de dictado automático.

Conversión de texto a audio para accesibilidad.

Interfaces de voz para automatización.

---

## 👨‍💻 Autor

Proyecto desarrollado por Maximiliano Ruiz
📚 Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial
🧾 Materia: Procesamiento del Habla
📅 Año: 2025