# Amigo Secreto

Una aplicación web sencilla e interactiva para organizar el tradicional juego del "Amigo Secreto". Los usuarios pueden agregar nombres de participantes, listar a los amigos, y realizar el sorteo de manera automática. Esta herramienta es ideal para reuniones, celebraciones y eventos donde se desea sortear un amigo secreto de forma rápida y divertida.

## Características
- **Agregar participantes:** Permite agregar nombres de amigos al listado.
- **Visualizar lista:** Muestra una lista de los nombres ingresados.
- **Sortear amigo secreto:** Selecciona al azar un amigo de la lista y lo muestra como resultado.
- **Diseño intuitivo:** Interfaz amigable y fácil de usar, ideal para cualquier tipo de usuario.

## Tecnologías utilizadas
- **HTML5:** Estructura del contenido.
- **CSS3:** Diseño y estilos, incluyendo fuentes de Google Fonts.
- **JavaScript:** Lógica para la gestión de nombres y el sorteo aleatorio.

## Estructura del proyecto
El proyecto consta de los siguientes archivos:

### 1. **index.html**
Archivo principal que contiene la estructura HTML de la aplicación:
- Encabezado con el título y una imagen representativa.
- Sección para ingresar nombres, visualizar la lista de amigos y sortear un participante.
- Botón interactivo para realizar el sorteo.

### 2. **app.js**
Archivo JavaScript con la lógica del proyecto:
- **Variables:**
  ```javascript
  let amigos = [];
  const lista = document.querySelector("#listaAmigos");
  ```
  - `amigos`: Array que almacena los nombres ingresados.
  - `lista`: Referencia al elemento HTML donde se muestran los nombres.

- **Funciones principales:**
  - `agregarAmigo()`: Agrega un nombre al array `amigos` y actualiza la lista en pantalla.
  - `mostrarAmigos()`: Renderiza los nombres de la lista en el DOM.
  - `sortearAmigo()`: Selecciona aleatoriamente un nombre de la lista y lo muestra como resultado.

### 3. **style.css**
Archivo de estilos que define el diseño visual de la aplicación

### 4. **assets/**
Carpeta que contiene recursos como imágenes e íconos utilizados en la aplicación.

## Uso
1. **Clona este repositorio:**
   ```bash
   git clone https://github.com/usuario/amigo-secreto.git
   ```
2. **Abre el archivo `index.html` en tu navegador.**
3. **Interacción:**
   - Ingresa los nombres de los participantes.
   - Haz clic en "Añadir" para agregarlos a la lista.
   - Cuando estés listo, haz clic en "Sortear amigo" para obtener un resultado.

## Capturas de pantalla
### Pantalla principal
![Pantalla principal de Amigo Secreto](assets/amigo-secreto.png)

## Mejoras futuras
- Permitir exportar la lista de participantes en formato de texto o archivo.
- Implementar la opción para guardar el sorteo y enviarlo por correo electrónico.
- Mejorar la experiencia de usuario con animaciones y efectos visuales.

## Contribuciones
Las contribuciones son bienvenidas. Si deseas colaborar:
1. Realiza un fork del repositorio.
2. Crea una nueva rama para tus cambios:
   ```bash
   git checkout -b feature/nueva-funcionalidad
   ```
3. Realiza un pull request con tus cambios.

## Autor
**Juan Dolmus Corea**  
Puedes contactarme en: [jbautista.dormo.corea@gmail.com]



