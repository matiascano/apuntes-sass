# 🎨 Hablemos de Sass

Una guía interactiva y completa sobre Sass (Syntactically Awesome Style Sheets) con ejemplos.

![Sass Logo](./assets/img/logoSass.svg)

## 📋 Descripción

**Hablemos de Sass** es una página web educativa que explica los conceptos fundamentales de Sass de manera clara y práctica. Ideal para desarrolladores que quieren aprender o repasar los conceptos básicos del preprocesador CSS más popular.

## ✨ Características

- 📚 **Guía completa**: Desde instalación hasta conceptos avanzados
- 💻 **Ejemplos de código**: Código Sass junto con su resultado CSS
- 🎯 **Navegación fluida**: Scroll automático y navegación sticky
- 📱 **Diseño responsivo**: Optimizado para todos los dispositivos
- 🎨 **Interfaz moderna**: Diseñada con Tailwind CSS

## 📖 Contenido

La guía cubre los siguientes temas de Sass:

### 🔧 Conceptos Básicos
- **Instalación**: Cómo instalar y configurar Sass
- **Compilación**: Proceso de transformación a CSS

### 🎯 Características Principales
1. **Variables**: Almacenamiento de valores reutilizables
2. **Anidamiento (Nesting)**: Organización jerárquica de selectores
3. **Mixins**: Bloques de código reutilizables con parámetros
4. **Funciones**: Cálculos personalizados y operaciones dinámicas
5. **Partials & Import**: Modularización del código
6. **Extend/Herencia**: Reutilización de estilos sin duplicación

### 🔄 Control de Flujo
7. **@each**: Iteración sobre listas para generar estilos dinámicos
8. **@for**: Bucles numéricos para patrones escalables
9. **@if/@else**: Estilos condicionales y lógica de decisión

## 🚀 Instalación y Uso

### Prerrequisitos
- Node.js instalado en tu sistema
- Navegador web moderno

### Instalación de Sass
```bash
# Instalación global
npm install -g sass

# O instalación local en el proyecto
npm install --save-dev sass
```

### Clonar el proyecto
```bash
git clone https://github.com/tu-usuario/hablemos-de-sass.git
cd hablemos-de-sass
```

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **Tailwind CSS**: Framework de utilidades CSS
- **JavaScript Vanilla**: Funcionalidad de navegación
- **Intersection Observer API**: Detección de secciones visibles

## 🎨 Características de Diseño

- **Colores personalizados**: 
  - Primary: `#CF649A` (Rosa)
  - Secondary: `#1F2937` (Gris oscuro)
- **Tipografía**: Fuentes del sistema optimizadas
- **Navegación sticky**: Menú fijo durante el scroll
- **Scroll suave**: Transiciones fluidas entre secciones
- **Resaltado activo**: Indicador visual de sección actual

## 📚 Ejemplos de Código

Cada concepto incluye:
- ✅ Código Sass original
- ✅ Resultado CSS compilado
- ✅ Explicación detallada
- ✅ Casos de uso recomendados

### Ejemplo: Variables
```scss
// Sass
$primary-color: #1daa7b;

.button {
  background-color: $primary-color;
}
```

```css
/* CSS compilado */
.button {
  background-color: #1daa7b;
}
```

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para contribuir:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/nueva-seccion`)
3. Commit tus cambios (`git commit -m 'Agregar nueva sección'`)
4. Push a la rama (`git push origin feature/nueva-seccion`)
5. Abre un Pull Request

### Tipos de contribución
- 📝 Mejoras en el contenido
- 🐛 Corrección de errores
- 🎨 Mejoras de diseño
- 📱 Optimizaciones responsive
- 🌐 Traduciones

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 👨‍💻 Autor

**Matías Cano**
- Website: [matiascano.com.ar](https://matiascano.com.ar)
- GitHub: [@tu-usuario](https://github.com/tu-usuario)

## 🙏 Agradecimientos

- [Sass Team](https://sass-lang.com/) por crear esta increíble herramienta
- [Tailwind CSS](https://tailwindcss.com/) por el framework de utilidades
- La comunidad de desarrolladores que hace posible estos recursos educativos

## 📈 Roadmap

- [ ] Agregar más ejemplos avanzados
- [ ] Incluir ejercicios interactivos
- [ ] Modo oscuro/claro
- [ ] Versión en inglés
- [ ] Integración con CodePen para ejemplos en vivo

---

⭐ Si este proyecto te resultó útil, ¡no olvides darle una estrella!

---