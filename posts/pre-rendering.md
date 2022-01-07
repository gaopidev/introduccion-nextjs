---
title: "Dos formas de Pre-renderizado"
date: "2022-01-06"
---

Next.js tiene dos formas de pre-renderizado: **Generación estática** y **Renderizado en servidor**. La diferencia está en **cuando** se genera el HTML de una pagina

- **Generacion estatica** es el metodo de pre-renderizado que genera el HTML en **tiempo de construccion**. El HTML pre-renderizado es _reutilizado_ en cada peticion.
- **Renderizado en servidor** es el metodo de pre-renderizado que genera el HTML en **cada peticion**.

Importante, Next.js te permite **elegir** cual forma de pre-renderizado usa para cada pagina. Tu puedes crear una aplicacion de Next.js **hibrida** usando generacion estatica para la mayoria de las paginas y usando renderizado en servidor para otras.
