# Pruebas de Interfaz (UI) y Usabilidad - Módulo de RQ- Pagos(PAYONE)

**Objetivo:** Verificar que la interfaz sea intuitiva y no induzca al error del usuario final.

### Hallazgos de Usabilidad:
1. **Contraste de Botones:** El botón de "Cancelar" tiene el mismo color que el de "Confirmar Pago". 
   * **Riesgo:** El usuario puede cancelar su pago por error.
   * **Sugerencia:** Cambiar "Confirmar" a verde y "Cancelar" a gris/rojo.

2. **Feedback Visual:** Al dar clic en "Pagar", el sistema no muestra un icono de carga (spinner).
   * **Riesgo:** El usuario puede dar clic varias veces pensando que no funciona, duplicando la transacción.

3. **Responsive Design:** En pantallas de celular, el formulario de tarjeta de crédito se corta.
   * **Riesgo:** Los usuarios móviles de Telrad no pueden completar sus RQ pagos.

### Checklist de UI validado:
- [x] Los campos obligatorios tienen un asterisco (*).
- [ ] Los mensajes de error son claros (No solo dice "Error", sino "Faltan dígitos en la tarjeta").
- [x] El logo de la empresa es visible en todo momento.
