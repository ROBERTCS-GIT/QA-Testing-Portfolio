# 📋 Plan de Pruebas: Módulo de Pagos y Servicios (Telrad)
**Versión:** 1.0  
**Responsable:** Robert (QA Analyst)
## 1. Introducción
Este documento define la estrategia para validar el correcto funcionamiento del módulo de facturación y pagos. El objetivo es asegurar que la lógica de cobro y el cumplimiento de SLAs funcionen según los requisitos del negocio.
## 2. Alcance (¿Qué vamos a probar?)
* **Funcionalidades:** Login de usuario, consulta de deudas, procesamiento de pagos con tarjeta y generación de recibos.
* **No Funcionalidades:** Rendimiento del servidor bajo carga de 10,000 usuarios (fuera de alcance por ahora).
## 3. Estrategia de Pruebas
* **Pruebas Manuales:** Validación de la interfaz de usuario y flujos de navegación.
* **Pruebas de API:** Validación de respuestas del servidor mediante Postman (visto en la carpeta Testing-Automation).
* **Pruebas de Regresión:** Verificación de que los cambios nuevos no dañen lo que ya funcionaba.
## 4. Criterios de Aceptación (¿Cuándo está "OK"?)
- El sistema debe procesar un pago en menos de 3 segundos.
- No deben existir errores críticos (Blockers) pendientes de resolver.
- El 100% de los casos de prueba críticos deben haber pasado con éxito.
## 5. Entorno de Pruebas (Toolstack)
- **Gestión:** Herramientas ITSM (Experiencia en Gilat) y GitHub Issues.
- **Pruebas de API:** Postman.
- **Navegadores:** Chrome y Microsoft Edge.
