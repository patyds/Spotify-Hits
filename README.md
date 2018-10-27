# Spotify-Hits
Red neuronal de canciones de Spotify que intenta predecir con un 67% de exactitud si una canción va a ser un éxito o no tomando en cuenta el Top 100 del 2017 y el Billboard Top 50  de los últimos 5 años
* (La red se basa únicamente en datos y propiedades de las canciones y no en los artistas o bandas)

## dataSpotify.csv
Dataset con alrededor de 3800 canciones que se encuentran en la aplicación de Spotify
Incluye en Top 100 del 2017 y el Top 50 de Billboard de los últimos 5 años.
### Columnas:
  * acousticness
  * danceability
  * duration_ms
  * energy
  * instrumentalness
  * keis
  * liveness
  * loudness
  * mode
  * speechiness
  * tempo
  * time_signature
  * valence
  * song_title
  * artist
  * Hit: 1 si fue un exito (Dentro del Top100 o el Top 50), 0 si no lo fue. 

## RedProyecto.ipynb
Jupyter Notebook con la red neuronal realiada on la librería Keras
