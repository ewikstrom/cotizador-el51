# Cotizador El 51 de Princesa

Cotizador de carta para uso interno.

## Estructura

```
index.html    → la app completa
Dockerfile    → build con nginx
fly.toml      → configuración de Fly.io
```

## Deploy en Fly.io

1. Conecta este repositorio en Fly.io
2. Fly detecta el `Dockerfile` automáticamente
3. Cada push a `main` redespliega la app

## Actualizar la carta

Edita `index.html` — el array `MENU` al final del archivo contiene todos los platos y precios.
