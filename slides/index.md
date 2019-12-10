---
theme: uncover
---

# Descentralizando la Web

---

### Martín Acosta
#### `@tinchoz49`
#### Trabajo en `Geut`.

![bg right w:50%](./images/martin.png)

---

![bg left w:50%](./images/geut.png)

### Desarrollamos aplicaciones y módulos sobre tecnologías P2P.

---

# Agenda

- Contexto
- Qué es `Dat`?
- Compartir y descargar con `Dat CLI`
- Crear una web descentralizada con `Beaker`
- Dat Awesome

---

# dat://contexto

---

![](./images/dropbox.png)

---

![](./images/drop-fb-1.png)

---

![bg w:40%](./images/drop-fb-2.png)

---

![bg left](./images/top-one.png)

## Decisión de negocio

---

![bg w:15%](./story/decent-Page-12.png)

---

![bg w:40%](./story/decent-Page-8.png)

---

![bg w:40%](./story/decent-Page-2.png)

---

![bg w:50%](./story/decent-Page-1.png)

---

# BitTorrent

---

![](./images/torrent.png)

---

![](./images/popcorn.png)

---

![bg w:30%](./images/dat-logo.png)

---

# Varias cosas

---

# Un protocolo P2P

#### Diseñado para la sincronización eficiente de grandes volumenes de datos.

---

> Parecido a BitTorrent pero con mejoras.

---

## Qué mejoras?

- Optimizado para la modificación y acceso de la información.
- Encriptación de datos.

---

## Un conjunto de modulos

> Todo desarrollado en JavaScript

![bg left w:90%](./images/stack.png)

---

# Un CLI

![bg right w:90%](./images/cli-share.gif)

---

# Una comunidad

###### https://dat.foundation
###### https://comm-comm.datproject.org

![bg right w:70%](./images/community.png)

---

# dat://cli

`Dat CLI` nos permite **compartir** o **descargar**
directorios/archivos :open_file_folder: de nuestro sistema
con otrxs :heart:.

---

![bg w:50%](./story/decent-Page-9.png)

---

![bg w:50%](./story/decent-Page-11.png)

---

![bg w:50%](./story/decent-Page-10.png)

---

![bg w:50%](./story/decent-Page-3.png)

---

![bg w:50%](./story/decent-Page-4.png)

---

![bg w:50%](./story/decent-Page-5.png)

---

![bg w:50%](./story/decent-Page-6.png)

---

![bg w:50%](./story/decent-Page-7.png)

---

![bg right w:80%](./images/beaker.png)

# Beaker

Browser diseñado para explorar y construir una web P2P.

---

> Construido utilizando los modulos que componen a **Dat**.

---

![bg w:50%](./story/decent-Page-13.png)

---

![bg w:50%](./story/decent-Page-14.png)

---

# Beaker API

### DatArchive

```javascript
var mySite = await DatArchive.create({title: 'My site'});
mySite.url // dat://1277b9...
await mySite.writeFile('index.html', 'Hello, world!');
```

---

# dat://awesome

---

### Cabal

https://cabal.chat

![bg left w:90%](./images/desktop.png)

---

![bg w:20%](./images/geut.png)

---

![w:200](./images/libscie.png)

### P2PCommons SDK (ese dk)

https://github.com/p2pcommons/sdk-js

The peer-to-peer commons is all about creating, remixing, and sharing.

---

![w:300](./images/wireline.svg)
![w:200](./images/dxos.png)

Biblioteca de módulos open source para el desarrollo de aplicaciones P2P en `JavaScript`.

---

![bg w:70%](./images/demo.gif)

---

![bg left w:70%](./images/aaron.png)

> Sólo aquellos que están cegados por la codicia se negarían a hacerle una copia a un amigue.

---

# Gracias

@tinchoz49

---
