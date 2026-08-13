# gemini-api
## Instrucciones de ejecución del código
1. Clona el repositorio en tu editor de código
2. Crea el entorno virtual ejcutando en la terminal:
 python -m venv venv

 3. Activa el entorno virtual en la terminal con:
.\venv\Scripts\Activate

4. Selección del Intérprete en VS Code
Para que VS Code reconozca el entorno:
-Presiona Ctrl + Shift + P para abrir la paleta de comandos.
-Escribe "Python: Select Interpreter".
-Selecciona la opción que apunta a tu carpeta del entorno virtual (debería
decir algo como ./venv/Scripts/python.exe ).

5. Instala las librerías en tu terminal usando:
pip install requests

Para actualizar usa:
python.exe -m pip install --upgrade pip

6. Crea una API key y guárdala con cuidado para su uso futuro

-Ingresa a Google AI Studio con tu cuenta de Google.
-En el menú lateral izquierdo, haz clic en el botón Get API key.
-Haz clic en la opción para crear una nueva API Key.
-Ingresa un nombre para la API Key y asígnala a un proyecto. Si no tienes un proyecto creado, puedes crear uno desde esa misma opción.
-Copia la clave y guárdala en un lugar seguro. No compartas la API Key ni la publiques en el repositorio.

7. Crea un archivo .env y añade:
  GEMINI_API_KEY=Tu_Clave_Aqui

Reemplaza Tu_Clave_Aqui por la API Key que obtuviste en Google AI Studio.
8. Presiona Run and Debug, haz clic derecho sobre el archivo y selecciona Run, o utiliza el método de ejecución de tu preferencia. Para realizar las pruebas, inicializa el archivo:
prueba_entorno.py

Debe salir la siguiente respuesta:

<img width="1569" height="973" alt="image" src="https://github.com/user-attachments/assets/4c5725cb-a331-4481-944b-46b0ef1ed44e" />

