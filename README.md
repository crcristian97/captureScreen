 # 📸 Aplicación Web de Captura de Pantalla
Este proyecto es una página web sencilla que permite a los usuarios capturar una captura de pantalla de la página actual y descargarla como una imagen usando la librería html2canvas.

 ## 📋Características
Captura todo el contenido visible de la página, incluidos los elementos dinámicos.
Descarga la captura como un archivo PNG.
Ajusta la escala de la captura según el window.devicePixelRatio para pantallas de alta resolución.

## 🚀 ¿Cómo Funciona?
Cuando el usuario hace clic en el botón "Tomar captura de pantalla", la aplicación:

Oculta temporalmente el botón de captura.
Utiliza html2canvas para capturar el contenido de la página web.
Convierte el contenido capturado en un lienzo (canvas) y lo transforma en una imagen PNG.
Descarga automáticamente la imagen.
Vuelve a mostrar el botón después de completar la captura.
