# Proyecto IA para ingenieros 
## Miembros del grupo

- José Alejandro Urrego Pabón, CC: 1152471721, Ingeniería Mecánica<br>
- Mateo Toro Molina, CC: 1152225394, Ingeniería Mecánica
  
## Datos

- Los datos fueron tomados de la Competición de Kaggle: https://www.kaggle.com/competitions/DontGetKicked/overview

Para acceder facilmente a los datos seguir lo siguiente:

Pueden poner su propio API con su respectiva llave (key) o usar la nuestra ya añadida en el codigo:

>!pip install kaggle
>!mkdir ~/.kaggle #Se instala la librería de Kaggle
>!touch ~/.kaggle/kaggle.json
>api_token ={"username":"josealejandrourrego","key":"c42e706678df9b3283b5473dbe2c0c8a"} 
>import json
>with open('/root/.kaggle/kaggle.json', 'w') as file:
>   json.dump(api_token, file)
>!chmod 600 ~/.kaggle/kaggle.json
>!kaggle competitions download -c DontGetKicked
>!unzip DontGetKicked.zip #Se descomprime el archivo .zip donde está el dataset

## Videos

Video segunda entrega: https://www.youtube.com/watch?v=JRk7keQAJGo




