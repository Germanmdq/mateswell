# MATESWELL PWA

Tienda demostrativa instalable, con catálogo, carrito, pedido por WhatsApp y administración local.

## Ejecutar localmente

Desde esta carpeta, iniciar un servidor web estático, por ejemplo:

```powershell
py -m http.server 8080
```

Abrir `http://localhost:8080`. La aplicación se puede instalar desde el navegador compatible.

## Panel de demostración

Ir a **Administración** e ingresar `mateswell-demo`. Los datos de catálogo, carrito, pedidos y configuración se guardan solo en el navegador para pruebas.

## Producción

Completar `.env` desde `.env.example` y ejecutar `supabase-schema.sql` en un proyecto Supabase. No exponer nunca una clave de servicio en el frontend. Reemplazar la contraseña de demostración por Supabase Auth antes de publicar.

Antes de la publicación, configurar en el panel el número comercial de WhatsApp y reemplazar los productos/fotografías de demostración por los reales.
