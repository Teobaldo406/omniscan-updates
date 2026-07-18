# OmniScan Updates

Este repositorio publico se usa solo para publicar descargas de OmniScan.

## Uso correcto

- Subir solo archivos de distribucion en GitHub Releases.
- Usar nombres como `OmniScan_1.0.1.zip`.
- Copiar el enlace del asset del Release en Firestore como `update_url`.
- Guardar el SHA256 del ZIP en Firestore como `update_sha256`.

## No subir aqui

- Codigo fuente.
- Archivos `.py`.
- Claves o tokens.
- Configuracion local.
- Bases de datos.
- Logs, temporales o backups.

## Ejemplo de enlace

```text
https://github.com/Teobaldo406/omniscan-updates/releases/download/v1.0.1/OmniScan_1.0.1.zip
```

El codigo fuente principal debe mantenerse en el repositorio privado.
