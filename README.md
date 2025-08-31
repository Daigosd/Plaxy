# 🚀 Exploración Espacial - Aplicación Web

Una aplicación web moderna y interactiva sobre exploración espacial, la NASA y los planetas del sistema solar.

## ✨ Características

- **Diseño Responsivo**: Optimizado para dispositivos móviles y de escritorio
- **Animaciones Suaves**: Utiliza Framer Motion para transiciones fluidas
- **Componentes UI Modernos**: Basado en Radix UI y Tailwind CSS
- **Navegación Intuitiva**: Menú de navegación con scroll suave
- **Información Educativa**: Datos detallados sobre planetas y la NASA
- **Sistema de Notificaciones**: Toast notifications para interacciones

## 🛠️ Tecnologías Utilizadas

- **Frontend**: React 18 + Vite
- **Estilos**: Tailwind CSS + PostCSS
- **Componentes**: Radix UI
- **Animaciones**: Framer Motion
- **Iconos**: Lucide React
- **Metadatos**: React Helmet

## 📋 Requisitos Previos

- **Node.js**: Versión 16 o superior
- **npm**: Gestor de paquetes de Node.js

## 🚀 Instalación

1. **Clonar el repositorio:**
   ```bash
   git clone <url-del-repositorio>
   cd appfinal
   ```

2. **Instalar dependencias:**
   ```bash
   npm install
   ```

3. **Ejecutar en modo desarrollo:**
   ```bash
   npm run dev
   ```

4. **Construir para producción:**
   ```bash
   npm run build
   ```

5. **Vista previa de producción:**
   ```bash
   npm run preview
   ```

## 📁 Estructura del Proyecto

```
appfinal/
├── src/
│   ├── components/
│   │   └── ui/
│   │       ├── button.jsx          # Componente de botón reutilizable
│   │       ├── toast.jsx           # Componente de notificación
│   │       ├── toaster.jsx         # Contenedor de notificaciones
│   │       ├── use-toast.jsx       # Hook para notificaciones
│   │       └── data/
│   │           └── planets.js      # Datos de los planetas
│   ├── lib/
│   │   ├── main.jsx               # Punto de entrada de React
│   │   └── utils.js               # Utilidades y funciones helper
│   ├── App.jsx                    # Componente principal de la aplicación
│   └── index.css                  # Estilos globales y Tailwind
├── index.html                     # Archivo HTML principal
├── package.json                   # Dependencias y scripts
├── vite.config.js                 # Configuración de Vite
├── tailwind.config.js             # Configuración de Tailwind CSS
└── postcss.config.js              # Configuración de PostCSS
```

## 🎯 Funcionalidades

### Secciones Principales
1. **Inicio**: Hero section con llamada a la acción
2. **NASA**: Información sobre la agencia espacial
3. **Planetas**: Datos detallados de cada planeta del sistema solar

### Características Interactivas
- Navegación con scroll suave
- Menú móvil responsive
- Notificaciones toast
- Animaciones de entrada y hover
- Diseño glassmorphism

## 🔧 Configuración

### Alias de Importación
El proyecto utiliza alias de importación configurados en `vite.config.js`:
- `@/` apunta a `./src/`

### Tailwind CSS
Configurado con:
- Modo oscuro automático
- Animaciones personalizadas
- Colores CSS variables
- Plugin de animaciones

## 📱 Responsive Design

- **Mobile First**: Diseño optimizado para dispositivos móviles
- **Breakpoints**: Adaptable a tablets y escritorio
- **Touch Friendly**: Interacciones optimizadas para pantallas táctiles

## 🚀 Despliegue

### Hosting Estático
La aplicación se puede desplegar en cualquier servicio de hosting estático:
- Netlify
- Vercel
- GitHub Pages
- AWS S3

### Comando de Construcción
```bash
npm run build
```

## 🐛 Solución de Problemas

### Error de Importación
Si encuentras errores de importación, verifica:
1. Que Node.js esté instalado correctamente
2. Que las dependencias estén instaladas (`npm install`)
3. Que el archivo `vite.config.js` esté presente

### Problemas de Estilos
Si los estilos no se cargan:
1. Verifica que Tailwind CSS esté configurado
2. Asegúrate de que `index.css` esté importado en `main.jsx`

## 📄 Licencia

Este proyecto está bajo la Licencia MIT.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:
1. Fork el proyecto
2. Crea una rama para tu feature
3. Commit tus cambios
4. Push a la rama
5. Abre un Pull Request

## 📞 Soporte

Para soporte técnico o preguntas, por favor abre un issue en el repositorio.
