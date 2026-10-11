# 🎬 CINEFLIX

**CINEFLIX** es una aplicación web ligera que permite buscar una película simultáneamente en múltiples sitios de streaming y descarga. Al introducir un título, la app abre automáticamente todas las páginas de búsqueda configuradas, ahorrándote tiempo y clics.

Empaquetada como aplicación de escritorio y móvil con **[PakePlus](https://pakeplus.com/)**, funciona en Windows, macOS, Linux, Android e iOS sin necesidad de instalar entornos de desarrollo.

---

## ✨ Características

- 🔍 **Búsqueda múltiple simultánea:** Introduce un título y la app abrirá todas las páginas configuradas con 1 segundo de diferencia entre cada una (para evitar el bloqueo de pop-ups).
- ⚙️ **Gestor de páginas personalizable:**
  - Añade nuevas páginas de búsqueda.
  - Elimina las que ya no funcionen.
  - Restaura la lista original con un solo clic.
- 📄 **Historial de búsquedas:** Guarda las últimas 5 búsquedas con fecha y hora (almacenado en `localStorage`).
- 📺 **Accesos rápidos a TV en vivo:**
  - Pluto TV
  - Plex TV
  - Canela TV
- ⚽ **Acceso directo a deportes:** Botón a Fútbol Libre Full HD.
- ☕ **Botón de donación:** Enlace directo a PayPal para invitar un café.
- 💾 **Persistencia:** Toda la configuración (páginas e historial) se guarda localmente en el dispositivo.

---

## 🚀 Uso

1. Abre la aplicación CINEFLIX (versión web o ejecutable).
2. Escribe el título de la película en el campo de búsqueda.
3. Presiona **Enter** o pulsa el botón **BUSCAR**.
4. Se abrirán automáticamente todas las páginas de búsqueda configuradas en pestañas nuevas.

> ⚠️ **Nota sobre ventanas emergentes:**  
> La primera vez que uses la app, el navegador (o el WebView del ejecutable) puede bloquear las pestañas adicionales. Si aparece un aviso, permite las ventanas emergentes para este sitio. A partir de ahí, funcionará sin problemas.

---

## ⚙️ Configuración de Páginas de Búsqueda

Pulsa el botón de **engranaje (⚙️)** en la esquina superior derecha para abrir el gestor de páginas:

- **Añadir una página:** Rellena el nombre y la URL. La URL debe contener una **X** que será reemplazada por el título buscado.
  - Ejemplo: `https://misitio.com/search/X`
- **Eliminar una página:** Pulsa el botón rojo **✕** junto al nombre.
- **Restaurar por defecto:** Vuelve a la lista original de 8 páginas.

### Páginas incluidas por defecto

| Nombre | URL base |
| :--- | :--- |
| TioPlus | `https://tioplus.app/search/X` |
| CineCalidad | `https://www.cinecalidad.my/?s=X` |
| EliteTorrent | `https://www.elitetorrent.com/?s=X` |
| PelisPanda | `https://pelispanda.org/search/?query=X` |
| PelicineHD | `https://pelicinehd.com/?s=X` |
| EstrenosCinesAA | `https://www.estrenoscinesaa.com/?s=X` |
| VerPeliculasUltra | `https://verpeliculasultra.com/index.php?do=search&subaction=search&story=X` |
| OfficialMovieBox | `https://officialmoviebox.com/newWeb/searchResult?keyword=X` |

---

## 🛠️ Tecnologías Utilizadas

- **HTML5** – Estructura de la interfaz.
- **CSS3** – Estilos, diseño responsivo y animaciones.
- **JavaScript (Vanilla)** – Lógica de búsqueda, gestión de configuración e historial.
- **localStorage** – Persistencia de datos en el dispositivo.

No requiere frameworks ni dependencias externas. Todo está contenido en un único archivo HTML.

## ⚠️ Descargo de Responsabilidad

CINEFLIX **no aloja ni distribuye contenido**. Es únicamente un buscador que abre páginas de terceros. El uso que se haga de los sitios enlazados es responsabilidad exclusiva del usuario. Respeta siempre las leyes de propiedad intelectual de tu país.

---

Hecho con ❤️ para quienes aman el cine.
