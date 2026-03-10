# 🍺 Bizarro Dive Bar - Sistema de Control de Gastos

> Aplicación web profesional para el control y gestión de gastos del **Bizarro Dive Bar**

## 📋 Descripción

Sistema completo de control de gastos diseñado específicamente para el **Bizarro Dive Bar**, con diseño negro/blanco elegante, acentos dorados (#F5C518), logo oficial integrado y funcionalidad profesional para la gestión financiera de un bar.

## ✨ Características Principales

### 🎨 Diseño Visual
- **Logo Oficial**: Logo real del Bizarro Dive Bar integrado
- **Tema Negro Profundo**: Fondo negro #0A0A0A
- **Acentos Dorados**: Color distintivo #F5C518
- **Interfaz Moderna**: Diseño limpio y profesional
- **100% Responsive**: Funciona en móviles, tablets y computadoras
- **PWA**: Instalable como aplicación en celular

### 🔐 Autenticación y Roles
- **3 Niveles de Acceso**:
  - 👑 **Admin** (`admin` / `admin123`): Acceso total
  - ✏️ **Capturista** (`capturista` / `cap123`): Registrar y consultar
  - 👁️ **Consulta** (`consulta` / `cons123`): Solo lectura

### 💰 Módulos Funcionales

#### 1. **Dashboard Principal**
- 4 KPIs en tiempo real:
  - Total gastos del mes
  - Gastos fijos mensuales
  - Nómina del mes
  - Compras del mes
- 4 Gráficas Chart.js:
  - Tendencia mensual (últimos 6 meses)
  - Distribución por categoría (dona)
  - Métodos de pago (pastel)
  - Comparativo mensual (barras)
- Tabla de gastos recientes (Top 10)

#### 2. **Gestión de Gastos**
- CRUD completo
- Filtros avanzados:
  - Búsqueda por texto
  - Por categoría
  - Por método de pago
  - Por mes
- Paginación de resultados
- Badges de colores por estado
- Categorías:
  - Bebidas
  - Alimentos
  - Servicios
  - Gasto Fijo
  - Nómina
  - Operativo
  - Permisos
  - Mantenimiento
  - Otros

#### 3. **Proveedores** (20 Proveedores Reales)
- Sam's Club
- Vino al Mar
- Grupo Modelo
- Cerveza Yudy
- La Escocesa
- Don Juan Empaques
- Gaspasa
- Gasolina
- Megacable
- CFE (Comisión Federal de Electricidad)
- Jumapan (Agua)
- Recolección de Basura
- Extensión Horario (Permiso)
- Alcoholes
- Los Canastos
- Agua Embotellada
- Hielo
- Piso (Limpieza)
- Carne Garatte
- Tecate

**Funcionalidad**:
- CRUD completo
- Búsqueda por nombre, contacto, categoría
- Estados: Activo/Inactivo
- Opción para agregar proveedores manualmente

#### 4. **Gastos Fijos Mensuales** (10 Gastos Precargados)
- Renta del Local ($25,000)
- CFE - Luz ($4,500)
- Agua - Jumapan ($800)
- Gas ($1,200)
- Internet - Megacable ($699)
- Recolección de Basura ($350)
- Extensión de Horario ($3,000)
- Licencia de Alcohol ($2,500)
- Seguro del Local ($1,800)
- Mantenimiento Preventivo ($1,500)

**Total Mensual**: $41,349

#### 5. **Gestión de Empleados** (10 Empleados Precargados)
- Gerente General
- Bartender Jefe
- Bartender
- Mesera/Mesero (2)
- Cajera
- Cocinero
- Ayudante de Cocina
- Seguridad
- Limpieza

**Información**:
- Puesto y salario
- Teléfono de contacto
- Antigüedad en meses
- Fecha de ingreso
- Estado activo/inactivo

#### 6. **Control de Nómina**
- Registro de pagos mensuales
- Cálculo automático:
  - Salario base (cargado del empleado)
  - Bonos
  - Deducciones
  - Total a pagar
- Filtros por empleado y período
- Historial completo de pagos
- 30 pagos precargados (3 meses × 10 empleados)

#### 7. **Control de Préstamos a Empleados**
- Registro de préstamos
- Sistema de pagos parciales
- Barra de progreso visual
- Cálculo automático de saldo
- Estados: Activo/Pagado
- Resumen con 4 métricas:
  - Préstamos activos
  - Total prestado
  - Total pagado
  - Saldo pendiente
- 4 préstamos de ejemplo (2 activos, 2 pagados)

#### 8. **Reportes y Estadísticas**
- **6 Tabs de Reportes**:
  1. Resumen General
  2. Por Categoría
  3. Por Proveedor
  4. Por Método de Pago
  5. Tendencia (últimos 6 meses)
  6. Top 10 Gastos
- Filtros por período (cualquier mes)
- Gráficas dinámicas
- **Exportación Profesional**:
  - 📗 **Excel** (.xlsx) con SheetJS
  - 📕 **PDF** con jsPDF + AutoTable

#### 9. **Configuración**
- Información del negocio editable
- Lista de categorías del sistema
- Gestión de datos:
  - Exportar todos los datos (JSON)
  - Cargar datos demo
  - Limpiar todos los datos
- Estadísticas del sistema

## 📊 Datos Precargados

### Resumen de Datos Demo
- **50 Gastos** de 3 meses (Diciembre 2025, Enero y Febrero 2026)
- **20 Proveedores** reales del bar
- **10 Empleados** con diferentes puestos
- **10 Gastos Fijos** mensuales
- **30 Pagos de Nómina** (3 meses completos)
- **4 Préstamos** a empleados con historial de pagos

**Total de gastos demo**: ~$400,000 MXN en 3 meses

## 🛠️ Tecnologías Utilizadas

### Core
- **HTML5** - Estructura semántica
- **CSS3** - Variables CSS, Flexbox, Grid
- **JavaScript ES6+** - Lógica moderna

### Librerías (CDN)
- **Chart.js 4.4.0** - Gráficas profesionales
- **Font Awesome 6.5.1** - Iconografía
- **Google Fonts (Inter + Montserrat)** - Tipografía
- **SheetJS (xlsx)** - Exportación Excel
- **jsPDF + AutoTable** - Generación de PDFs

### Almacenamiento
- **LocalStorage** - Persistencia de datos en navegador
- Sin necesidad de backend ni base de datos

## 🚀 Instalación y Uso

### Método 1: Uso Directo
1. Abre `index.html` en cualquier navegador moderno
2. Inicia sesión con usuario demo:
   - 👑 Admin: `admin` / `admin123`
   - ✏️ Capturista: `capturista` / `cap123`
   - 👁️ Consulta: `consulta` / `cons123`
3. ¡Empieza a usar el sistema!

### Método 2: Instalar como PWA (en celular)
1. Abre la aplicación en navegador móvil
2. Busca opción "Agregar a pantalla de inicio"
3. Instala la app
4. Accede desde tu pantalla de inicio como app nativa

## 📱 Responsive Design

| Dispositivo | Resolución | Características |
|-------------|-----------|----------------|
| **Desktop** | > 1024px | Vista completa con sidebar fijo |
| **Tablet** | 768-1024px | Adaptación de grids, sidebar colapsable |
| **Móvil** | < 768px | Sidebar deslizable, diseño en columna |

## 🎨 Paleta de Colores

```css
/* Colores Principales */
--color-black: #0A0A0A        /* Negro profundo */
--color-dark-gray: #1A1A1A    /* Gris oscuro */
--color-white: #FFFFFF        /* Blanco puro */

/* Acento Dorado */
--color-gold: #F5C518         /* Dorado distintivo */
--color-gold-dark: #D4A017    /* Dorado oscuro */

/* Estados */
--color-success: #10B981      /* Verde éxito */
--color-warning: #F59E0B      /* Naranja alerta */
--color-danger: #EF4444       /* Rojo error */
--color-info: #3B82F6         /* Azul info */
```

## 📂 Estructura de Archivos

```
bizarro-dive-bar/
├── index.html                 (63.6 KB) ✅
├── manifest.json              (1.0 KB) ✅ PWA
├── css/
│   └── style.css              (28.8 KB) ✅
├── js/
│   ├── data.js                (30.6 KB) ✅ Datos demo
│   └── app.js                 (95.2 KB) ✅ Lógica completa
└── README.md                  (Este archivo)

Total: ~220 KB de código limpio y documentado
```

## ⚙️ Funcionalidades Técnicas

### Sistema de Permisos (RBAC)

| Acción | Admin | Capturista | Consulta |
|--------|:-----:|:----------:|:--------:|
| Ver Dashboard | ✅ | ✅ | ✅ |
| Crear Gastos | ✅ | ✅ | ❌ |
| Editar Gastos | ✅ | ✅ | ❌ |
| Eliminar Gastos | ✅ | ❌ | ❌ |
| Gestionar Proveedores | ✅ | ✅ | ❌ |
| Gestionar Empleados | ✅ | ✅ | ❌ |
| Ver Nómina | ✅ | ✅ | ✅ |
| Gestionar Nómina | ✅ | ❌ | ❌ |
| Gestionar Préstamos | ✅ | ❌ | ❌ |
| Ver Reportes | ✅ | ✅ | ✅ |
| Exportar Excel/PDF | ✅ | ❌ | ❌ |
| Configuración | ✅ | ❌ | ❌ |

### Persistencia de Datos

Todos los datos se guardan automáticamente en **LocalStorage**:

| Clave | Descripción |
|-------|-------------|
| `currentUser` | Sesión del usuario actual |
| `usuarios` | Lista de usuarios del sistema |
| `gastos` | Todos los gastos registrados |
| `proveedores` | Catálogo de proveedores |
| `empleados` | Lista de empleados |
| `gastosFijos` | Gastos fijos mensuales |
| `nomina` | Historial de pagos de nómina |
| `prestamos` | Préstamos a empleados |
| `categorias` | Categorías de gastos |
| `negocio` | Información del negocio |

## 📈 Gráficas Disponibles

### Dashboard
1. **Tendencia Mensual** (Línea) - Últimos 6 meses
2. **Distribución por Categoría** (Dona) - Mes actual
3. **Métodos de Pago** (Pastel) - Mes actual
4. **Comparativo Mensual** (Barras) - Por categoría

### Reportes
5. **Distribución por Categoría** (Dona) - Período seleccionado
6. **Métodos de Pago** (Pastel) - Período seleccionado
7. **Tendencia de Gastos** (Línea) - Últimos 6 meses

**Total**: 7 gráficas interactivas con Chart.js

## 🎯 Casos de Uso

### 1. Registrar Compra a Proveedor
```
Admin/Capturista → Gastos → Nuevo Gasto
→ Fecha, Concepto, Monto, Categoría (Bebidas/Alimentos)
→ Proveedor (ej: Sam's Club)
→ Método de Pago (Transferencia/Tarjeta/Efectivo)
→ Guardar
```

### 2. Pagar Servicios Mensuales
```
Admin → Gastos Fijos → Verificar listado
→ Gastos → Nuevo Gasto
→ Concepto (CFE, Agua, Internet, etc.)
→ Categoría (Gasto Fijo)
→ Guardar
```

### 3. Procesar Nómina Mensual
```
Admin → Nómina → Registrar Pago
→ Seleccionar Empleado (carga salario automáticamente)
→ Período (mes actual)
→ Bonos y Deducciones
→ Total calculado automáticamente
→ Guardar
```

### 4. Otorgar Préstamo a Empleado
```
Admin → Préstamos → Nuevo Préstamo
→ Seleccionar Empleado
→ Monto del préstamo
→ Concepto (opcional)
→ Guardar
→ Luego: Registrar Abonos parciales
```

### 5. Generar Reporte Mensual
```
Todos los usuarios → Reportes
→ Seleccionar Período (mes)
→ Ver 6 tabs de reportes diferentes
→ Admin puede Exportar Excel o PDF
```

## 💾 Gestión de Datos

### Exportar Datos (Backup)
```
Admin → Configuración → Datos
→ "Exportar Todos los Datos (JSON)"
→ Descarga archivo .json con todos los datos
```

### Cargar Datos Demo
```
Admin → Configuración → Datos
→ "Cargar Datos Demo"
→ Confirmar (reemplaza datos actuales)
```

### Limpiar Datos
```
Admin → Configuración → Datos
→ "Limpiar Todos los Datos"
→ Doble confirmación (acción irreversible)
```

## 🔒 Seguridad

- ✅ Autenticación con usuario y contraseña
- ✅ Sesión persistente en LocalStorage
- ✅ Validación de permisos por rol
- ✅ Datos cifrados en LocalStorage del navegador
- ✅ Sin conexión a internet necesaria (máxima privacidad)
- ✅ Auditoría automática (usuario que creó cada registro)

## 🌐 Compatibilidad

### Navegadores Soportados
- ✅ Chrome/Edge 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Opera 76+

### Sistemas Operativos
- ✅ Windows 10/11
- ✅ macOS Big Sur+
- ✅ Linux (Ubuntu, Fedora, etc.)
- ✅ iOS 14+
- ✅ Android 8+

## 📖 Guía Rápida de Uso

### Para Administradores

1. **Configurar el Negocio**
   - Ir a Configuración
   - Actualizar nombre, RFC, dirección, teléfono
   - Guardar cambios

2. **Gestionar Proveedores**
   - Verificar los 20 proveedores precargados
   - Agregar nuevos proveedores si es necesario
   - Editar datos de contacto

3. **Revisar Gastos Fijos**
   - Verificar los 10 gastos fijos precargados
   - Ajustar montos si es necesario
   - Agregar nuevos gastos fijos

4. **Gestionar Empleados**
   - Verificar los 10 empleados precargados
   - Agregar nuevos empleados
   - Actualizar salarios

5. **Monitorear Dashboard**
   - Revisar diariamente las 4 métricas principales
   - Analizar gráficas de tendencia
   - Revisar gastos recientes

6. **Procesar Nómina**
   - A fin de mes: Ir a Nómina
   - Registrar pago para cada empleado
   - Agregar bonos y deducciones

7. **Generar Reportes**
   - Semanalmente: Revisar reportes del mes
   - Mensualmente: Exportar Excel y PDF para contabilidad
   - Comparar con meses anteriores

### Para Capturistas

1. **Registrar Gastos Diarios**
   - Ir a Gastos → Nuevo Gasto
   - Completar todos los campos
   - Guardar

2. **Actualizar Información**
   - Editar gastos propios si hay error
   - Consultar proveedores disponibles

3. **Consultar Reportes**
   - Ver reportes del mes actual
   - Analizar gastos por categoría

### Para Usuarios de Consulta

1. **Ver Dashboard**
   - Revisar métricas del mes
   - Analizar gráficas

2. **Consultar Gastos**
   - Buscar gastos específicos
   - Filtrar por categoría o fecha

3. **Ver Reportes**
   - Revisar todos los tipos de reportes
   - Analizar tendencias

## ❓ Preguntas Frecuentes (FAQ)

### ¿Los datos se guardan en la nube?
Los datos se guardan en **LocalStorage** del navegador, en tu dispositivo local. No se envían a ningún servidor externo, garantizando máxima privacidad.

### ¿Puedo acceder desde varios dispositivos?
Cada dispositivo mantiene sus propios datos. Para sincronizar, puedes exportar los datos en un dispositivo e importarlos en otro.

### ¿Qué pasa si borro el caché del navegador?
Los datos en LocalStorage se perderán. Por eso es importante hacer backups periódicos usando "Exportar Todos los Datos".

### ¿Cómo instalo la app en mi celular?
Abre `index.html` en el navegador móvil, busca la opción "Agregar a pantalla de inicio" y confirma. La app se instalará como una aplicación nativa.

### ¿Puedo personalizar las categorías?
Las 9 categorías precargadas están optimizadas para bares. Para modificarlas, edita el archivo `js/data.js`.

### ¿Los 20 proveedores son editables?
Sí, puedes:
- Editar los 20 proveedores precargados
- Agregar nuevos proveedores manualmente
- Desactivar proveedores que ya no uses

### ¿Cuánto espacio ocupa la aplicación?
La aplicación completa ocupa ~220 KB. Los datos que generes dependerán de tu uso, típicamente:
- 1,000 gastos ≈ 500 KB
- 10,000 gastos ≈ 5 MB

## 🎁 Ventajas Clave

1. **Sin instalación** - Solo abrir el archivo HTML
2. **Sin costos** - 100% gratuito, sin suscripciones
3. **Sin internet** - Funciona offline después de carga inicial
4. **Privacidad total** - Datos solo en tu dispositivo
5. **Responsive** - Funciona en todos los dispositivos
6. **Profesional** - Calidad empresarial
7. **Completo** - 9 módulos funcionales
8. **Personalizable** - Adaptable a tu negocio

## 🔄 Actualizaciones Futuras Sugeridas

- [ ] Sincronización en la nube (Supabase/Firebase)
- [ ] Notificaciones push para gastos fijos
- [ ] OCR para leer comprobantes automáticamente
- [ ] Predictive analytics con IA
- [ ] Múltiples sucursales
- [ ] API REST para integraciones
- [ ] Modo oscuro/claro toggle
- [ ] Más tipos de gráficas
- [ ] Dashboard personalizable

## 📧 Soporte

Para soporte o personalizaciones adicionales, contactar al desarrollador.

## 📄 Licencia

Este proyecto fue creado específicamente para **Bizarro Dive Bar**. Todos los derechos reservados.

---

## 🎊 ¡Aplicación Lista!

**Bizarro Dive Bar** ahora tiene un sistema profesional para controlar sus gastos, gestionar proveedores, procesar nómina y generar reportes detallados.

✨ **¡Éxito en tu negocio!** 🍺
