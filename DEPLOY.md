# Guía rápida de despliegue

## Local

```bash
php -S localhost:8000
```

Abrir:

```text
http://localhost:8000
```

## XAMPP / Laragon / WAMP

1. Copia la carpeta del proyecto dentro de `htdocs` o `www`.
2. Inicia Apache.
3. Abre `http://localhost/ERP_Comercial_GitHub_Ready`.

## Hosting compartido

1. Sube todos los archivos.
2. Verifica PHP 8+.
3. Verifica SQLite habilitado.
4. Da permisos de escritura a `data/`.
5. Abre el sitio.

## GitHub Pages

No compatible con PHP/SQLite.
Para GitHub Pages se necesitaría una versión estática usando `localStorage` o `IndexedDB`.
