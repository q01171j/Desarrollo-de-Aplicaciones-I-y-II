# 🌐 Guía de Instalación de Insomnia REST Client

**Insomnia** es una herramienta de código abierto diseñada para probar y documentar **APIs REST**, GraphQL y otros servicios web.  
Permite enviar solicitudes HTTP como `GET`, `POST`, `PUT`, `DELETE`, entre otras, de forma sencilla y visual.

---

## 🎯 ¿Para qué lo usamos?

En el curso **Taller de Desarrollo de Aplicaciones II**, utilizaremos **Insomnia** principalmente para:

- ✅ **Probar nuestras APIs creadas con Java Spring Boot**.
- 🔗 Simular peticiones y respuestas HTTP sin necesidad de una interfaz gráfica.
- 🧪 Verificar que los endpoints funcionen correctamente (envío, edición, borrado, etc.).
- 📤 Enviar datos en formato `JSON` y recibir respuestas del servidor.
- 🛠️ Realizar pruebas de autenticación, headers, tokens, entre otros.

---

## 💻 ¿Cómo instalar Insomnia?

1. Ingresa a 👉 [https://insomnia.rest/](https://insomnia.rest/) 🌐  
*(usa Ctrl + clic para abrir en nueva pestaña)*

   ![Página de descarga de Insomnia](./images/1-pagina-descarga-insomnia.png)

2. El sitio detectará automáticamente tu sistema operativo.  
   Haz clic en el botón correspondiente (Windows, macOS o Linux).

   ![Opciones de descarga Insomnia](./images/2-opciones-descarga-insomnia.png)

3. Abre el archivo descargado e instala la aplicación.  
   📌 En Windows, da doble clic al instalador `.exe` y sigue los pasos habituales.

   ![Instalador de Insomnia](./images/3-instalador-insomnia.png)

4. Una vez instalado, abre Insomnia. Aparecerá una pestaña de bienvenida; haz clic en **Continue**.

   ![Bienvenida de Insomnia](./images/4-bienvenida-de-insomnia.png)

5. Inicia sesión con tu cuenta de GitHub.

   ![Ingresar con GitHub en Insomnia](./images/5-ingresar-con-github-en-insomnia.png)

6. Serás redirigido a una página de GitHub; haz clic en **Authorize insomnia-infra**.

   ![Autorizar a GitHub en Insomnia](./images/6-autorizar-a-github-en-insomnia.png)

7. Espera a que la redirección hacia Insomnia se complete automáticamente.

   ![Espera redirección a Insomnia](./images/7-espera-a-redireccion-a-insomnia.png)

8. Haz clic en el botón **Launch**.

   ![Launch de Insomnia](./images/8-launch-de-insomnia.png)

9. Otorga permiso para abrir la aplicación Insomnia.

   ![Abrir Insomnia](./images/9-abrir-insomnia.png)

10. ¡Listo! Ya tienes acceso a Insomnia y puedes comenzar a probar tus APIs.

    ![Probar Insomnia](./images/10-probar-insomnia.png)

---

## 🧠 Consejos para usarlo con Java Spring Boot

- Crea **colecciones** por proyecto y agrupa las peticiones según el módulo o entidad (`/usuarios`, `/productos`, etc.).
- Asegúrate de que tu servidor local (`localhost:8080`) esté corriendo antes de enviar peticiones.
- Usa el formato `application/json` en el body para enviar objetos correctamente.
- Puedes añadir **token JWT** o autenticación básica según la configuración de tu API.

---

## 📂 Archivos sugeridos en esta carpeta

- `Proyecto-API-Spring-Demo.json` → Colección de ejemplo exportada con endpoints comunes.
- `Guía-Básica-Insomnia.pdf` → Manual resumido para probar APIs Spring paso a paso.

---

## ✅ ¡Todo listo!

Ahora puedes probar, depurar y validar el comportamiento de tus APIs creadas en Java con Spring Boot  
de forma clara, rápida y profesional usando **Insomnia**. ¡Es una herramienta clave para cualquier backend developer! 🚀