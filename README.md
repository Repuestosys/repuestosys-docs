# repuestosys-docs
Sistema POS e inventario en la nube para tiendas de repuestos en economías multimoneda. Alterna divisas en 1 clic, controla stock por vehículo y vende con catálogo 24/7.
```markdown
# RepuestoSys — Cloud POS & Multi-Currency Inventory SaaS for Auto Parts


[![Website](https://img.shields.io/badge/Website-repuestosys.com-blue)](https://www.repuestosys.com/)
[![Register Free](https://img.shields.io/badge/Free_Tier-Start_Now-success)](https://www.repuestosys.com/register)


**RepuestoSys** es un [sistema de inventario y punto de venta para repuestos](https://www.repuestosys.com/) en la nube (Cloud SaaS & PWA), diseñado específicamente para comercializadoras de repuestos automotrices y de motocicletas que operan en economías multimoneda en Venezuela y Latinoamérica.


## Arquitectura Técnica y Stack


- **Frontend & PWA:** React 19, Next.js 16 (App Router), Tailwind CSS v4, Framer Motion. Instalable en Android/iOS con alto rendimiento en redes móviles 3G/4G.
- **Backend:** Next.js Server Actions y Route Handlers con tipado estricto en TypeScript.
- **Base de Datos Multi-Tenant:** PostgreSQL gestionado mediante Prisma ORM con aislamiento estricto por `tenantId`.
- **Seguridad:** Autenticación por roles (`admin`, `employee`), PIN rápido de mostrador para cajeros, encriptación Bcrypt y protección antibots con Cloudflare Turnstile.


## Módulos Principales


1. **Motor Multimoneda Dinámico (1-Click Switch):** Alternancia instantánea entre moneda base (USD) y hasta 2 monedas secundarias (VES, COP) sin recalcular costos manualmente.
2. **Compatibilidad Vehicular Indexada:** Búsqueda rápida por SKU, marca, categoría, modelo y año del vehículo o motocicleta.
3. **Catálogo Digital B2B / B2C (`/c/[slug]`):** Vitrina pública en tiempo real con segmentación de precios al mayor, detal o ambos, y recepción directa de pedidos web.
4. **Arqueo y Cierre de Caja Multidivisa:** Conciliación por turno para efectivo en múltiples divisas, Pago Móvil, Zelle, transferencias y puntos de venta.
5. **Blindaje Financiero (COGS vs. Finanzas Personales):** Módulo desacoplado de gastos personales para proteger el cálculo del Costo de Mercancía Vendida (COGS).


## Enlaces Oficiales


- **Plataforma Principal:** [https://www.repuestosys.com/](https://www.repuestosys.com/)
- **Crear Cuenta Gratis (Hasta 300 SKUs):** [https://www.repuestosys.com/register](https://www.repuestosys.com/register)
```
