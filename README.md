Nombre del proyecto: Calculadora Básica en Python
Descripción del proyecto: Se presenta una pantalla que representa una calculadora básica, dicha calculadora tiene los botones de los dígitos del 0 al 9, un botón para el punto “.”, un botón para limpiar la pantalla de la calculadora, y un botón para las operaciones básicas: Suma, Resta, Multiplicación, División, Porcentaje y Raiz cuadrada. 
Tecnologías usadas: Python, librería tkinter y librería math
Características principales: Importa la librería tkinter y le da el alias tk para facilitar su uso. Importa la librería math para poder usar la función de raíz cuadrada (math.sqrt). Importa la librería math para poder usar la función de raíz cuadrada (math.sqrt).
global expresion_actual: Declara una variable global para almacenar la cadena de la operación que el usuario está escribiendo (ej. "15+5").
def clic_boton(simbolo): Esta función es el corazón de la lógica. Se llama cada vez que se presiona un botón.
●	eval(): Esta función de Python es muy útil para este tipo de proyectos. Evalúa una cadena de texto como si fuera una expresión matemática y devuelve el resultado. Por ejemplo, eval("10+5") devuelve 15. Es una forma simple y efectiva de resolver las operaciones.
●	try...except: Es un bloque para manejar errores. Si el usuario ingresa una operación inválida (como "5/0"), el programa no fallará, sino que mostrará "Error" en la pantalla.

Instalación: Opción A – Para ejecutar la aplicación dirígete a la carpeta “dist” y ejecuta el archivo Calculadora.exe
Opción B – Para abrir el proyecto de Python y manipular el código abrir el archivo main.py en algún editor de código y asegurarse de tener instalado el interprete de Python. 
Nota: Se incluye guía de pasos para instalar y configurar VS Code (IDE) y Python (interprete) https://rodokizzzdev.com/archivos/Instalación y Config VSCyPython.pdf
Uso: Al iniciar la ejecución de la calculadora, se da click en un botón digito (1,2,3,4,5,6,7,8,9,0), luego se da click en un botón operador (*,/,-,+,%,sqrt), opcionalmente si se requiere expresar una cifra fraccionaria, dar click en el botón Punto “.”, si es requerido borrar algo que esta en la pantalla de la calculadora dar click en el botón “C”, y si se quiere obtener el resultado de una expresión dar click en el botón igual “=”.

Contribuciones: 
¡Las contribuciones son bienvenidas! Si deseas ayudar a mejorar este proyecto, por favor sigue los siguientes pasos:
1.	Haz un fork del repositorio: Crea una copia del repositorio en tu cuenta de GitHub.
2.	Clona el repositorio: Clona tu fork a tu máquina local.
Bash
git clone https://github.com/rodokizzzdev/calculadoraPython.git
3.	Crea una nueva rama: Trabaja en una rama separada para tus cambios.
Bash
git checkout -b nombre-de-tu-rama
4.	Haz tus cambios y commit: Realiza las modificaciones que consideres necesarias y describe claramente tus cambios.
Bash
git add .
git commit -m "Descripción clara de tus cambios"
5.	Envía los cambios a tu repositorio: Sube tus cambios a tu fork en GitHub.
Bash
git push origin nombre-de-tu-rama	
6.	Abre un pull request: Desde tu repositorio en GitHub, abre un pull request hacia la rama main del repositorio original. Explica tus cambios y por qué crees que deberían ser integrados.
Una vez que envíes tu pull request, lo revisaré lo antes posible. ¡Gracias por tu interés en mejorar este proyecto!

Licencia: MIT
