# Mi Proyecto: Clasificador the imagenes de lugares turisticos

## Descripcion
La idea es crear un modelo que me clasifique mis fotos favoritas entre Mar, Ciudad y Montania

## Demo


## Por que este tema
Uno de mis hobbies favoritos es viajar, y de los lugares visitados siempre me llevo
una gran impresion de las playas de El Salvador y California. Sus montanias y bellas ciudades.

## Dataset
- Total de imagenes: 240
- Clases: ['Playa','Ciudad','Montania']
- Fuentes: de donde vinieron las imagenes

## Resultados
Mejor accuracy obtenido: 54%

| Clase     | Precision | Recall | F1   |
|-----------|-----------|--------|------|
| Ciudad    | 0.00      | 0.25   | 0.40 |
| Playa     | 0.00      | 0.00   | 0.00 |
| Montania  | 0.38      | 0.88   | 0.53 |

## Analisis de errores
Los tonos de azules, presentes en el cielo en todas las imagenes.
Creo que hizo falta mas analisis de la parte de abajo donde estaba
la diferencia principal.

## Aprendizajes
No es facil clasificar imagenes que tienen casi la misma estructura visual en la parte
superior, que es el cielo azul.

## Tecnologias usadas
- Python, TensorFlow/Keras
- Transfer Learning con ResNet50
- Streamlit para interfaz
- Streamlit Cloud para deploy

## Autor
Ricardo Guzman Alfaro