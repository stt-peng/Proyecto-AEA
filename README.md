# Proyecto AEA (Minería de Datos)
## Análisis de Emociones por Audios
**2020-I**

Curso: [Minería de datos](https://github.com/AprendizajeProfundo/Ciencia-de-Datos)

## - David Espinosa
## - Joan Bofill

**Video de introducción:** [https://youtu.be/8G-4li1ZbBE](https://youtu.be/8G-4li1ZbBE)

Consiste en una aplicación de machine learning que clasifica audios de diferentes interlocutores (actores) respecto a las emociones asociadas a su discurso.

---

- Base de datos: https://drive.google.com/file/d/1wWsrN2Ep7x6lWqOXfr4rpKGYrJhWc8z7/view
    - Etiquetas de los archivos:
      - Modality (01 = full-AV, 02 = video-only, 03 = audio-only).
      - Vocal channel (01 = speech, 02 = song).
      - Emotion (01 = neutral, 02 = calm, 03 = happy, 04 = sad, 05 = angry, 06 = fearful, 07 = disgust, 08 = surprised).
      - Emotional intensity (01 = normal, 02 = strong). NOTE: There is no strong intensity for the 'neutral' emotion.
      - Statement (01 = "Kids are talking by the door", 02 = "Dogs are sitting by the door").
      - Repetition (01 = 1st repetition, 02 = 2nd repetition).
      - Actor (01 to 24. Odd numbered actors are male, even numbered actors are female).
      
    - (Para mayor información visitar: https://zenodo.org/record/1188976#.XoPj5M17ntE )
    
---

- Aplicación web para entender espectogramas: https://musiclab.chromeexperiments.com/Spectrogram/
