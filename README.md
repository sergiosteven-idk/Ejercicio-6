# 🎥 Cámaras Profesionales - E-commerce

Tienda online especializada en equipos fotográficos profesionales con implementación de imágenes responsive.

## 📌 Características técnicas

1. **Imágenes optimizadas**:
   - Producto 1: Art Direction con `<picture>` (cuadrada en móvil/rectangular en desktop)
   - Producto 2: `srcset` + `sizes` con múltiples resoluciones
   - Producto 3: WebP + JPEG fallback
   - Producto 4: Background image responsive

2. **Performance**:
   - Lazy loading en todas las imágenes
   - `decoding="async"` para mejor rendimiento
   - `aspect-ratio` para evitar layout shift

3. **Diseño fluido**:
   - Tipografía con `clamp()`
   - Espaciado adaptable
   - Grid responsive automático

## 🖥️ Breakpoints

| Dispositivo       | Columnas | Ancho mínimo |
|-------------------|----------|--------------|
| Móvil             | 1        | 280px        |
| Tablet            | 2        | 768px        |
| Desktop           | 3        | 1024px       |
| Pantallas grandes | 4        | 1440px       |

## 🛒 Productos incluidos

1. Cámara DSLR Pro 24MP
2. Lente 70-200mm f/2.8
3. Flash TTL Profesional
4. Protector de lente

## 📝 Cómo personalizar

1. Reemplaza las imágenes en `srcset` por tus propias fotos
2. Modifica los colores en las variables CSS
3. Añade más productos duplicando la estructura de tarjeta
