# Grupo Data Stalkers

---

drive: https://drive.google.com/drive/folders/1Q_Ug49goOZk_VRvC_6JOpq3Nn81SCXLq?usp=sharing

overleaf: https://www.overleaf.com/1464475512jstbnkvqtnvs

Un notebook con ejemplos: [Aqui](https://www.kaggle.com/pmarcelino/comprehensive-data-exploration-with-python)
## Actualización 12/5
Cada uno investiga las columnas que más relacionan con sus preguntas (las del word de ideas). Matías las de tipo estadístico/censo, Cropa las de altura, materiales, Tomas las de ubicación. Cada una va a estar relacionada con daños eventualmente.
## Notas:
* Matías y tp1.ipynb son similares. Relacionar variables entre sí, y mover esos analisis a tp1.ipynb
* Ejemplos de relacionar variables entre si: familias vs geo_level_1 (hecho), superstructuras vs ubicacion, uso secundario vs ubicacion, altura vs ubicacion (podemos intuir que es una ciudad?) 
* Realizar analisis sobre los datos faltantes del dataset, la poblacion es de 26M y solo hay 260K edificios
* De cuantas personas se conforman una familia
* Los graficos sueltos se van a usar?
---

Por ahora seguiria este orden:
1. Limpieza
* Fijarse si hay datos faltantes (no los hay) 
* Formatear los datos de manera adecuada (hecho)
* Clasificar los tipos de columnas (datos geográficos, material construido, estado de la casa, segundo uso) y ponerlos en variables (Ver si es necesario)
2. Analisis a gran escala
* ¿Que variables estan correlacionadas?
* ¿Qué eje central elegir? Para mí, es evidente que es damage_grade
3. Elegir ejes respecto al sentido común por ej: 
 * la edad está relacionado con el daño causado?
 * el tipo de construcción está relacionado con el daño causado?
 * las casas mas bajitas también son más antiguas?
 
Igualmente se pueden establecer muchas relaciones lógicas, pero debemos quedarnos con aquellas que tengan sentido según nuestro objetivo
