# XpertAuth Association - Sistema de Gestión de Transportes Especiales

## Overview

XpertAuth Association es una plataforma web especializada en la gestión de permisos y servicios para transporte especial en Catalunya. El sistema proporciona servicios de consultoría, tramitación de permisos, coordinación de acompañamientos policiales, gestión de seguros especializados y formación en herramientas de inteligencia artificial. La aplicación está orientada a transportistas, empresas de transporte especial y profesionales del sector que necesitan navegar el complejo marco regulatorio del transporte de cargas especiales.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Tecnología Base**: HTML5 estático con CSS3 y JavaScript ES6+ moderno
- **Diseño**: Arquitectura multi-página con navegación unificada y diseño responsive
- **Sistema de Estilos**: CSS personalizado con variables y grid layouts responsivos
- **Tipografía**: Google Fonts (Poppins) para consistencia visual
- **Estructura de Páginas**: 
  - Página principal (index.html) con secciones ancla
  - Páginas de servicios especializadas en subdirectorio /pages/servicios/
  - Páginas legales en subdirectorio /legales/
  - Página de contacto independiente

### Backend Architecture
- **Almacenamiento**: Supabase como backend-as-a-service
- **Base de Datos**: PostgreSQL gestionada por Supabase
- **Autenticación**: No implementada (sitio público informativo)
- **API**: Supabase REST API para operaciones CRUD
- **Tablas Principales**: `contactos` para almacenar formularios de contacto

### Gestión de Formularios
- **Validación**: Validación client-side con JavaScript nativo
- **Procesamiento**: Envío asíncrono mediante fetch API
- **Seguridad**: Hash SHA-256 para identificadores únicos
- **UX**: Mensajes de éxito/error dinámicos y estados de loading

### Estructura de Contenido
- **SEO**: Optimización completa con meta tags, Open Graph y Schema.org
- **Accesibilidad**: Navegación semántica y estructura ARIA
- **Multiidioma**: Configurado para español con soporte futuro para otros idiomas
- **Contenido Especializado**: Información técnica sobre regulaciones de transporte especial en Catalunya

### Optimización y Performance
- **Carga de Assets**: CSS y JavaScript optimizados para carga rápida
- **Imágenes**: Optimización responsive con lazy loading implícito
- **Navegación**: Sistema de breadcrumbs y navegación contextual
- **Mobile-First**: Diseño completamente responsive con breakpoints optimizados

## External Dependencies

### Backend Services
- **Supabase**: PostgreSQL database hosting y REST API
  - URL: https://gpanqnyxmzpbnlixcttw.supabase.co
  - Gestión de formularios de contacto
  - Almacenamiento de datos empresariales

### Frontend Libraries
- **Google Fonts**: Poppins font family para tipografía consistente
- **Supabase JavaScript Client**: Librería ESM para interacción con backend

### Third-Party Integrations
- **Google**: Fuentes web y potencial integración con servicios de mapas
- **Schema.org**: Structured data para SEO empresarial
- **Open Graph**: Integración con redes sociales

### Domain-Specific Services
- **Organismos Gubernamentales**: Integración informativa con DGT, SCT y Mossos d'Esquadra
- **Sector Transporte**: Referencias a normativas catalanas y españolas de transporte especial
- **Herramientas IA**: Documentación de integración con herramientas como ChatGPT, Claude, etc.