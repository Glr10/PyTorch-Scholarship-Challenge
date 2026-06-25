# Formulario web para clientes

Página web con un formulario de contacto listo para usar. Es un solo archivo
(`index.html`) que incluye HTML, estilos (CSS) y la lógica (JavaScript), así que
**no necesita instalación ni servidor** para probarlo.

## Cómo usarlo

1. Abre `index.html` haciendo doble clic, o arrástralo a tu navegador.
2. Completa el formulario y presiona **Enviar**.
3. Verás un mensaje de confirmación. Los datos quedan registrados en la consola
   del navegador (F12 → pestaña *Console*).

## Campos del formulario

- **Nombre completo** (obligatorio)
- **Correo electrónico** (obligatorio, con validación de formato)
- **Teléfono** (opcional)
- **Servicio de interés** (obligatorio)
- **Mensaje** (obligatorio, mínimo 10 caracteres)

## Cómo recibir los datos de verdad

Tal como está, el formulario **valida y muestra** los datos pero no los envía a
ningún lado (no tiene servidor). Para recibir las respuestas tienes varias
opciones sencillas:

- **Formspree / Getform / Basin**: servicios gratuitos. Solo cambias la etiqueta
  `<form>` para que apunte a su URL y ellos te envían cada respuesta por correo.
- **Google Forms**: si prefieres no programar el backend.
- **Tu propio servidor** (Node, Python, PHP, etc.): recibir el `POST` con los datos
  que ya se arman en la variable `datos` dentro de `index.html`.

Si me dices qué opción prefieres, te dejo el formulario conectado y funcionando.
