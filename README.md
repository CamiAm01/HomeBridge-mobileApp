# HomeBridge Mobile App 🏡📱
### Información del Proyecto
La aplicación móvil de **HomeBridge** contiene todas las características, funcionalidades, opciones, herramientas, artefactos, y muchísimo más, cuyo objetivo principal es facilitar la compra, venta y alquiler de inmuebles. Con **SaleSquare**, los usuarios pueden explorar una amplia variedad de propiedades, obtener recomendaciones personalizadas, y conectarse directamente con propietarios o agentes inmobiliarios. Además, la aplicación ofrece herramientas de calculadora financiera para evaluar económicamente una posible compra a corto o largo plazo.

### Segmento Objetivo
Nuestra aplicación está dirigida a personas entre 25 y 55 años, de cualquier género, que residan en áreas urbanas de Perú y estén en busca de una propiedad para comprar, vender o alquilar. SaleSquare es ideal para quienes desean una herramienta sencilla y eficiente para gestionar operaciones inmobiliarias, así como para aquellos que buscan invertir o encontrar su nuevo hogar.

### 🛠 Tecnologías Utilizadas
La aplicación está desarrollada con las siguientes tecnologías y librerías:
- **Lenguaje:** Kotlin
- **Arquitectura:** MVVM (Model-View-ViewModel)
- **Persistencia de Datos:** Room Database
- **Networking:** Retrofit & OkHttp (conectado a backend en Azure)
- **UI & Diseño:** Material Components, ConstraintLayout, Image Carousel
- **Servicios de Google:** Google Maps SDK & Location Services

### 🚀 Características Principales
- **Gestión de Propiedades:** Los usuarios pueden publicar nuevas propiedades, editarlas y gestionar sus anuncios existentes.
- **Búsqueda Inteligente:** Filtros avanzados para encontrar la propiedad ideal según ubicación, precio y tipo.
- **Calculadora Financiera:** Herramienta para evaluar la viabilidad económica de compras de inmuebles.
- **Mapas Interactivos:** Visualización de la ubicación exacta de las propiedades.
- **Perfil de Usuario:** Gestión de información personal y configuración de cuenta.

### 📁 Estructura del Proyecto
- `ui/`: Actividades y fragmentos de la interfaz de usuario.
- `network/`: Definición de servicios API y configuración de Retrofit.
- `db/`: Configuración de la base de datos local Room.
- `models/`: Clases de datos utilizadas en toda la aplicación.
- `adapters/`: Adaptadores para RecyclerViews.

### ⚙️ Instalación y Configuración
1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/CamiAm01/homebridge-mobileApp.git
   ```
2. **Abrir en Android Studio:**
   Selecciona la carpeta `App_SaleSquare_HomeBridge`.
3. **Sincronizar Gradle:**
   Asegúrate de tener una conexión a internet para descargar las dependencias necesarias.
4. **Ejecutar:**
   Selecciona un emulador o dispositivo físico con Android SDK 28 o superior.

---

## 👥 Autores

| Nombre |
|--------|
| Amaro Villanueva, Camila Elena | 
| Cuadros Rodriguez, Juan Alejandro | 
| Huilca Chipana, Gustavo |
| Mallma Quispe, Ruben Elias |
| Paredes Zapata, Luiggi Gianfranco |
| Shimabukuro Uku, Carlos Joel |

Curso: Aplicaciones para Dispositivos Móviles
Docente: David Gerardo Quevedo Velasco
UPC — Noviembre 2024

¡Descubre tu próxima propiedad con HomeBridge!
