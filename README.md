# Propuesta E-Commerce Shopify 2.0 • Melinda's Makeup (@melindas_makeup\_)

Esta es una **propuesta web interactiva y prototipo funcional de e-commerce** diseñada especialmente para **Melinda's Makeup** (Cali, Colombia). Incluye arquitectura de escalabilidad en Shopify 2.0, catálogo de productos, configurador interactivo de Ramos de Maquillaje, calculadora de retorno de inversión (ROI) y una experiencia visual inmersiva con una **paleta de sombras 3D que se abre y acciona al hacer scroll (trigger on scroll)**.

## 🚀 Despliegue Inmediato en GitHub Pages (Deploy from a branch)

Este proyecto está empaquetado en un único archivo estático de alto rendimiento (`index.html`) sin dependencias de compilación (`zero build steps`), listo para desplegarse gratis en **GitHub Pages**:

### Paso 1: Subir a GitHub

Abre tu terminal en la carpeta donde tengas este proyecto y ejecuta:

```
# 1. Inicializar repositorio Git y añadir archivos
git init
git add .
git commit -m "feat: propuesta e-commerce Shopify para Melinda's Makeup"
git branch -M main

# 2. Vincular a tu repositorio en GitHub (crea uno nuevo en github.com/new)
git remote add origin https://github.com/TU-USUARIO/melindas-makeup-ecommerce.git

# 3. Subir los cambios
git push -u origin main

```

### Paso 2: Activar GitHub Pages en el Repositorio

1. Ingresa a tu repositorio en GitHub: `https://github.com/TU-USUARIO/melindas-makeup-ecommerce`.

2. Haz clic en la pestaña **Settings** (Configuración) en la barra superior.

3. En el menú lateral izquierdo, haz clic en **Pages**.

4. En la sección **Build and deployment**:

   * **Source**: Selecciona `Deploy from a branch`.

   * **Branch**: Selecciona `main` y en la carpeta mantén `/(root)`.

   * Haz clic en el botón **Save**.

5. ¡Listo! En menos de 60 segundos tu sitio web estará disponible públicamente en:

   `https://TU-USUARIO.github.io/melindas-makeup-ecommerce/`

## ✨ Características de la Propuesta

1. **Paleta de Maquillaje 3D (Trigger on Scroll)**:

   * Mecanismo en CSS 3D Transforms que abre la tapa imantada de la paleta conforme el usuario se desplaza por la sección.

   * Reflejo realista en el espejo interior con inscripción de marca.

   * 12 tonos de sombras con acabados Mate Terciopelo, Shimmer Metálico y Glitter Prensado inspirados en Cali y el Valle del Cauca.

   * Probador dinámico de swatches sobre diferentes tonos de piel (Clara, Canela, Morena y Ébano) con información de fórmula y códigos HEX.

2. **Catálogo E-Commerce & Carrito Interactivo**:

   * Filtros por categorías: *Ramos de Maquillaje*, *Paletas & Ojos*, *Labios & Rostro*, *Boxes & Kits*.

   * Carrito de compras deslizante (Slide Cart Drawer) con barra de progreso para **Envío Gratis en Colombia** (meta: \$150.000 COP).

   * Modal de simulación de Checkout One-Page de Shopify con integración para pasarelas colombianas.

3. **Configurador de Ramos de Maquillaje (Ramo Builder)**:

   * Personalizador guiado en 3 pasos: tamaño (Petit, Deluxe, Imperial), envoltura de papel luxury y complementos (luces LED, chocolates Ferrero, dedicatoria personalizada).

   * Cálculo dinámico de precios y añadido directo al carrito.

4. **Arquitectura Tecnológica Shopify 2.0**:

   * **Pasarelas de Pago:** Wompi (Nequi, Bancolombia), PSE, Addi (Compre ahora y pague a 3 cuotas con 0% interés) y tarjetas de crédito.

   * **Logística:** Integración con Coordinadora, Envía, Inter Rapidísimo y mensajería urbana express para entregas el mismo día en Cali.

   * **Omnicanalidad:** Conexión con Instagram Shopping (`@melindas_makeup_`) y Meta Conversions API.

   * **Retención:** Flujos de Klaviyo y notificaciones transaccionales vía WhatsApp.

5. **Calculadora Financiera de ROI**:

   * Proyecciones interactivas de ventas mensuales basadas en tráfico de Instagram, tasa de conversión estimada y ticket promedio (AOV).

   * Estimación de horas humanas ahorradas en atención manual de chats de WhatsApp.

6. **Roadmap de 4 Semanas**:

   * Plan detallado para pasar del diseño al lanzamiento oficial de la tienda online en 30 días calendario.