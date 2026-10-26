# CYCLE360 AI — PWA starter

Esta carpeta contiene una aplicación web progresiva (PWA) instalable como punto de partida.

## Qué funciona ahora
- Interfaz adaptable a móvil y escritorio.
- Planificador semanal básico basado en reglas locales.
- Recomendaciones generales de nutrición.
- Catálogo de rutas ilustrativas (no son rutas GPS verificadas).
- Perfil, plan y rutas guardados en el almacenamiento local del navegador.
- Manifiesto PWA y service worker para caché/offline del shell de la aplicación.

## Qué NO está implementado aún
- Backend, cuentas reales ni sincronización entre dispositivos.
- Entrenador con modelo de IA conectado.
- GPS en segundo plano, navegación ni rutas verificadas.
- Integraciones con Garmin, Strava u otros servicios.
- Publicación en tiendas de aplicaciones.

## Publicar gratis con GitHub Pages
1. Crea una cuenta gratuita en GitHub si no tienes una.
2. Crea un repositorio nuevo, por ejemplo `cycle360-ai`.
3. Sube TODOS los archivos y carpetas de esta carpeta al repositorio (el `index.html` debe quedar en la raíz).
4. En el repositorio abre **Settings → Pages**.
5. En “Build and deployment”, selecciona **Deploy from a branch**, la rama `main` y la carpeta `/ (root)`, y guarda.
6. Espera a que GitHub Pages publique la web. La URL aparecerá en esa misma sección.
7. Abre esa URL con HTTPS en tu móvil u ordenador.

## Instalar
- Android/Chrome: abre la web publicada; usa el menú del navegador y elige “Instalar aplicación” o “Añadir a pantalla de inicio”.
- iPhone/iPad: abre la web en Safari → Compartir → “Añadir a pantalla de inicio”.
- Ordenador: abre la web en un navegador compatible y usa el icono de instalación de la barra de direcciones o el menú.

## Nota importante
El archivo HTML original puede abrirse localmente, pero la instalación PWA y el modo sin conexión requieren servirlo desde HTTPS o localhost. Los datos locales no se sincronizan entre dispositivos. No introduzcas información médica sensible. El planificador y la nutrición son orientativos, no sustituyen asesoramiento profesional.
