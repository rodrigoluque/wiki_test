---
title: Introducción
description: documentación
published: true
date: 2021-09-01T14:38:44.526Z
tags: introducción
editor: markdown
dateCreated: 2021-09-01T12:59:35.516Z
---

El API de SimpliRoute es un conjunto de endpoints de tipo REST. Por lo mismo, nuestra API tiene un comportamiento predecible, orientado a recursos via URL, y usa códigos de respuesta HTTP para indicar las respuestas del sistema y errores. Utilizamos características propias de HTTP, como HTTP authentication y verbos HTTP que son entendidos de manera nativa por cualquier cliente HTTP moderno. Soportamos cross-origin resources, lo que permite interactura de manera segura con nuestra API desde tus aplicaciones web tanto como back-end como desde front-end. Igualmente, recomedamos que nunca expongas tu API Key en el código público de tu app en el lado del cliente. Todas las respuestas de nuestra API son de tipo JSON, incluyendo los errores que puedan existir.