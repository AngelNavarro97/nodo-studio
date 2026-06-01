# N®Std. — Sistema de reservas

Prototipo visual del sistema de reservas y panel de gestión de **NODO Studio**,
clínica de fisioterapia ubicada en Murcia.

## Contenido

- **`index.html`** — Sitio público de reservas para pacientes
  (selección de servicio, calendario, hora y datos personales).
- **`admin.html`** — Panel interno de gestión:
  - Citas (lista por día, filtros por estado y servicio)
  - Calendario mensual con bloqueos de días y franjas
  - Fichas de pacientes con tratamiento, fotos de progreso, sesiones y bono
  - Login con email y contraseña
- **`RECURSOS/`** — Activos de marca (logotipo).

## Cómo abrirlo

Abre `index.html` o `admin.html` directamente en cualquier navegador
moderno (Safari, Chrome, Firefox). No necesita servidor ni instalación.

### Credenciales demo del panel admin

- **Email:** `isa@nstd.es`
- **Contraseña:** `nstd2026`

> Aviso: esto es un prototipo visual. Las reservas, citas, fichas y
> bloqueos se guardan únicamente en memoria del navegador y se reinician
> al recargar la página.

## Diseño

- Monocromo (blanco / negro / grises) fiel al logotipo N®Std.
- Tipografías: **Mona Sans** y **JetBrains Mono**.
- Estética inspirada en Apple (Liquid Glass en la barra de navegación
  móvil, animaciones suaves, gradientes sutiles, burbujas en el fondo).
- Optimizado para iPhone con barra inferior fija de 4 pestañas.

## Próximos pasos

Fase 2 contemplará:

- Persistencia real con base de datos.
- Autenticación segura.
- Recordatorios automáticos por email / WhatsApp.
- Sincronización con calendario externo.
- Gestión multi-usuario (administradora, fisioterapeutas, recepción).
