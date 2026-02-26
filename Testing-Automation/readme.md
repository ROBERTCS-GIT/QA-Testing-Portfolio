#  Automatización de Pruebas de API (Postman)

En este proyecto paso de las pruebas manuales a la automatización básica utilizando **Postman**.

## ¿Por qué automatizar esta prueba?
Validar que un servidor responda (Status 200) es una tarea repetitiva. Al escribir un script, 
permito que el sistema verifique la salud del servicio de forma instantánea sin intervención manual.

## Detalles de la prueba
- **Herramienta:** Postman.
- **Método:** GET.
- **Endpoint:** `https://jsonplaceholder.typicode.com/todos/1`
- **Script de validación (JavaScript):**
```javascript
pm.test("El código de estado es 200", function () {
    pm.response.to.have.status(200);
});
