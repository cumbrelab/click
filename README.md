# Click – Centro de negocios · Sitio web

Sitio estático de Click (Otavalo, Ecuador): landing principal y una página por propiedad, enlazadas entre sí.

## Estructura

```
index.html                         Landing principal (todo incluido en un solo archivo)
favicon.svg                        Ícono de la pestaña
propiedades/
  casa-atuntaqui/index.html        Casa en Atuntaqui
  casa-quichinche/index.html       Casa de campo en Quichinche
  terreno-lomatica/index.html      Terreno en Lomatica
  */img/                           Fotos de cada propiedad
```

## Publicar

1. Sube esta carpeta completa a un repositorio de GitHub (la raíz del repositorio debe ser esta carpeta).
2. En Vercel: Add New → Project → importa el repositorio → Framework preset: **Other** → Deploy. No necesita comando de build.
3. Las páginas quedan en `/propiedades/casa-atuntaqui/`, `/propiedades/casa-quichinche/` y `/propiedades/terreno-lomatica/`.

También funciona con GitHub Pages (Settings → Pages → rama `main`, carpeta raíz).

## Agregar una propiedad

Copia una carpeta de `propiedades/`, cambia textos y fotos, y añade la tarjeta en la landing.
