# 🥩 Carnicería Premium - Cortes Supremos

Plataforma de e-commerce para una carnicería argentina con PWA, panel de administración, integración con WhatsApp y estadísticas de ventas.

## ✨ Características

### 📱 Progressive Web App (PWA)
- ✅ Descargable como app nativa en celulares
- ✅ Funciona sin conexión a internet
- ✅ Icono personalizado en pantalla de inicio
- ✅ Optimizado para todos los dispositivos

### 🛒 Sistema de Compras
- 21 cortes argentinos diferentes
- Selección de cantidad en kg y gramos (100 gr mínimo)
- Filtrado por categorías
- Carrito persistente
- Descuentos por producto
- Compra mínima: 3 kg o $30.000

### 👨‍💼 Panel Administrador
**Acceso:** 5 clicks rápidos en el logo → Contraseña: `corte2026`

- ✏️ Editar productos (nombre, precio, descuento, imagen, costo)
- ➕ Agregar nuevos productos
- ❌ Eliminar productos
- 🚫 Marcar como "Sin Stock" (oculta sin eliminar)
- 💰 Campo de "Precio Costo" (opcional)
- 📊 Estadísticas de ventas filtradas por día, semana y mes
- 💵 Cálculo automático de ganancia neta

### 📊 Reportes y Estadísticas
- Ventas totales por período
- Costo total de productos vendidos
- Ganancia neta calculada automáticamente
- Resumen diario para enviar al vendedor

### 📱 Integración WhatsApp
- Pedidos se envían a: **+54 9 11 2348-4720**
- Resumen diario se envía a: **+54 9 11 1668-8111**
- Detalles completos del pedido con cantidades y precios

## 🚀 Cómo instalar como app

### iPhone (Safari)
1. Abre el sitio en Safari
2. Presiona el botón "Compartir"
3. Selecciona "Añadir a pantalla de inicio"

### Android (Chrome)
1. Abre el sitio en Chrome
2. Presiona el menú (⋮)
3. Selecciona "Instalar app"

## 📁 Estructura del proyecto

```
.
├── index.html          # App principal con HTML, CSS y JS
├── manifest.json       # Configuración de PWA
├── sw.js              # Service Worker para caché offline
├── cortesupremo.png   # Logo de la carnicería
└── README.md          # Este archivo
```

## 💾 Almacenamiento de datos

Los datos se guardan localmente en el navegador usando `localStorage`:
- `products` - Lista de productos
- `dailyOrders_[DATE]` - Pedidos del día

**Nota:** Los datos se guardan solo en el navegador del usuario. Para un sistema de producción, se recomienda usar una base de datos backend.

## 🛠️ Tecnologías utilizadas

- HTML5
- CSS3 (Responsive Design, Grid, Flexbox)
- JavaScript Vanilla (sin frameworks)
- PWA (Progressive Web App)
- Service Workers
- localStorage API

## 📝 Licencia

Proyecto privado - Carnicería Premium

## 👤 Autor

Rodrigo Arena - rodrigo.n.arena@hotmail.com

---

**Última actualización:** Mayo 2026
