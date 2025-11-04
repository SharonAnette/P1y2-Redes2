# Sockets TCP – Conexiones Bloqueantes

Este proyecto implementa un sistema **cliente-servidor** en Python utilizando **sockets orientados a conexión (TCP)** en modo bloqueante.  
Forma parte de la materia **Aplicaciones para Comunicaciones en Red (ESCOM-IPN)**.

---

## Objetivo
Comprender e implementar **sockets orientados a conexiones bloqueantes** dentro de un entorno cliente-servidor, asegurando una comunicación confiable y ordenada entre ambas partes mediante el protocolo **TCP**.

---

## Descripción
El proyecto consta de dos programas en Python:
- **Servidor**: escucha conexiones en el puerto 8080, recibe mensajes y los muestra.
- **Cliente**: se conecta al servidor, envía un mensaje y cierra la conexión.

Ambos operan en modo bloqueante (`setblocking(True)`), garantizando que cada operación (conexión, envío, recepción) se complete antes de continuar la ejecución.

---

## Ejecución

### Servidor
```python
python servidor.py
