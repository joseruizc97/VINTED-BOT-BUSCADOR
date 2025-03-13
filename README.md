# VINTED-BOT-BUSCADOR
Este es un bot automatizado que busca artículos de marcas específicas en Vinted y envía notificaciones a través de Telegram cuando encuentra artículos nuevos con precios entre 1€ y 10€. (Tanto el precio como las marcas podrán ser modificadas a gusto del usuario)

# REQUISITOS
Python 3.8 o superior

Google Chrome: El bot utiliza Selenium con ChromeDriver para navegar en Vinted.

ChromeDriver: Asegúrate de tener instalado ChromeDriver y que su versión coincida con la de tu navegador Chrome. Descárgalo desde [aquí](https://sites.google.com/chromium.org/driver/).

# INSTALACIÓN
Clona el repositorio:
![image](https://github.com/user-attachments/assets/538d1030-2cdc-4127-bb88-b5a08f6b59f2)

Crea un entorno virtual:
![image](https://github.com/user-attachments/assets/c1a6d83a-892d-4fa4-a8d8-7ba7d54774fd)

Configura las variables de entorno:

Crea un archivo .env en la raíz del proyecto.

Añade las siguientes variables con tus credenciales de Telegram:

![image](https://github.com/user-attachments/assets/f2603bb3-dc94-4fc4-b71c-f541eeed8715)

Para obtener tu TOKEN_TELEGRAM, crea un bot usando BotFather.

Para obtener tu CHAT_ID_TELEGRAM, puedes usar el bot @userinfobot en Telegram.
  
Configura ChromeDriver:

Asegúrate de que la ruta a chromedriver.exe en el código sea correcta. Por ejemplo:

![image](https://github.com/user-attachments/assets/a214fa29-385b-4150-a0b0-e1287096ad66)


# USO
Ejecuta el bot:
python bot_vinted.py

El bot hará lo siguiente:
Buscará artículos de las marcas configuradas en Vinted.
Enviará notificaciones a Telegram cuando encuentre artículos nuevos con precios entre 1€ y 10€.
Esperará un tiempo aleatorio entre 2 y 10 minutos antes de realizar la siguiente búsqueda.

# Marcas disponibles
El bot busca artículos de las siguientes marcas:
Adidas, Nike, Carharrt, The North Face, Lacoste, Tommy Hilfiger, Ralph Lauren

Puedes modificar el diccionario MARCAS en el código para añadir o eliminar marcas.

# Contribuciones
Si deseas contribuir a este proyecto, ¡eres bienvenido! Por favor, abre un issue o envía un pull request con tus mejoras.
