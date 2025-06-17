# 🏪 Mi Tiendita - Gestión de Inventario para Abarrotes

Una aplicación móvil desarrollada en Kotlin para la gestión eficiente de inventario y ventas en tiendas de abarrotes pequeñas y medianas.

## 📱 Descripción

**Mi Tiendita** es una solución digital diseñada específicamente para automatizar la gestión de inventario en tiendas de abarrotes como "Abarrotes El Sol". La aplicación permite el control en tiempo real del stock, registro de ventas, y generación de reportes, eliminando los procesos manuales y reduciendo errores operativos.

## 🎯 Objetivos

### Objetivo General
Desarrollar una aplicación móvil en Kotlin que permita la gestión de inventario y ventas mediante un sistema de autenticación seguro y una interfaz intuitiva, automatizando el control de stock y mejorando la precisión de los datos.

### Objetivos Específicos
- ✅ Sistema de autenticación seguro con roles (Administrador/Empleado)
- ✅ Gestión completa de productos (CRUD)
- ✅ Sistema de búsqueda y filtrado por categorías
- ✅ Control de existencias en tiempo real
- ✅ Alertas automáticas de bajo stock
- ✅ Generación de reportes de inventario
- ✅ Almacenamiento optimizado de imágenes

## 🚀 Características Principales

### 🔐 Autenticación y Roles
- **Administrador**: CRUD completo, gestión de usuarios, reportes avanzados
- **Empleado**: Consulta de inventario, registro de ventas, reportes básicos
- Recuperación de contraseñas vía email
- Encriptación con bcrypt

### 📦 Gestión de Inventario
- Registro de productos con imagen, precio, cantidad y categoría
- Búsqueda rápida por nombre
- Control de entradas y salidas
- Alertas automáticas cuando stock ≤ 5 unidades (o 4kg)

### 📊 Reportes y Analytics
- Inventario actual
- Productos con bajo stock
- Historial de movimientos
- Productos más vendidos

### 🛡️ Seguridad
- Base de datos encriptada con SQLCipher
- Control de acceso basado en roles
- Respaldos automáticos
- Registro de cambios y auditoría

## 🛠️ Stack Tecnológico

- **Lenguaje**: Kotlin
- **IDE**: Android Studio
- **Base de Datos**: Room (SQLite) / Firebase Cloud Firestore
- **Autenticación**: bcrypt para hash de contraseñas
- **Seguridad**: SQLCipher para encriptación de BD
- **Almacenamiento**: Local + Cloud (opcional)
- **Compatibilidad**: Android 8.0 (API 26) o superior

## 📋 Requisitos del Sistema

### Mínimos
- Android 8.0 (Oreo) o superior
- 2GB RAM
- 500MB espacio libre
- Conexión a internet (opcional para sincronización)

### Recomendados
- Android 10.0 o superior
- 4GB RAM
- 1GB espacio libre
- Conexión estable a internet

## 🏗️ Arquitectura del Proyecto

```
Mi Tiendita/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/mitiendita/
│   │   │   │   ├── ui/
│   │   │   │   ├── data/
│   │   │   │   ├── domain/
│   │   │   │   └── utils/
│   │   │   ├── res/
│   │   │   └── AndroidManifest.xml
│   │   └── test/
│   └── build.gradle
└── README.md
```

## 🔧 Instalación y Configuración

### Prerrequisitos
```bash
# Verificar versión de Java
java -version # Requiere Java 8 o superior

# Instalar Android Studio
# Descargar desde: https://developer.android.com/studio
```

### Clonar el Repositorio
```bash
git clone https://github.com/equipo4pm/Programaci-n-M-vil.git
```

### Configuración del Proyecto
1. Abrir Android Studio
2. Seleccionar "Open an Existing Project"
3. Navegar a la carpeta del proyecto
4. Esperar a que Gradle sincronice las dependencias


## 🗂️ Estructura de la Base de Datos

### Tablas Principales
- **users**: Información de usuarios y roles
- **products**: Catálogo de productos
- **categories**: Categorías de productos
- **inventory_movements**: Historial de entradas/salidas
- **sales**: Registro de ventas

## 📊 Roadmap

### ✅ Fase 1 - MVP (Completado)
- [x] Sistema de autenticación
- [x] CRUD de productos
- [x] Inventario básico

### 🔄 Fase 2 - En Desarrollo
- [ ] Sistema de reportes avanzados
- [ ] Alertas push
- [ ] Sincronización en la nube

### 📋 Fase 3 - Planeado
- [ ] Integración con códigos de barras
- [ ] Módulo de proveedores
- [ ] App para múltiples sucursales

## 🤝 Contribución

### Equipo de Desarrollo
- **Diego Alejandro Bustamante Serdio**
- **Alison Michell Castillo Alonso**
- **Emanuel Anthuan García Cervantes**
- **Cristian Eduardo Morales Solís**
- **Luis Angel Vázquez García**

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE.md](LICENSE.md) para más detalles.

### Documentación
- [Wiki del Proyecto](https://github.com/equipo4pm/Programaci-n-M-vil/wiki)
- [Guía de Usuario](https://drive.google.com/file/d/1OAv71khycREFz0AfSkPfPdqjUXbSdzIR/view?usp=sharing)

## 🙏 Agradecimientos

- **Instituto Politécnico Nacional - UPIICSA**
- **Profesor**: Gustavo Martínez Vázquez
- **Abarrotes Axel** - Por brindar información sobre el negocio

---

**📈 Estadísticas del Proyecto**
- **Líneas de código**: ~5,000
- **Cobertura de tests**: 85%
- **Tiempo de desarrollo**: 4 meses
- **Versión actual**: 1.0.0

---
