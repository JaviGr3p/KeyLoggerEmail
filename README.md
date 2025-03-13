# ☠︎ Keylogger Email - J4Gr3p

Este es un **keylogger educativo** en Python, diseñado para **demostrar la importancia de la seguridad en endpoints**.  

> 🛑 **Advertencia:** El uso de este script **debe ser autorizado y en entornos controlados**. No nos hacemos responsables del uso indebido.

---

## 🗂️ Características  
✔ Captura las teclas presionadas en un sistema  
✔ Guarda el registro en un archivo `keylog.txt`  
✔ Envía el archivo por **correo electrónico** automáticamente  
✔ **Código personalizable** con configuración fácil  

---

## ▶️ Instalación  
1. Clona el repositorio:  
   ```bash
   git clone https://github.com/J4Gr3p/KeyLoggerEmail.git
   cd KeyLoggerEmail
   ```
2. Instala las dependencias:
```bash
pip install -r requirements.txt
```

3. Configura tu correo en el archivo keylogger.py:
```bash
Reemplaza tu_email@gmail.com y tu_contraseña con tus credenciales (usa una App Password).
Cambia destinatario@gmail.com por el correo donde recibirás los registros.
```

##🚦 Uso

Ejecuta el script:
```bash
python keylogger.py
```

El keylogger funcionará en segundo plano, enviando los registros por correo cada 60 segundos.

⚡ Recomendaciones de Seguridad
♾️ Usar solo en entornos de prueba o con autorización explícita.
♾️ No ejecutar en sistemas de terceros sin permiso.
♾️ Eliminar los registros después de la prueba para evitar exposición de datos.

##🗝️ Licencia
Este proyecto es de uso educativo. No nos hacemos responsables del mal uso de este código.

☘︎ Desarrollado por J4Gr3p 🏍️
