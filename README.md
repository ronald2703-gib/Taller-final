# 🦜 Alas de Colombia - Expo 2026

¡Bienvenido al repositorio oficial de **Alas de Colombia**! Este proyecto es una plataforma web interactiva diseñada para la simulación de un ecosistema digital dedicado al avistamiento, catalogación y conservación de la majestuosa avifauna colombiana. 

Desarrollado como entrega práctica para el **Taller 4**, el sitio adopta un estilo visual **tropical oscuro** —combinando fondos negros profundos, textos grises de alta legibilidad y acentos verde selva— construido bajo estrictos estándares de accesibilidad, rendimiento y diseño responsivo.

---

## 🛠️ Requerimientos Técnicos Implementados

*   **Framework**: Implementación limpia de **Bootstrap 5 (vía CDN)**. El único script cargado en el proyecto es `bootstrap.bundle.min.js`.
*   **Iconografía**: Uso exclusivo de **Bootstrap Icons** para enriquecer las interfaces visuales.
*   **Navegación**: Todos los archivos HTML están completamente interconectados para simular una experiencia de usuario fluida (desde la Landing Page pública hasta los módulos privados).
*   **Accesibilidad (Lighthouse)**: Código optimizado para cumplir con relaciones de contraste adecuadas, objetivos táctiles móviles de tamaño óptimo (`padding` integrado) y uso correcto de puntos de referencia estructurales (`<main>`, `<nav>`).

---

## 📂 Estructura del Proyecto

El encarpetado del proyecto se organiza de la siguiente manera:

```text
taller4/
│
├── index.html          # Landing Page (Presentación oficial del evento)
├── README.md           # Documentación del proyecto (Este archivo)
│
└── app/                # Módulos internos de la plataforma
    ├── login.html      # Formulario de inicio de sesión (Floating labels)
    ├── record.html   # Formulario de inscripción en cuadrícula
    ├── recover.html  # Recuperación de contraseña con validación estática
    ├── admin.html      # Dashboard Administrativo (Métricas, tablas y modales)
    └── customer.html    # Dashboard de Expositor (Alertas, perfiles y pestañas)



💻 Componentes por Página
Parte A: Sitio Público (index.html)
Navbar Sticky (fixed-top): Barra de navegación superior fija con un menú hamburguesa colapsable en pantallas pequeñas.

Hero / Carrusel: Un componente interactivo que expone las especies insignia (Cóndor, Tucán, Colibrí) con texto superpuesto (carousel-caption) y botones de acción.

Tarjetas de Información: Secciones organizadas con el sistema Grid (container, row, col-md-4) utilizando componentes card para los pilares de conservación.

Footer: Un pie de página estructurado en columnas bajo la clase bg-dark.

Parte B: Módulo de Autenticación (app/)
Inicio de Sesión (login.html): Uso de etiquetas flotantes (form-floating), casillas de verificación y un botón adaptado al ancho completo (w-100).

Registro (registro.html): Formulario extenso organizado mediante cuadrículas simétricas (row, col-md-6).

Recuperación (recuperar.html): Demostración visual de manejo de errores utilizando clases nativas de validación (is-invalid e invalid-feedback).

Parte C: Paneles de Control (app/)
Dashboard Administrativo (admin.html):

Layout con barra lateral izquierda (sidebar) responsiva.

Tarjetas superiores con métricas clave destacadas mediante componentes badge.

Tabla de participantes responsiva con estados contextuales (bg-success, bg-warning) y botones de acción pequeños (btn-sm).

Formulario de actualización de datos incrustado en un componente Modal.

Dashboard de Cliente/Expositor (cliente.html):

Panel de perfil con el avatar del investigador estilizado en círculo (rounded-circle).

Sistema interactivo de pestañas dinámicas (nav-tabs) para alternar entre inscripciones.

Componente de alerta descartable (alert-dismissible) configurado de manera nativa.

🚀 Despliegue
El proyecto se encuentra desplegado en vivo y puede ser visualizado de manera interactiva a través de GitHub Pages en el siguiente enlace:

🔗 [Inserta aquí el enlace que te dé GitHub Pages]

Desarrollado en 2026 para fines académicos siguiendo los lineamientos de diseño web responsivo y accesibilidad digital.


