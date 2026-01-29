# 🐕 Peluquería Canina Pati-pet - Agenda Profesional

Una aplicación web progresiva (PWA) para la gestión de turnos en una peluquería canina. Funciona completamente offline y se puede instalar en el teléfono.

## ✨ Características

- 📅 **Gestión completa de turnos** con validación de fechas
- 👥 **Registro de clientes** y perritos
- 💰 **Estadísticas financieras** automáticas
- 📱 **Funciona offline** - todos los datos se guardan localmente
- 🔔 **Recordatorios por WhatsApp** integrados
- 🖨️ **Impresión y exportación** de datos
- 📊 **Vistas múltiples**: Mes, Semana y Día
- ⚠️ **Validación inteligente**: No permite turnos en fechas pasadas

## 🚀 Cómo usar

### Opción 1: Usar desde GitHub Pages
1. Visita: `https://[tu-usuario].github.io/Peluqueria-Pati-pet/`
2. Haz clic en "Instalar" cuando aparezca el banner
3. ¡Listo! La app está instalada en tu teléfono

### Opción 2: Instalar localmente
1. Descarga todos los archivos
2. Ábrelos en cualquier servidor web
3. Accede desde tu navegador

### Opción 3: GitHub Pages (Recomendado)
1. Haz fork de este repositorio
2. Ve a Settings > Pages
3. Selecciona la rama main como fuente
4. Guarda y accede a tu URL personalizada

## 📱 Instalación en el teléfono

1. **Desde Chrome/Edge (Android):**
   - Abre la app en el navegador
   - Toca el menú (tres puntos)
   - Selecciona "Instalar app" o "Añadir a pantalla de inicio"

2. **Desde Safari (iPhone):**
   - Abre la app en Safari
   - Toca el ícono de compartir
   - Desplázate y selecciona "Añadir a pantalla de inicio"

## 🔧 Funcionalidades principales

### ✅ Nuevo Turno
- Registro completo con teléfono y notas
- Validación automática de fechas futuras
- Métodos de pago: Efectivo, Mercado Pago, Transferencia

### 📊 Estadísticas
- Totales por día, semana, mes y año
- Desglose por método de pago
- Actualización automática

### 📱 Compartir
- Envío de recordatorios por WhatsApp
- Compartir turnos individuales
- Exportar todos los turnos del día

### 💾 Datos
- Guardado automático localmente
- Exportación a JSON para backup
- Carga automática al abrir la app

## 🛡️ Validaciones implementadas

1. **No se pueden agendar turnos en fechas pasadas**
   - El sistema bloquea fechas anteriores a la actual
   - Muestra advertencias claras
   - Permite ver pero no modificar turnos pasados

2. **Campos obligatorios**
   - Cliente, fecha/hora y servicio son requeridos
   - Validación en tiempo real

3. **Datos persistentes**
   - Todo se guarda en el navegador
   - Funciona sin conexión a internet

## 🎨 Diseño responsive

- Adaptado para móviles y tablets
- Navegación intuitiva con pestañas
- Iconos y colores consistentes
- Animaciones suaves

## 🗂️ Estructura de archivos

