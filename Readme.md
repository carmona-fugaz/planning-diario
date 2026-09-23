# Mi Día — Planning Diario

**Mi Día** es un planificador personal para organizar tu día a día: un calendario semanal para tus eventos con hora de inicio y fin, y una lista de tareas diarias recurrentes con casillas para marcarlas según las vas completando. Todo pensado para verse de un vistazo, sin complicaciones.

Funciona como aplicación web y también como app instalable en el móvil o la tablet (PWA), con tus datos sincronizados en la nube en tiempo real entre todos tus dispositivos.

## ✨ Qué puedes hacer con ella

- **Calendario semanal**: navega entre semanas y consulta de un vistazo qué tienes cada día.
- **Eventos con horario**: crea eventos (trabajo, estudio, gimnasio, citas...) con fecha, hora de inicio, hora de fin, color y notas.
- **Tareas diarias recurrentes**: añade tareas que quieres repetir cada día (beber agua, leer, ordenar...) y márcalas con un check; el check es independiente para cada fecha, así que vuelven a aparecer sin marcar al día siguiente.
- **Panel de productividad**: reloj y fecha en tiempo real de España (zona horaria Europe/Madrid), resumen de eventos del día, progreso de tareas completadas y tu próximo evento.
- **Modo claro / oscuro** y **4 colores de acento** para personalizar el aspecto (rosa, azul, rojo o verde).
- **Copia de seguridad manual**: exporta tus datos a un archivo `.json` cuando quieras tener una copia extra.

## 🔗 Acceder a la aplicación

👉 **https://carmona-fugaz.github.io/planning-diario/**

Puedes usarla directamente desde el navegador (portátil, móvil o tablet) sin instalar nada, o instalarla como app siguiendo los pasos de abajo.

## 📱 Instalación en móvil o tablet (PWA)

Instalarla te da un icono propio en la pantalla de inicio y la abre a pantalla completa, como una app normal.

1. **Abre el enlace en Google Chrome**: https://carmona-fugaz.github.io/planning-diario/
2. Toca el menú de tres puntos (⋮) en la esquina superior derecha del navegador.
3. Selecciona **"Instalar aplicación"** (a veces aparece como "Descargar aplicación").

> ⚠️ **Importante:** no elijas "Añadir a la pantalla de inicio" ni "Crear acceso directo" — esas opciones solo crean un enlace directo al navegador. Debes pulsar específicamente **"Instalar aplicación"** para que se abra en su propia ventana, sin la barra de Chrome, y funcione como una app independiente.

En un ordenador, Chrome también permite instalarla: busca el icono de instalación (una pantalla con una flecha) en la barra de direcciones.

## 🔐 Cuenta y sincronización entre dispositivos

La aplicación usa un sistema de cuentas (correo y contraseña) para guardar tus datos en la nube:

1. La primera vez, crea tu cuenta desde la pantalla de acceso.
2. A partir de ahí, inicia sesión con esas mismas credenciales en cualquier otro dispositivo: móvil, tablet u ordenador.
3. **Todo se sincroniza al instante y de forma automática**: un evento que añadas o una tarea que marques en un dispositivo aparece al momento en los demás, sin que tengas que hacer nada más.

Si en algún momento pierdes la conexión a internet, la app te avisa y sigue mostrando la última versión sincronizada; en cuanto recuperas la conexión, se pone al día sola.

Tus datos son privados: solo tu cuenta puede ver y modificar tus propios eventos y tareas.

## 🛠️ Cómo está hecha (para curiosos)

Un único archivo web (HTML, CSS y JavaScript) sin frameworks, con [Supabase](https://supabase.com) como base de datos y sistema de autenticación en la nube, y configurada como PWA (manifiesto + service worker) para poder instalarse y funcionar sin conexión.
