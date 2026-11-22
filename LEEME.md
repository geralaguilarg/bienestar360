# Bienestar 360° — App personal gratuita (PWA)

Esta es la primera versión funcional de tu dashboard de bienestar. No necesita Firebase, tarjeta ni suscripción. Los registros se guardan únicamente en el almacenamiento local del navegador/dispositivo; no hay sincronización automática entre dispositivos.

## Funcionalidades
- Dashboard con gráficas de cumplimiento diario, distribución por categoría, hidratación semanal.
- Registro rápido de agua en cantidades de 200, 300, 500 y 750 ml o personalizado, con historial de consumos.
- Checklists por fecha: facial AM/PM, capilar, corporal, salud íntima, suplementos, CrossFit, fortalecimiento de tobillo y Bridal Arms.
- Métricas: pasos, sueño, minutos de entrenamiento, dolor, olor íntimo, energía y peso opcional.
- Seguimiento Bridal Arms de 8 semanas (23 nov 2026–17 ene 2027).
- Exportación/importación de registros JSON y resumen semanal copiable para ChatGPT.
- PWA instalable en el iPhone una vez publicada por HTTPS.

## Probar en el computador
Abre `index.html` en un navegador. Para probar funciones de instalación PWA y uso sin conexión, usa un servidor local o publica en HTTPS. Por ejemplo, si tienes Python:

```sh
cd bienestar360_app
python3 -m http.server 8080
```

Después visita http://localhost:8080.

## Publicar gratis en GitHub Pages
1. Crea un repositorio **privado o público según tus preferencias**. Importante: para cuentas gratuitas, GitHub Pages suele requerir un repositorio público; el código de la app no contiene tus registros personales. Verifica los requisitos actuales de GitHub Pages antes de elegir visibilidad.
2. Sube los archivos de esta carpeta a la raíz del repositorio.
3. En GitHub abre Settings → Pages → Build and deployment → Deploy from a branch; selecciona `main` y `/ (root)`; guarda.
4. Cuando GitHub te muestre la URL HTTPS, ábrela en Safari en el iPhone.
5. En Safari: Compartir → Añadir a pantalla de inicio → Añadir.

Alternativa: Firebase Hosting con plan Spark (gratuito dentro de cuotas). No activaremos facturación.

## Privacidad
- La app NO envía información a servidores; el navegador almacena los datos localmente en `localStorage`.
- Los datos de bienestar y salud son sensibles. Usa un dispositivo personal protegido; evita compartir copias de seguridad.
- Exporta una copia semanal desde Ajustes → Descargar copia JSON. Conserva el archivo de manera segura.
- Borrar datos del navegador o reinstalar puede eliminar tus registros. Una instalación en iPhone y una sesión en computador NO comparten datos automáticamente.
- La primera versión NO envía notificaciones push; el recordatorio diario de ChatGPT a las 9 p. m. es independiente.

## Precauciones de salud
La app sirve para seguimiento, no diagnóstico ni tratamiento. El olor genital fuerte parecido a pescado (5/5) merece evaluación clínica pronto. No utilizar PanOxyl en vulva o vagina. Los suplementos necesitan revisar indicaciones y dosis; los retinoides se deben evitar en embarazo o búsqueda de embarazo; el regreso a CrossFit tras el esguince debe ser progresivo.


## Actualización v1.1 — Hair oiling

Los lavados de cabello están programados lunes, miércoles y sábado. El hair oiling se marca en el checklist de las noches anteriores: domingo, martes y viernes. Usar una pequeña cantidad de jojoba de medios a puntas; evitar el cuero cabelludo si hay sensibilidad o tendencia a acumular grasa. Si dejarlo toda la noche causa irritación o apelmazamiento, usar aceite 20–30 minutos antes del lavado en su lugar.


## Versión 1.2 — icono
Nuevo icono flor de loto lila. Antes de eliminar/reinstalar la app en iPhone, exporta una copia de seguridad desde Ajustes. Eliminar la app puede borrar datos locales. Actualiza todos los archivos en GitHub, incluida la caché sw.js.
